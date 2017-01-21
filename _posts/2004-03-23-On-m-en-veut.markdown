---
layout: post
title: "On m'en veut ?"
date: 2004-03-23 05:07:57
author: Hoedic
comments: true
categories: 
---


Bon voilà, je rentre de mon aikido, traaanquille, je me pose devant mon écran... quelques messages ICQ sont arrivés, je veux y répondre mais la connexion veut pas, mes messages restent scotchés au départ (Désolé aux messages auxquels j'ai pas répondu, mais ICQ est en grêve depuis). Pas moyen d'ouvrir une page web ni de recevoir un mail. Diagnostic poussé, le routeur s'est encore chié dessus.

Panel de config du routeur, il est persuadé d'être connecté. Soit. Bouton "release" pour le forcer à se reconnecter. Rien. Bouton "renew" (vaguement pareil), niet, queud'. Je vais voir la log et là surprise, elle est remplie : , , , , à peu près tout y est passé... pendant plusieurs heures en plus ! Surement qu'à la fin, il (le routeur) en a eu plein le cul et a laché la connexion. Finalement j'ai fait un reset puis il s'est reconnecté.

![Image]({{ site.url }}/images/hacker-flag_22-03-2004.jpg)


En brave bête qu'il est, le routeur m'a floodé d'e-mail d'alerte.

Bien que mon routeur semble détecter (et repousser ces attaques), je me demande toujours dans quelle mesure certaines ne passent pas au travers... d'autant plus que j'ai quand même quelques ports d'ouverts. Surtout ça me fatiguerait de devoir constamment reseter.

Mon routeur (décidément c'est sa fête ce soir... si avec ce message je ne devient pas premier dans Google pour le terme "routeur", je ne sais pas ce qu'il lui faut), donc mon routeur est sympa, il me donne l'adresse IP de la machine qui m'attaque : 0.0.0.0, 127.0.0.1 ou des adresses farfelues qui contiennent des 255. Ça m'aide beaucoup, merci. Ceci dit, toujours mon routeur m'a fait découvrir  avec un whois général, c'est assez pratique... enfin quand on a une IP valide !

Autre chose qui me chagrine : après mon reset, j'ai changé d'IP (phénomène rare chez Vidéotron) et il a à peine fallu plus d'une minute pour que les attaques recommencent. Comment il m'a retrouvé ce con ? À moins qu'il ne broadcaste la classe d'IP au complet auquel cas c'est logique que soit toujours concerné.

Toujours est-il que c'est assez chiant et je n'aime pas ça, moi !