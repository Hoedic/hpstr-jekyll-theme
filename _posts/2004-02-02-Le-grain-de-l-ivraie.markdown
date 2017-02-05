---
layout: post
title: "Le grain de l'ivraie"
date: 2004-02-02 18:17:20
author: Hoedic
comments: true
categories: 
---


Voici mes statistiques de fréquentation depuis mon [déménagement]({{ site.url }}/2004/01/26/Demenagement) sur mon nouveau nom de domaine.

![Image]({{ site.url }}/images/evolution-visites-02-02-04.png)
<div class="photoattrib">Je tooooommmmmbe</div>



Comme on le voit, c'est la chute libre et faut bien dire que j'ai fait ce qu'il faut pour : j'ai uniquement fait une redirection pour la page d'accueil de mon ancien site, laissant une erreur pour les pages d'articles, le but étant de couper tout le trafic généré par les moteurs de recherches (qui souvent pointent un article directement et plus rarement la page d'accueil).

N'ayant pas d'analyseur de stats très précis, j'avais du mal à quantifier l'apport de Google dans nos quelques 150 visites par jour ; maintenant je peux le dire : beaucoup ! Puisque nous tournons désormais à quelques 30/40 visites par jour de vrais lecteurs :)

Comparativement, pour mon site sur le [Canada](http://mon-ile.net/canada/), la fréquentation n'a pas bougé. Dans ce cas-ci, comme Google est très important, j'ai fait une redirection page pour page (c'est là qu'on voit la puissance du module [rewrite](http://httpd.apache.org/docs/mod/mod_rewrite.html) d'Apache et de PHP ensemble). Sûrement une petite baisse  à prévoir le temps que Google se mette à jour, mais j'espère rien de bien énorme.

Et pour notre blog, c'est mieux ainsi. C'est mieux pour les internautes qui ne tombent plus sur un article pointant vers un flash débile quand ils cherchent "fumer tue" (mon premier référant avant le déménagement). C'est mieux parce qu'à la vitesse où grimpait la fréquentation, j'allais rapidement dépasser le volume autorisé et devoir payer plus. Enfin c'est mieux parce que ça limite une partie des saloperies qui vont avec un ranking élevé (toute proportion gardée) sous Google : troll, spam, pollution des statistiques et autres.

Reste à voir maintenant comment vont réagir les moteurs de recherche au fait que seuls quelques articles (ceux que je veux publics) soient en *index* alors que la page d'accueil et la majorité des articles sont en *follow, noindex*.