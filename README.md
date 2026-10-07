# Que nous apprend notre adresse sur notre santé ?

**Équipe :** Evann Hislers et Mathys Gauthier  
**Défi :** Odissé Dataviz Challenge 2026, défi 3 — Inégalités sociales et territoriales de santé

## Notre question

Que peut nous apprendre notre adresse sur les inégalités de santé, et que ne permet-elle pas d'expliquer ?

## Notre visualisation

Notre site est un récit interactif que l'on fait avancer en défilant. Les cartes changent de mesure et d'échelle au fil de la lecture : nous partons des départements français, puis nous entrons dans onze communes autour de Gien. À la fin, le lecteur peut rechercher sa propre commune et la comparer à une autre. Chaque chiffre conserve l'échelle à laquelle il a été publié.

**1. Une carte de santé ne raconte pas toute l'histoire.** Nous ouvrons avec le diabète traité par médicament, mesuré par département en 2023. En Seine-Saint-Denis, son taux corrigé des différences d'âge est de 8,21 %. La carte devient ensuite celle de la pauvreté. En 2023, celle-ci atteint 29,5 % dans le même département. Mais les deux géographies ne se superposent qu'en partie : parmi les 20 départements aux valeurs les plus élevées pour chaque mesure, seuls 9 figurent dans les deux groupes. Le lecteur voit ainsi un rapprochement possible, puis ses limites.

**2. Les écarts existent aussi entre personnes.** Deux barres remplacent la carte pour présenter le Baromètre 2024 de Santé publique France. Dans cette enquête, 4,5 % des adultes se disant financièrement à l'aise déclarent un diabète, contre 9,3 % de ceux disant connaître des difficultés financières. Ces résultats nationaux concernent des personnes de 18 à 79 ans et un *diabète déclaré* : ils ne sont pas la version détaillée de la carte départementale du *diabète traité*.

**3. Changer d'indicateur change le portrait d'un territoire.** Trois colonnes se succèdent pour la grossesse : couverture sociale, entretien prénatal précoce et prématurité. L'entretien concerne 33,5 % des femmes comptées en Seine-Saint-Denis, contre 80,7 % dans le Finistère ; la Haute-Marne atteint 10,4 % de naissances prématurées. Puis trois cartes de prévention suivent la Somme : elle se classe 14e sur 96 pour la vaccination HPV des filles, 22e sur 94 pour le dépistage du sein et 88e sur 94 pour le dépistage colorectal. Les publics et les actes diffèrent ; il ne s'agit pas d'un palmarès général de la prévention.

**4. Descendre à l'échelle communale rend d'autres écarts visibles.** La carte zoome sur les onze communes de la communauté de communes Giennoises. Un indice publié par Odissé situe le contexte social de chacune par rapport aux communes de France. Gien et Coullons appartiennent au groupe des 20 % de communes les plus défavorisées ; Boismorand et Le Moulinet-sur-Solin, à celui des 20 % les plus favorisées. Sans changer les contours, les couleurs représentent ensuite l'accès potentiel à un cardiologue. Cet indicateur de 2019 varie de 5,75 à 9,50 contacts potentiellement accessibles par an pour 100 habitants dans les onze communes. Il estime une offre accessible, pas des consultations effectivement obtenues.

**5. Que signifie cette accessibilité sur le terrain ?** Nous avons retenu la cardiologie comme exemple d'accès à une spécialité parce qu'un indicateur est disponible à la commune et que les adresses d'exercice peuvent être situées sur une carte. Chaque point représente une adresse retenue dans l'Annuaire Santé, pas un cardiologue unique. Les points apparaissent autour de Gien, puis un trajet routier estimé relie le centre de la commune à un lieu retenu à La Bussière : 15,2 minutes en voiture. Des zones de 15, 30, 45 et 60 minutes montrent ensuite ce que l'on peut atteindre depuis ce même point de départ, sans s'arrêter aux frontières administratives. Ces calculs ne représentent ni le trajet depuis chaque domicile ni la disponibilité de rendez-vous. La séquence ne prétend pas expliquer les maladies cardiovasculaires par la distance aux soins.

