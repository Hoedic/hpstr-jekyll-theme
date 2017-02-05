---
layout: post
title: "Routeur Wifi"
date: 2004-07-28 00:31:01
author: Hoedic
comments: true
categories: 
---


Le routeur Wifi qu'a commandé Ebb pour pouvoir se promener dans tout l'appart avec son iBook est arrivé hier. Pour ceux que ça intéresse, il s'agit d'un [SMC2804WBRP-G](http://www.smc.com/index.cfm?sec=Products&pg=Product-Details&prod=318&site=c). Pas de réelle difficulté à l'installation si ce n'est que les produits SMC semblent avoir un peu de mal à reconnaître les modem-cables de Videotron mais ça a fini par marcher.

Un problème demeure.

Le routeur peut faire serveur d'impression en se branchant par port USB.

Pas de soucis pour faire fonctionner l'imprimante branchée au routeur de ma boîte linux. En revanche, rien à faire avec Mac OSX qui envoie l'ordre d'impression quelque part dans le vide puis rien ne se passe. J'ai pourtant suivi les infos spécifiées sur 2 sites plus le site de SMC (ils disent tous de faire la même chose) mais rien n'y fait.

Certains d'entre vous ont-ils rencontrés des difficultés d'impression en LPD avec Mac OSX Panther ?

Ah oui, puis j'ai une question subsidiaire : ça marche comment les drivers d'impression sous Mac ? Parce que mon imprimante ne fait pas partie de la liste connue par OSX et l'installer fourni par HP tient absolument à installer l'imprimante en local. Comme il n'y a pas moyen de modifier les paramètres de l'imprimante une fois qu'elle est installée, bien je ne vois pas comment installer correctement ce truc...

À noter que ça me faisait pareil avec le [routeur précédent](http://www.smc.com/index.cfm?action=products_show_description&productCode=SMC7004ABR) (ça marchait à partir de Linux Fedora mais pas à partir du iBook), sauf que là pour diverses raisons de branchement, ce serait pratique si ça pouvait marcher.

À noter aussi que je pourrais utiliser Samba pour partager l'imprimante sur le réseau, le résultat serait à peu près le même. D'ailleurs j'ai essayé et ça marche. Seulement dans ce cas, on utilise les drivers Linux qui impriment de façon assez moche (sérieux, le grain d'impression est mauvais), qui cadrent mal les feuilles, qui est lent et ne fait pas de recto-verso. Puis faut que ma machine tourne.