---
layout: post
title: "Technicalités"
date: 2013-05-20 09:31
comments: true
author: Hoedic
image:
  feature: 2013-05-20_phasme.jpg
---


La construction du présent blogue va bon train. Quelques réflexions sur le sujet:

* Lorsque Octopress/Jekyll génère les pages publiques, il a la mauvaise habitude de tout générer plutôt que de ne procéder que les pages qui nécessitent de l'être. Ceci implique également les images et autres fichiers de supports qui sont recopiés dans la zone publique.
* Conséquence directe: les scripts de synchronisation à la rsync ont tendance à vouloir tout envoyer sur le serveur à chaque fois. Avec <code>lftp</code>, il est toutefois possible de s'en sortir mais cela nécessite quelques accrobaties.
* J'ai mis en place des redirections de l'ancien blogue vers le nouveau, page par page, incluant le fil atom. Cela m'a rappelé combien les configuration de Apache, notamment par htaccess, sont pénibles.
* Reste à complètement remiser l'ancien blogue sous forme d'un backup.
* Octopress nécessite encore quelques ajustements, notamment des dates et quelques termes en anglais qui trainent par endroits