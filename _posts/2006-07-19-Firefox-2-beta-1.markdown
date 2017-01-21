---
layout: post
title: "Firefox 2 beta 1"
date: 2006-07-19 03:26:30
author: Hoedic
comments: true
categories: 
---


Pour ceux que cela intéresse, la version beta de Firefox 2 est . <strike>Notez qu'en l'installant, vous écrasez votre version précédente, donc ce n'est pas forcément une bonne idée, ça reste une béta</strike> Ah ben non, j'ai toujours moyen de lancer l'ancienne 1.5.0.4.


![Image]({{ site.url }}/images/5883_eff53e5b65_z_d.jpg)
<div class="photoattrib">Fireworks</div>



Sachez que si vous tenez à vos extentions, j'ai trouvé comment bidouiller pour que Firefox les accepte (mais ça augmente l'instabilité bien entendu). Cherchez le fichier install.rdf de l'extention et pour l'argument <code>maxVersion</code> mettez 2.* (<code>em:maxVersion="2.*"</code>). S'il y a un argument <code>em:updateURL</code>, supprimez la ligne. Ça marche pour l'extention Del.icio.us. À vos risques, bien entendu ! ;)

En revanche, j'aime pas trop la fonction de fermeture des onglets directement sur l'onglet. Y aurait-il quelqu'un qui sait si un élément de config permet de remettre un unique bouton de fermeture à droite ?

Sinon, la correction automatique dans les zones de texte, ça marche bien :)