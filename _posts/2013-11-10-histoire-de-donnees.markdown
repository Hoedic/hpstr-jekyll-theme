---
layout: post
title: "Histoires de données: les accidents de la route"
date: 2013-11-10 12:46
comments: true
author: Hoedic
image:
  feature: 2013-11-10-super-velo.jpg
  credit: "Vancouver, 19 février 2013"
---


Attendu par certains (dont moi), la Table québécoise de la sécurité routière a publié son [troisième rapport de recommandations](http://www.mtq.gouv.qc.ca/portal/page/portal/Librairie/Publications/fr/salle_presse/2013/D%E9p%F4t%20troisi%E8me%20rapport%20de%20la%20TQSR/TQSR_rapport_complet_web.pdf) assorti de 23 recommandations. Les-dites recommandations ne placent vraiment pas la barre très haute, mais là n'est pas mon point.

Regardons la recommandation 8:

> Rappeler aux gestionnaires de réseaux la nécessité d’assurer une veille de la performance des intersections, notamment sur le plan des statistiques relatives aux accidents ou aux situations particulières qui surviennent et qui concernent plus spécialement le virage à droite au feu rouge.
> <div class="attrib">Troisième rapport de recommandations, Table québécoise de la sécurité routière</div>


On apprend par ailleurs que les données proviennent de la SAAQ, compilées par le MTQ. Ça tombe bien, ce sont les mêmes données que celles que nous avons utilisé pour la [carte d'accidents](http://www.montrealgazette.com/news/road-safety/map/index.html) de The Gazette. Autant dire ce qui est, la qualité de ces données est plus que discutable. Dans notre cas, 30% des données étaient inutilisables (cas typique: la localisation de l'accident contenait seulement une rue, sans intersection ni numéro de rue) et le reste nécessitait une masse de travail conséquente. Un expert en transport de la Ville de Montréal m'a confirmé qu'ils utilisaient ce même jeu de données pour évaluer les intersections qui devaient être améliorées et qu'ils devaient eux aussi passer un temps considérable à normaliser les données.

> Il n’en demeure pas moins que, depuis l’entrée en vigueur du [virage à droite sur feu rouge], 6 décès, 34 blessés graves et 864 blessés légers ont été associés à cette manœuvre. Quant aux 6 personnes décédées, elles étaient toutes âgées de 65 ans et plus.
> <div class="attrib">Ibid</div>

Possiblement que le MTQ a eu accès à des données plus riches que ce que nous avions obtenu via une demande d'accès à l'information. Il n'en reste pas moins que je me permets de douter de l'exactitude d'un tel décompte.

⁂

Quand on parle de données représentant des faits, il est primordiale de comprendre comment ces données sont "créées". En l'occurrence, les données de la SAAQ proviennent des rapports de police. Or, plusieurs cyclistes ont récemment souligné que lors d'accidents impliquant des cyclistes, aucun constant d'accident n'avait été fait. C'est notamment le cas pour les accidents de "[dooring](http://www.cbc.ca/news/canada/montreal/cyclists-say-more-needs-to-be-done-to-prevent-dooring-1.2074231)" où la police insiste pour dire que ce n'est pas un accident de la route. En l'absence de constat d'accident... l'accident n'existe pas.

Un de mes projets de rêve serait d'étudier combien d'organisations différentes se retrouvent à retravailler cette même information et ce que cela représente en temps perdu et en différences dans le résultat final. Le summum serait de remonter certaines informations jusqu'à leur source, le constat d'accident (ou son absence). Cela permettrait surement de confirmer que les données utilisées pour étayer un tel rapport sont douteuses.

En tout état de cause, il s'agit de données qui devraient être rendues publiques selon une politique de données ouvertes, pour permettre aux organisations et personnes impliquées dans ces questions de faire leur propre analyse.

⁂

> In 1720, traffic fatalities from "furiously driven" carts and coaches were named the leading cause of death in London (eclipsing fire and "immoderate quaffing")
> <div class="attrib">Traffic - Why we drive the way we do (and what is says about us), Tom Vanderbilt</div>

