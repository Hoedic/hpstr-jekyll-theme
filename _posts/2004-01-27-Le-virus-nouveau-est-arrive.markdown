---
layout: post
title: "Le virus nouveau est arrivé !"
date: 2004-01-27 23:58:01
author: Hoedic
comments: true
categories: 
---


Son petit nom c'est *Doom* ou encore *W32.Novarg.A@mm*, même principe que d'habitude : se propage par mail et crée un backdoor (faille dans le système permettant l'intrusion à distance), en plus de préparer une attaque de type DoS le 12 février prochain.

La plus grande prudence est de rigueur dans les mails que vous ouvrez. Les courriels contaminés se présentent sous forme de messages d'erreur comme on en reçoit quand un destinataire n'est pas accessible. C'est sûrement cette caractéristique qui fait que ce virus fonctionne très bien, donc prudence sur les emails d'erreur.

Les systèmes touchés sont tous les windows sans exception avec une prédominance pour ceux utilisant outlook express, le virus est véhiculé dans un fichier joint de 22,258 octets avec comme extention .pif, .scr, .exe, .cmd, .bat, ou .zip.

Le virus crée un fichier Shimgapi.dll, c'est un moyen facile pour vous de vérifier si vous êtes infectés. Pour plus d'info : [Symantec](http://securityresponse.symantec.com/avcenter/venc/data/w32.novarg.a@mm.html).

J'ai regardé vite fait ce que proposait Thunderbird en matière de filtre. S'il est assez intelligent pour le junk mail, je n'ai rien trouvé pour les virus. L'idéal serait surement une fonction permettant de tester les attachements selon des critères précis comme la taille du fichier (puisqu'on l'a très exactement là). Un filtre sur les extentions ne serait pas de trop non plus, franchement je ne reçois jamais d'image .pif et encore moins d'écran de veille (.scr), et je ne parle pas de fichiers de commande DOS (.cmd, .bat), quant aux executables (.exe), je les fous directement à la poubelle en général, j'ai pas confiance en ces choses là.

Ayant Thunderbird et roulant sous Linux la majorité du temps, je ne me sens pas trop vulnérable à ces virus-ci, c'est juste que ça me fatigue de recevoir tous ces messages et que je ne serais pas contre le fait que ces virus partent à la poubelle directement.

Le top serait un module Thunderbird qui se connecte à un serveur pour récupérer un liste de signatures de fichiers joints vérolés pour ensuite faire le tri sur cette base. (y a surement des antivirus qui font ça très bien, mais surement pas sous Linux, puis j'ai pas d'antivirus sous Windows, c'est beaucoup trop contraignant comme chose).