**6. Et chez vous ?** Le lecteur recherche une commune, explore les indicateurs disponibles et peut comparer deux lieux. Sur ordinateur, les cartes sont côte à côte ; sur téléphone, les fiches se suivent et un bouton permet de passer d'une carte à l'autre. L'outil précise toujours si un chiffre concerne le département, l'intercommunalité ou la commune. Par exemple, la mesure de cardiopathie ischémique issue d'Odissé reste celle de l'intercommunalité : la recherche d'une commune ne la transforme pas en statistique communale. Le fond de carte détaillé couvre la France hexagonale ; lorsqu'une commune ultramarine est recherchée, les chiffres disponibles sont présentés sans lui attribuer une couleur sur ce fond.

## Ce que nous cherchons à montrer

Une adresse permet de situer des écarts de santé, de conditions sociales, de prévention et d'accès aux soins. Elle ne donne ni le parcours d'une personne ni la cause d'une maladie. Nous avons donc choisi de montrer plusieurs cartes et leurs décalages, plutôt que de fabriquer un score unique ou d'attribuer l'état de santé d'un territoire à un seul facteur.

## Les données utilisées

| Source et jeu de données | Période et échelle | Rôle dans le récit |
| --- | --- | --- |
| [Odissé — diabète traité](https://odisse.santepubliquefrance.fr/explore/assets/diabete-prevalence-departement/) | 2023, département | Première carte ; taux corrigé des différences d'âge. |
| [Odissé — diabète déclaré, Baromètre](https://odisse.santepubliquefrance.fr/explore/assets/diabete-indicateurs-du-barometre-2024/) | 2024, enquête nationale auprès des 18–79 ans | Comparaison selon la situation financière déclarée. |
| [Insee — Filosofi](https://www.insee.fr/fr/statistiques/8984752) | 2023, département | Carte de la pauvreté. |
| Odissé — [situation sociale à la naissance](https://odisse.santepubliquefrance.fr/explore/assets/perinatalite-donnees-socio-demographiques-departement/), [suivi de grossesse](https://odisse.santepubliquefrance.fr/explore/assets/grossesse-dep/) et [prématurité](https://odisse.santepubliquefrance.fr/explore/assets/perinatalite-prematurite-departement/) | 2024, département | Trois mesures distinctes de la séquence périnatale. |
| Odissé — [vaccination HPV](https://odisse.santepubliquefrance.fr/explore/assets/couvertures-vaccinales-des-adolescent-et-adultes-departement/), dépistages [du sein](https://odisse.santepubliquefrance.fr/explore/assets/cancer-participation-au-depistage-organise-du-cancer-du-sein_dep/) et [colorectal](https://odisse.santepubliquefrance.fr/explore/assets/cancer-participation-au-depistage-organise-du-cancer-du-colon-rectum-departement-copie/) | 2025 pour le HPV ; 2024–2025 pour les dépistages ; département | Trois actions de prévention aux populations cibles différentes. |
| [Odissé — indice de défavorisation sociale F-EDI](https://odisse.santepubliquefrance.fr/explore/assets/french-european-deprivation-index-f-edi-2021-par-commune/) | 2021, commune | Contexte social des communes du zoom et de l'exploration. |
| [Irdes — accès potentiel à un cardiologue](https://www.data.gouv.fr/datasets/accessibilite-potentielle-localisee-apl-en-cardiologie-france-irdes) | 2019, commune | Estimation des contacts potentiellement accessibles ; distincte d'un temps de trajet. |
| [Annuaire Santé — lieux d'exercice RPPS](https://www.data.gouv.fr/datasets/annuaire-sante-extractions-des-donnees-en-libre-acces-des-professionnels-intervenant-dans-le-systeme-de-sante-rpps) | Extraction d'octobre 2026, adresses géocodées | Points montrés dans le zoom autour de Gien. |
| [OpenStreetMap](https://www.openstreetmap.org/copyright) et calcul d'itinéraires avec Valhalla | Calcul réalisé en 2026, réseau routier | Trajet et zones atteignables en voiture depuis le centre de Gien. |
| [Odissé — maladies cardio-neuro-vasculaires](https://odisse.santepubliquefrance.fr/explore/assets/maladies-cardio-neuro-vasculaires-taux-standardises-epci/) | Moyenne 2021–2023, intercommunalité | Mesure de cardiopathie ischémique accessible dans « Et chez vous ? » ; elle n'est pas comparée à l'accès aux soins dans le récit guidé. |
| [Contours administratifs — départements 2024](https://adresse.data.gouv.fr/data/contours-administratifs/2024/geojson/departements-1000m.geojson) | Découpage 2024, carte hexagonale | Fond des cartes départementales. |
| [Contours administratifs — EPCI 2024](https://adresse.data.gouv.fr/data/contours-administratifs/2024/geojson/epci-1000m.geojson) | Découpage 2024, carte hexagonale | Le fond de carte correspond au découpage des taux cardiovasculaires Odissé. |

Les tableaux et les contours nécessaires au site se trouvent dans [`production/data/`](production/data/).

## Limites rencontrées

- Les indicateurs portent sur des années, des populations et des définitions différentes. Le diabète déclaré dans le Baromètre ne mesure pas le diabète traité de la carte départementale. Les taux cardiovasculaires publiés à l'intercommunalité ne deviennent pas communaux quand on recherche une commune.
- Les rapprochements entre cartes décrivent des écarts territoriaux ; ils ne démontrent pas que la pauvreté, le suivi médical ou l'offre de soins causent un résultat de santé.
- Certains jeux ne couvrent pas tous les territoires ou comportent des valeurs manquantes. Les comparaisons de rangs dans la prévention conservent les différents nombres de départements disponibles. Le fond de carte communal détaillé concerne la France hexagonale ; les valeurs disponibles pour l'outre-mer restent consultables sous forme de chiffres.
- Les 59 points du zoom cardiologie sont des **adresses d'exercice RPPS sélectionnées et géocodées**, pas 59 cardiologues uniques ni un inventaire exhaustif. Une adresse inscrite ne garantit pas qu'un praticien y consulte aujourd'hui ou accepte de nouveaux patients. L'APL date de 2019 et les adresses RPPS de 2026 : elles ne décrivent pas le même instant.
- Le trajet et les zones de 15, 30, 45 et 60 minutes sont calculés en voiture depuis un point de départ à Gien, sur un réseau routier, sans trafic en temps réel. Ils ne représentent ni le trajet depuis chaque domicile ni l'obtention d'un rendez-vous.
- La recherche de communes, les polices et deux bibliothèques graphiques dépendent de services externes : une connexion Internet est nécessaire pour profiter de toutes les fonctions. Le site propose des liens d'évitement, des descriptions textuelles des cartes, des tableaux de valeurs, une navigation au clavier et une réduction des animations selon la préférence du système.

## Frugalité

Le dossier `production/` pèse environ **4,1 Mo**. Il contient les tableaux et les contours simplifiés utilisés par la page ; les sources brutes et les fichiers intermédiaires ne sont pas nécessaires à sa lecture. Les trajets et les zones atteignables sont pré-calculés : le lecteur n'interroge pas un serveur d'itinéraires à chaque défilement. Le site est statique, sans compte utilisateur ni serveur applicatif ; il peut être hébergé sur GitHub Pages. Les animations sont allégées lorsque le système demande moins de mouvement. Nous n'avons pas mesuré l'empreinte carbone du site.

## Les outils employés

Nous avons préparé et vérifié les jeux de données avec RStudio et des scripts de traitement afin de ne conserver que les indicateurs utilisés dans le récit. Le site utilise D3 et TopoJSON pour les cartes et les transitions. Claude Code/Design a aidé à prototyper et à mettre en œuvre l'interface à partir de nos consignes. Le choix des questions, des comparaisons, des formulations et des limites affichées relève de notre travail éditorial ; les valeurs présentées ont été contrôlées dans les fichiers sources.

## Consulter le site

La visualisation est accessible ici : <https://mathysgtr.github.io/defi-3_gauthier-hislers/production/>.

La visualisation et son code source se trouvent dans [`production/`](production/). Pour la voir localement, ouvrir un terminal à la racine du dépôt et lancer :

```bash
python3 -m http.server 8766
```

Ouvrir ensuite <http://127.0.0.1:8766/production/>. L'ouverture directe de `production/index.html` par double-clic ne permet pas au navigateur de charger les CSV et les fichiers géographiques. Python 3 et une connexion Internet sont nécessaires.
