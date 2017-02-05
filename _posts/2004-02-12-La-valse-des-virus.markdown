---
layout: post
title: "La valse des virus"
date: 2004-02-12 17:59:39
author: Hoedic
comments: true
categories: 
---


Alors que je me disais hier qu'on arrivait vers la fin de MyDoom qui est programmé pour arrêter de se répliquer le 12 février, ce qui devrait faire baisser assez nettement le nombre de courriel que je reçois, voilà-t-y pas qu'on remet ça.

Cette fois, il s'appelle *[DoomJuice](http://securityresponse.symantec.com/avcenter/venc/data/w32.hllw.doomjuice.b.html)* et il présente un étrange prolongement de [MyDoom]({{ site.url }}/2004/01/27/Le-virus-nouveau-est-arrive). En effet, DoomJuice utilise  un backdoor (ouverture d'une brèche de sécurité dans Windows (qui en est déjà truffé naturellement) permettant l'accès à distance) sur le port 3127 pour se répliquer. Ensuite, ce virus va s'amuser à attaquer les serveurs de Microsoft. Éventuellement, ça peut donner un accès quasi-illimité à votre ordinateur.

En d'autres termes, vérifier encore que vous n'avez pas MyDoom, et si vous découvrez que vous être contaminé par ce dernier, vous avez possiblement DoomJuice, auquel cas il faut passer un coup d'antivirus avec les dernières mise-à-jour. Attention car ce virus-ci, comme je l'ai expliqué, ne se transmet pas par e-mail, il utilise une faille de sécurité pour s'immiscer "par derrière", donc même si vous filtrez bien vos courriels entrant prenez garde !

Et enfin n'oubliez pas mettre à jour votre Windows parce que de nouvelles failles critiques ont été découvertes récemment. Oui, je sais, télécharger un patch de 10Mo toutes les semaines avec une connexion téléphonique c'est pas cool. Ben fallait prendre autre chose que Windows. Des unions de consommateurs devraient demander à Microsoft de rembourser les temps de connexions pour télécharger les patches (surtout en France où les communications locales sont payantes) ainsi que les dépassement de forfaits. C'est vrai après tout, quand on achète Windows, on ne signe pas pour devoir télécharger 1Go de patch par mois.

***

Étant donné que je passe un peu plus de temps sous Windows XP dernièrement... Et là j'ai pas fini ma phrases que certains me coupent *"Mais malheureux, pourquoi passes-tu plus de temps sous Windows ?*.  D'abord parce que je joue plus en ce moment, et ensuite parce que je cherche un boulot, ce qui me fait envoyer des tonnes de documents Word. Oui, je sais, OpenOffice fait très bien du Word, mais il me fucke complètement la mise en page de mon CV qui du coup dépasse de ses 3 pages alors ça me plait pas, alors je fais mes documents sous Microsoft Word et tant pis si ça ne vous plait pas ! Et puis je n'ai pas de compte à rendre sur l'utilisation de mon ordinateur à moi.

Bref, j'en ai profité pour me pencher un peu plus sur la sécurité de mon XP et je suis resté sur le cul de découvrir que le FTP et le serveur Web se lançaient par défaut ! Quand on sait le nid à merde qu'est un ISS non patché et les risquent que présente un FTP ouvert en permanence, on se demande bien pourquoi ces éléments sont activés par défaut. Y sont fous !