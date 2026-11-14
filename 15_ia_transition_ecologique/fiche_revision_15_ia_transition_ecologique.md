# Fiche de révision — Thème 15 (sujet croisé) : Intelligence artificielle et transition écologique

> **Sujet type** : « L'intelligence artificielle peut-elle être une alliée de la transition écologique des territoires ? »
>
> **Formulations voisines** : « Transition numérique et transition écologique : des transitions conciliables ? », « Les collectivités face à l'essor des centres de données », « Le numérique responsable dans les collectivités », « Innovation technologique et sobriété : un paradoxe pour l'action publique locale ? », « Qui décide de l'implantation des grands projets sur un territoire ? ».
>
> **Thèmes croisés** : 06 (transition écologique), 07 (mutations de l'administration), 05 (décentralisation : qui décide ?), 03 (démocratie locale : contestations), 13 (développement économique), 02 (finances).

---

## 1. Définitions à maîtriser

| Notion | Définition à retenir |
|---|---|
| **Intelligence artificielle** | Selon le règlement européen du 13 juin 2024 : un **système automatisé** qui, à partir des données qu'il reçoit, **déduit** comment produire des prédictions, des contenus, des recommandations ou des décisions. |
| **IA spécialisée ou prédictive / IA générative** | L'IA **spécialisée** remplit une tâche précise, comme détecter une fuite, classer une image ou prévoir une consommation. Elle est souvent **sobre**. L'IA **générative** (ChatGPT, Mistral, Albert) produit du texte ou des images. Elle est polyvalente mais **beaucoup plus énergivore**. **C'est la distinction clé de la copie.** |
| **IA frugale** | IA conçue pour **limiter ses besoins** en données, en calcul, en énergie et en matériel, et utilisée seulement quand elle est **pertinente** (référentiel AFNOR Spec « IA frugale », juin 2024, piloté par l'Ecolab du ministère de la Transition écologique). |
| **Centre de données (data center)** | Bâtiment qui héberge des serveurs. Il consomme de l'**électricité**, souvent de l'**eau** pour le refroidissement, et du **foncier**. Il produit de la **chaleur fatale**. |
| **Chaleur fatale** | Chaleur produite par une activité et non utilisée, qui peut être **récupérée** dans un réseau de chaleur. |
| **Effet rebond (paradoxe de Jevons, 1865)** | Un gain d'efficacité fait baisser le coût d'usage et **augmente** la consommation totale. |
| **Numérique responsable** | Démarche qui réduit l'**empreinte environnementale** du numérique (écoconception, allongement de la durée de vie des équipements, sobriété des usages) et renforce son **utilité sociale**. |
| **Jumeau numérique** | Réplique numérique d'un territoire, alimentée par des données, qui permet de **simuler** des scénarios : îlots de chaleur, inondations, ZAN. |

**Distinction clé** : l'IA **au service** de la transition (*AI for green*) et l'IA **comme charge** pour la transition (*green AI*). Une bonne copie traite les deux.

---

## 2. Cadre juridique

### Textes européens
- **Règlement (UE) 2024/1689 sur l'IA du 13 juin 2024** (AI Act) : il classe les systèmes par niveau de **risque**. Depuis le 2 août 2025, les fournisseurs de modèles d'IA à usage général doivent **documenter leur consommation d'énergie**.
- **Directive (UE) 2023/1791 du 13 septembre 2023 relative à l'efficacité énergétique** : les centres de données de plus de 500 kW doivent **déclarer leur performance énergétique**. Ceux de plus de 1 MW doivent **valoriser leur chaleur fatale**, sauf impossibilité technique ou économique.

### Lois françaises
- **Loi REEN n° 2021-1485 du 15 novembre 2021** (réduire l'empreinte environnementale du numérique) : les **communes et EPCI de plus de 50 000 habitants** doivent adopter une **stratégie numérique responsable** au plus tard le **1er janvier 2025** (décret du 29 juillet 2022). Elle a créé l'observatoire ADEME-Arcep.
- **Loi du 23 décembre 2021** : elle confie à l'**Arcep** un pouvoir de collecte de données environnementales sur le numérique.
- **Loi AGEC du 10 février 2020, art. 55** : une part (**20 %**) des équipements informatiques achetés par les acheteurs publics doit être **reconditionnée ou issue du réemploi**.
- **Loi Climat et résilience du 22 août 2021, art. 35** : depuis **août 2026**, **tous les marchés publics** doivent comporter une **considération environnementale** (critère ou condition d'exécution).
- **Loi n° 2026-403 du 26 mai 2026 de simplification de la vie économique** :
  - les **centres de données de dimension industrielle** peuvent être qualifiés de **projets d'intérêt national majeur (PINM)**, ce qui permet à l'État de mettre en compatibilité les documents d'urbanisme et accélère le raccordement électrique ;
  - en contrepartie, un permis de construire de data center **peut être refusé** lorsque le territoire connaît des **tensions structurelles sur la ressource en eau** ;
  - une **réservation de capacité de raccordement** est créée pour les grands consommateurs d'électricité ;
  - **CC, 2026-903 DC, 21 mai 2026** : censure de **25 cavaliers législatifs**, dont la **suppression des ZFE** et l'**assouplissement du ZAN**, et censure partielle de l'article sur les PINM. ⚠️ Pour le détail, dis « une partie des dispositions ».
- **Code des relations entre le public et l'administration, art. L. 311-3-1** : l'usager doit être informé lorsqu'une décision individuelle est fondée sur un **traitement algorithmique**.

---

## 3. Chiffres et faits d'actualité (2025-2026)

### L'empreinte du numérique et de l'IA
- **ADEME-Arcep (janvier 2025, données 2022)** : le numérique représente **4,4 % de l'empreinte carbone** de la France et **11 % de la consommation électrique**. Cette empreinte se répartit entre les **terminaux (50 %)**, les **centres de données (46 %)** et les réseaux (4 %).
- **RTE** : les data centers consomment environ **10 TWh**, soit environ **2 %** de la consommation électrique française, et **23 à 28 TWh possibles en 2035**. Les data centers raccordés récemment n'utilisent en moyenne que **20 % de la puissance réservée**.
- **ADEME, étude prospective (6 janvier 2026)** : en scénario tendanciel, la consommation des data centers pour les usages français serait **multipliée par 3,7 d'ici 2035**, et par 4,4 en comptant les data centers étrangers. L'ADEME propose cinq scénarios, dont « **Coopérations territoriales** » (projets concertés avec les territoires) et « Génération frugale » (moratoire).
- **ADEME, avis du 22 juillet 2026** sur l'IA générative : des impacts environnementaux « **importants** » ; l'agence demande de la **transparence** et un futur **label** de frugalité. Formule à citer : l'IA n'a « **rien d'artificiel ni d'immatériel** ».
- **Agence internationale de l'énergie (avril 2025)** : la consommation mondiale des data centers passerait de **415 TWh en 2024 à environ 945 TWh en 2030**, soit un **doublement**.
- **Arcep, rapport du 21 mai 2026** sur l'IA générative et l'environnement : **48 % des Français** utilisent l'IA générative (2025). Il formule **9 recommandations**, dont l'**éco-conditionnalité de la commande publique** et une « **implantation territoriale concertée** des centres de données ».
- **Eau** : le Sénat cite une estimation de **4,2 à 6,6 milliards de m³** d'eau consommés par l'IA dans le monde en 2027. ⚠️ En France, les chiffres disponibles sont **faibles et contestés** : reste qualitatif.

### Les data centers dans les territoires
- **Sommet pour l'action sur l'IA (Paris, 10 et 11 février 2025)** : **109 Md€** d'investissements privés annoncés, **35 sites** identifiés comme « prêts à l'emploi » pour des data centers, et lancement d'une **coalition pour une IA durable**.
- **Campus IA de Fouju (Seine-et-Marne)** : présenté comme le **plus grand d'Europe**, avec **1,4 GW** à terme (fonds émirien MGX, Bpifrance, Mistral AI, Nvidia). La pétition contre le projet a recueilli environ 70 000 signatures.
- **SoftBank (Choose France, juin 2026)** : **3,1 GW** sur trois sites des Hauts-de-France (Loon-Plage, Bouchain, Bosquel) d'ici 2031.
- **Google dans l'Indre** : **195 hectares** réservés près de Châteauroux. La **maire d'Étrechet** et plusieurs élus ont **démissionné**, en conflit avec la communauté d'agglomération.
- **Contestation** : l'association marseillaise « Le Nuage était sous nos pieds » recense **au moins 36 oppositions citoyennes pour 68 projets**. En **octobre 2026**, quatorze collectifs ont publié une **tribune dans *Le Monde*** et lancé la pétition « **Data centers partout, démocratie nulle part** », qui demande une **pause**. À **Rovaltain (Drôme)**, un permis de data center a été **suspendu en référé** en 2026.
- **Récupération de chaleur** : le data center d'Equinix à **Saint-Denis** chauffe le **Centre aquatique olympique** et le quartier, et **Val-d'Europe (Seine-et-Marne)** est chauffé par un data center depuis 2012. En France, cette chaleur reste **très peu valorisée**.

### L'IA au service de la transition dans les collectivités
- **Programme TID-DIAT** (« démonstrateurs d'IA frugale pour la transition écologique des territoires ») : **France 2030**, environ **40 M€**, opéré par la **Banque des Territoires** avec l'Ecolab. Les rencontres nationales des lauréats ont eu lieu à **Dijon** les 13 et 14 janvier 2026.
- **« Territoires d'IA »** (Banque des Territoires, 21 mai 2026) : objectif de **100 000 agents** utilisateurs d'ici 2030, avec la mutualisation des cas d'usage.
- **Rapport du Sénat n° 379 (2024-2025)**, délégation à la prospective, « IA et environnement » (Christine Lavarde, Nadège Havet, Jean-Baptiste Blanc, février 2025) : l'IA est un **outil d'aide à la décision** environnementale, mais elle est **très consommatrice**. Il recommande d'ouvrir et de **qualifier les données**, de privilégier les **IA spécialisées plutôt que polyvalentes**, de **mutualiser** et de **recruter** des profils data.
- **Fonds vert** : environ **650 M€** en autorisations d'engagement dans le PLF 2026, contre 2 Md€ en 2023 (voir le thème 06).

---

## 4. Trois exemples concrets

1. **Noisy-le-Grand (Seine-Saint-Denis), projet Récital (TID-DIAT)** : une IA analyse **200 bâtiments publics**, formule 355 recommandations et réduit la consommation de **7 à 9 % sans investissement**. Elle simule aussi un plan de travaux sur dix ans. C'est l'**IA alliée** : sobre, ciblée, utile au budget comme au climat.
2. **L'IGN et la mesure du ZAN** : l'occupation des sols à grande échelle (OCS GE) est produite par IA, « **trois fois plus vite pour trois fois moins cher** » selon son directeur général. Elle sert à mesurer l'artificialisation dans tous les territoires. L'IGN, le Cerema et le BRGM construisent un **jumeau numérique** national. C'est l'IA au service de la **planification écologique**.
3. **Les data centers de Fouju, de Châteauroux et d'Étrechet** : des projets de plusieurs centaines d'hectares et de plus d'un gigawatt, décidés au niveau national ou par des investisseurs étrangers, désormais **PINM**. Ils suscitent conflits d'usage (eau, électricité, foncier agricole), contestations citoyennes et démissions d'élus. C'est l'**IA charge**, qui pose la question de **qui décide sur le territoire**.

**Exemples de secours** :
- la **détection des fuites d'eau** : un litre d'eau potable sur cinq est perdu dans les réseaux. Leakmited et Mission 90+ interviennent avec le syndicat du Brivadois, et le Sicoval (Haute-Garonne) détecte aussi ses fuites par IA ;
- **I-Arbre** (Grand Lyon, coopérative Telescoop, **open source**) : un score de « plantabilité » qui aide à végétaliser contre les **îlots de chaleur**, testé à Grenoble et à Rennes ;
- le **SDIS d'Indre-et-Loire** : une douzaine de caméras à IA installées sur des châteaux d'eau détectent les départs de feu, pour 1,8 M€ financés par le **Fonds vert**. Dans l'**Aude**, des dispositifs comparables ont produit **trop de faux positifs** au départ ;
- **Bourg-en-Bresse** : des caméras à IA sur les véhicules municipaux cartographient les déchets et la propreté ;
- **Urba IA** (Saclay) : simulation de l'impact carbone et biodiversité des projets d'urbanisme ;
- l'abandon de **Self Data** (Grand Lyon), faute de recrutement et de budget : les **limites** des projets locaux.

---

## 5. Arguments contradictoires

### ✅ OUI, l'IA peut être une alliée
- Elle permet d'**optimiser** les réseaux et les bâtiments : énergie, eau, déchets, éclairage, mobilités.
- Elle aide à **connaître** le territoire : artificialisation, îlots de chaleur, biodiversité, trait de côte.
- Elle permet d'**anticiper** les risques : feux, inondations, canicules, prévisions météorologiques.
- Elle **simule** les décisions grâce aux jumeaux numériques, et aide à **arbitrer** le ZAN.
- Elle libère du temps d'agent et peut générer des **économies** dans un contexte budgétaire contraint.
- Les **soutiens** existent : France 2030 (TID-DIAT), Territoires d'IA, Ecolab, Fonds vert.

### ❌ NON, elle peut aussi être une menace
- Son **empreinte** est matérielle et croissante : électricité, eau, métaux, déchets électroniques.
- Elle produit un **effet rebond** : les gains d'efficacité sont annulés par la multiplication des usages.
- Les **data centers** créent des **conflits d'usage** avec le ZAN, l'eau, l'électrification des transports et de l'industrie, et les terres agricoles.
- Les collectivités sont **dépossédées** : PINM, décisions de l'État et d'investisseurs étrangers, comme à Étrechet.
- Elle crée des **dépendances** à des fournisseurs non européens, ce qui pose la question de la **souveraineté** des données.
- Les projets locaux sont **fragiles** : faux positifs, coûts, réplicabilité faible, ingénierie inégale entre grandes et petites collectivités.
- Elle soulève des risques démocratiques : **opacité** des algorithmes et décisions non concertées.

---

## 6. Problématique et plan détaillé

**Problématique** :
> L'intelligence artificielle, qui offre aux collectivités des outils inédits pour conduire la transition écologique, peut-elle devenir leur alliée, alors que son propre développement accroît la pression sur l'énergie, l'eau et le foncier des territoires ?

**I. Une alliée potentielle : l'IA offre aux collectivités des outils nouveaux pour la transition écologique**
- **A.** Optimiser la gestion des ressources et des services publics : énergie des bâtiments (Noisy-le-Grand), eau (fuites), déchets (Bourg-en-Bresse), mobilités.
- **B.** Mieux connaître, planifier et protéger les territoires : ZAN (IGN), jumeau numérique, îlots de chaleur (I-Arbre), risques (SDIS 37), soutien de France 2030 (TID-DIAT).

**II. Une alliée ambivalente, qui ne sert la transition que si elle est frugale et démocratiquement maîtrisée**
- **A.** Une empreinte matérielle croissante, qui pèse sur les territoires et échappe aux collectivités : chiffres de l'AIE, de l'ADEME et de RTE, data centers (Fouju, Étrechet), PINM, contestation, fragilité des projets locaux.
- **B.** Une IA frugale, concertée et mutualisée : loi REEN, IA frugale, commande publique, implantation concertée (Arcep), refus pour cause de tension hydrique, chaleur fatale (Saint-Denis), mutualisation (Territoires d'IA).

---

## 7. Auteurs et références

- **Ivan Illich**, *La Convivialité* (1973) : un outil est « convivial » s'il reste **maîtrisé** par ses usagers, et il devient contre-productif au-delà d'un certain seuil.
- **Jacques Ellul**, *Le Système technicien* (1977) : la technique tend à s'autonomiser des fins humaines.
- **Hans Jonas**, *Le Principe responsabilité* (1979) : la puissance technique crée une **responsabilité** envers les générations futures.
- **William Stanley Jevons** (1865) : le paradoxe de l'effet rebond.
- **Kate Crawford**, *Contre-atlas de l'intelligence artificielle* (2021) : l'IA est une **industrie extractive** de minerais, d'énergie, d'eau et de travail.
- **Guillaume Pitron**, *L'Enfer numérique* (2021) : la matérialité cachée du numérique.
- **Commission européenne** : la « **double transition** » verte et numérique, censée se renforcer mutuellement.

---

## 8. Pièges à éviter

- ❌ Traiter l'IA comme un bloc. Il faut **distinguer** l'IA spécialisée et sobre de l'IA générative énergivore.
- ❌ Écrire un catalogue de start-up et d'outils sans démonstration. Chaque exemple doit **prouver** une idée.
- ❌ Oublier les **collectivités**. Le sujet porte sur les territoires : il faut parler de leurs compétences (urbanisme, énergie, eau, déchets), de leurs moyens et de leur pouvoir de décision face aux data centers.
- ❌ Être technophobe ou technophile. Le jury attend une réponse **conditionnelle** : « oui, à condition que… ».
- ❌ Donner des chiffres d'eau précis pour la France. Ils sont contestés : reste qualitatif.

---

## 9. Passerelles

| Thème | Ce que tu peux réutiliser |
|---|---|
| Thème 06, transition écologique | ZAN, PCAET, Fonds vert, adaptation, TRACC |
| Thème 07, administration | Territoires d'IA, chartes éthiques, AI Act, cybersécurité, illectronisme |
| Thème 05, décentralisation | Les PINM et la recentralisation des décisions d'aménagement, la loi « État local » |
| Thème 03, démocratie | « Data centers partout, démocratie nulle part », la concertation, la démission d'Étrechet |
| Thème 13, économie | Les 109 Md€, Choose France, la concurrence entre territoires pour attirer les investissements |
| Thème 02, finances | Les économies d'énergie grâce à l'IA, la fiscalité des data centers (CFE, foncier bâti) |

---

## 10. Auto-test

1. Quelle différence fais-tu entre l'IA spécialisée et l'IA générative du point de vue environnemental ?
2. Que doivent faire les communes de plus de 50 000 habitants depuis le 1er janvier 2025 (loi REEN) ?
3. Qu'a changé la loi du 26 mai 2026 pour les data centers ? Quelle contrepartie a été prévue pour l'eau ?
4. Cite trois chiffres sur l'empreinte du numérique (ADEME-Arcep, RTE, AIE).
5. Cite deux usages vertueux de l'IA dans une collectivité, et un projet de data center contesté.
6. Récite ta problématique et ton plan.
