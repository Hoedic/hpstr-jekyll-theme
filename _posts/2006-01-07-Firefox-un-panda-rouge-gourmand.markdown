---
layout: post
title: "Firefox, un panda rouge gourmand"
date: 2006-01-07 18:19:06
author: Hoedic
comments: true
categories: 
---


Récemment, alors que je trouvais que mon laptop ramait sans raison (et qu'en effet j'étais rendu à 850Mo de mémoire utilisée), j'ai arrêté Firefox tout en suivant l'utilisation de la mémoire vive qui en quelques instant est retombée à 500Mo.

J'ai relancé mon brouteur et après avoir rouvert exactement toutes les fenêtres présentes avant fermeture (j'utilise SessionSaver), la consommation était seulement de 535Mo !

Ça donne ceci :

![Image]({{ site.url }}/images/firefox_07-01-2006.jpg)
<div class="photoattrib">Arrêt puis redémarrage de Firefox</div>



Suis-je le seul à constater ça ? On dirait qu'en cours d'utilisation, Firefox ne libère pas sa mémoire, fait du memory leak d'une manière ou d'une autre (et 300Mo de memory leak, c'est pas rien !). Je me demande si ce n'est pas la conséquence des mises en veille profonde du laptop ou d'autre chose (certaines extension comme session saver justement ?)

J'ai cherché sur Bugzilla et j'ai rien trouvé à ce sujet. Si quelqu'un connait la cause (et éventuellement une méthode de contournement :p)

Note : cependant, je ne lacherai jamais Firefox, ben' trop pratique, trop d'extensions très utiles. Comme l' Tristan récemment, Firefox est plus d'un navigateur, c'est une plateforme !

Update : j'ai finalement trouvé quelque chose dans bugzilla , je vais voir ce que ça donne :)