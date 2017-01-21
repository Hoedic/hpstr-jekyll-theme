---
layout: post
title: "Problème de commentaire ?"
date: 2004-01-31 06:07:07
author: Hoedic
comments: true
categories: 
---


Un aimable lecteur m'a fait part d'un bogue de mon système de commentaire. Bizarrement, cette chose ne se semble se produire que sous Safari (éventuellement Camino, mais n'ayant pas *encore* de Mac, je ne peux pas tester).

Le bogue en question consiste en une redirection vers l'url *://commentaire* après avoir posté. J'attribue ça à l'absence de l'élément HTTP_REFERER dans la requête du navigateur mais je n'ai rien trouvé à ce sujet sur 'ternet, quelqu'un a-t-il des informations sur le sujet ?

Le problème est contourné, toutefois les clients n'envoyant pas d'*http_referer* n'auront pas le même comportement que les autres, tant pis, ça vous apprendra à utiliser un navigateur malpoli qui fait n'importe quoi !

(Et là certains vont me crier dessus en me demande pourquoi donc j'utilise *http_referer* pour poster un pauvre commentaire, ce à quoi je réponds... rien)