---
layout: post
title: "Netscape et le CSS"
date: 2004-03-20 19:23:45
author: Hoedic
comments: true
categories: 
---


Avec un autre maudit Français, nous allons, peut-être, hériter d'un contrat pour faire le site Internet d'une PME (et on vise aussi le site d'une plus que PME, leur site existe déjà mais... il est moche -enfin, y a matière à amélioration). Bon, je sais c'est pas mon boulot webdesigntruc, tout ça, tout ça, mais ça nous dépannerait bien... puis j'aime bien faire des sites Internet... puis je n'hésite pas à dire que je me débrouille mieux que pas mal de travailleurs autonomes dont c'est, soi-disant, la formation (j'en ai vu à l'action, je sais de quoi je parle).

Enfin bref, c'est pas le sujet. Voilà, commençant à réfléchir au design qu'on pourrait proposé et même plus généralement à l'approche à privilégier, j'ai décidé de télécharger Netscape 4.7 car paraît-il qu'il y a encore des gens pour l'utiliser et je me suis dit qu'un site d'entreprise devait être regardable (et pas trop moche) par tout le monde (y a rien qui m'agace plus qu'un message qui me dit que je ne peux pas regarder un site parce que je suis sous autre chose qu'IE, grrr).

J'installe Netscape, et je vais voir notre site, et là *"AAAAAAAAAAAAAAHHHHhhhhhh !"*, c'est tout gris, plus de mise en page, plus rien. Effectivement Netscape éprouve certaines difficultés avec le CSS.

![Image]({{ site.url }}/images/mon-ile_netscape-20-03-04.jpg)
<div class="photoattrib">Chez nous version Netscape 4.7</div>



Bon, mais alors, comment qu'on fait ? Est-ce qu'on prend en compte Netscape 4.x pour faire notre truc ? Et peut-on espérer faire quelque chose en CSS qui a du sens avec Netscape ?

Malgré tout j'ai trouvé des pages avec du CSS qui n'étaient pas toutes grises, celle de  par exemple, mais la mise en page n'est plus trop au rendez-vous. Pour les sites professionnels, nombreux sont ceux qui n'utilisent pas de CSS ni même de version HTML claire, mais ils sont généralement correctement affichés. Mentions spéciales à Libé et Le Monde qui ne s'ouvrent pas !

Visiblement l'incorporation du fichier .css avec un @import fonctionne très mal (d'ailleurs, je me demande encore pourquoi j'ai fait comme ça !), mais c'est le support css qui est plus généralement en cause.

Alors on fait quoi ? On s'essaie avec un CSS "light", on ignore les utilisateur Netscape 4.7 ou on laisse le client choisir (solution un peu facile :p) ?