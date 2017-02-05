---
layout: post
title: "Ping-O-Blog"
date: 2003-10-12 05:48:43
author: Hoedic
comments: true
categories: 
---


<h2 align="center">Tout pour annoncer votre blog ;)</h2>

**<a href="ping/telecharger.html" target="_blank" title="Installez Ping-O-Blog chez vous">Télécharger les sources en PHP</a>**

**<a href="form-ping.html" target="_blank" title="Le formulaire">Le formulaire</a>**

**Le principe** - Certains sites internet dédiés au weblogues sont des agrégateurs de billets, comme <a href="http://www.weblogues.com" title="Vive les blogs francophones !">weblogues.com</a>. Certains de ces sites fonctionnent selon le principe des <i>pings</i> : lorsqu'un site se met à jour, il envoie un "ping" pour signaler le nouveau message.

**Ce qui existe déjà** - <a href="http://www.la-grange.net" title="Karl and cow">Karl</a> a bien fait un [script PERL](http://www.la-grange.net/web/pingWeblog) qui rempli très bien cette fonction et qui fonctionne très bien... en tous cas, il fonctionne très bien en mode console mais je n'ai pas réussi à le faire executer automatiquement lorsque je postais un billet (faut dire que je suis une tanche en Perl/CGI). Je n'ai pas trouvé d'équivalent en PHP, je me suis donc dit que j'allais adapter son script et accessoirement le rendre accessible par un formulaire tel que c'est proposé <a href="form-ping.html" target="_blank" title="Le formulaire">ici</a>(Merci de ne pas abuser de ce formulaire en postant plusieurs fois une même mise-à-jour de votre blog, faute de quoi je serai obligé d'en limiter l'accès).

**Version béta** - Pour l'heure, le script est en version de test, donc ne vous étonnez pas s'il plantouille parfois et d'ailleurs, j'attends votre aide pour me permettre de trouver les erreurs. Tout comme le script de Karl, le mien ping weblogues.com, weblog.com, blo.gs et joueb.com (Niutopia).

**Pour qui ?** - Bien entendu, ce script s'adresse aux personnes dont le site ne ping pas automatiquement les quatre services listés plus haut. Avant d'utiliser le formulaire je vous invite donc à vérifier que votre site ne figure pas sur ces différents sites lorsque vous mettez votre blog en ligne.

**Ping quoi ?** - Pour l'heure, je me suis limité aux sites listés par script de Karl, mais si vous connaissez d'autres sites qui supportent les pings XMLRPC, vous pouvez m'en faire part. Toutefois, vous remarquerez que le script peut mettre plusieurs dizaines de secondes pour afficher le résultat, notamment parce que weblogues.com et weblog.com mettent énormément de temps à répondre et je ne pense pas que j'ajouterai de nouveaux site à long temps de réponse.

**Credits** - En plus d'utiliser la logique du script de Karl, mon process est basé sur la librairie XMLRPC de [Keith Devens](http://www.keithdevens.com/software/xmlrpc/) et nécessite un PHP avec XMLRPC pour être executé.

<h2 align="center">Le formulaire de ping a déménagé <a href="form-ping.html" target="_blank" title="Le formulaire">ici</a></h2>
