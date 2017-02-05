---
layout: post
title: "Argl... j'ai failli mourir !!!"
date: 2003-09-26 22:19:21
author: Hoedic
comments: true
categories: 
---


Impossible de me connecter à mon interface de rédaction de message pendant toute l'après-midi. Finalement j'arrive à avoir le formulaire pour m'identifier, je rentre mon login, réponse de spip : *"L'identifiant « xxxxx » est inconnu."*

????

Je réessaie, pareil... encore une fois... rien à faire, il ne veut pas entendre parler de moi.

Je vais voir dans la base de données [mysql](http://www.mysql.com/) de quoi il en retourne... gloups : la table **auteur** n'est plus, n'est pas... enfin de toute évidence y a un gros soucis avec, pas même moyen d'accéder à sa structure.

Heureusement, sur la même base, j'ai un autre spip qui tourne pour site sur l'<a href="http://canada.ouvaton.org/" title="Destination Canada">immigration au Canada</a>. A tout hasard je droppe l'ancienne table qui ne marche plus et je la remplace par une copie modifiée de la table équivalente de Destination Canada et... ouf ! Ça marche.

Je sais pas ce que j'aurais fait sinon !!! :(