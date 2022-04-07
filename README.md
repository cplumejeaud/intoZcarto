Cours introductif et TD Cartographie avec MAGRIT

Christine Plumejeaud-Perreau, UMR MIGRINTER 7301
Plateforme Universitaire de Données, Poitiers, 14 avril 2022

- [1. Cours le matin - 10h-12h](#1-cours-le-matin---10h-12h)
  - [1.1. Sites](#11-sites)
  - [1.2. Plateformes de données](#12-plateformes-de-données)
  - [1.3. Définitions de la cartes, des types de cartes](#13-définitions-de-la-cartes-des-types-de-cartes)
  - [1.4. Exemple de plan d'un cours complet](#14-exemple-de-plan-dun-cours-complet)
  - [1.5. Le succédané de cours en 2H](#15-le-succédané-de-cours-en-2h)
- [2. TD l'après-midi : 14h-17h](#2-td-laprès-midi--14h-17h)
  - [2.1. Cartographier le logement étudiant](#21-cartographier-le-logement-étudiant)
  - [2.2. Cartographier le traffic maritime en 1789](#22-cartographier-le-traffic-maritime-en-1789)

# 1. Cours le matin - 10h-12h

## 1.1. Sites
- https://www.sciencespo.fr/cartographie/ l'atelier carto de SciencePo
- https://neocarto.hypotheses.org/  le blog du cartographe Nicolas Lambert
- https://visionscarto.net  : ancien blog de cartographie du Monde diplomatique, celui de Philippe Rivière
- https://magrit.hypotheses.org/ : le blog du projet MAGRIT et ses tutos
- https://www.sciencespo.fr/cartographie/khartis/ : Le site du projet KHARTIS
- https://le-cartographe.net/ 
- mappemonde http://mappemonde.mgm.fr/ et https://journals-openedition-org.ressources.univ-poitiers.fr/mappemonde/6404 

## 1.2. Plateformes de données
-	Geoportail https://www.geoportail.gouv.fr/carte 
-	Openstreetmap https://www.openstreetmap.org/ et http://download.geofabrik.de/ 
-	Ign https://geoservices.ign.fr/ 
-	naturalEarth https://www.naturalearthdata.com/ 
-	https://www.observatoire-des-territoires.gouv.fr/outils/cartographie-interactive/#c=home   
-	etalab https://www.etalab.gouv.fr/ et https://www.data.gouv.fr/fr/ 
-	Site européen pour recherche de données FAIR : http://b2find.eudat.eu/ 
-	ONU : http://data.un.org/
-	insee : www.insee.fr  
-	Eurostat https://ec.europa.eu/eurostat/fr/data/database et GISCO https://ec.europa.eu/eurostat/fr/web/gisco/geodata/reference-data/administrative-units-statistical-units 

## 1.3. Définitions de la cartes, des types de cartes

La carte est la représentation d’un espace. C’est la transcription dans une image de phénomènes localisés et des relations qui se développent entre ces phénomènes. [Le Fur, 2007]
1.	Echelle : rapport de réduction entre l’espace réel et la représentation
2.	Sémiologie graphique : une image qui renvoie à des normes de perception visuelle
3.	Intention : représentation simplifiée et construite d’un phénomène réalisée à partir d’hypothèses, d’intentions et d’un savoirfaire.

Types de cartes
-	Carte touristique
-	Carte géologique
-	Carte mentale : Représentation dessinée par des individus d’un espace et/ou de leurs pratiques. C’est une représentation imagée selon leur perception de l’espace.

**Carte topographique**
Résultats d’observations directes : relief, cours d’eau, aménagements... Représentations d’objets concrets, fixes, et durables dans le temps.

**Carte thématique**
Représentations de phénomènes localisables, qualitatifs ou quantitatifs, de toute nature.

## 1.4. Exemple de plan d'un cours complet

L’INFORMATION GÉOGRAPHIQUE ET SON ANALYSE

1.1. Le fond de carte
1.2. Les données attributaires
1.3. Les sources de l’information éographique et statistique
1.4. Discrétiser pour cartographier

LE LANGAGE CARTOGRAPHIQUE
2.1. La conception : de l’intention à la carte
2.2. La sémiologie graphique
2.3. Cartographier le temps
2.4. Cartographier pour comparer

CARTOGRAPHIER DES RELATIONS

3.1. Observer deux phénomènes sur une même carte
3.2. Représenter une corrélation
3.3. Représenter une relation entre plusieurs variables

## 1.5. Le succédané de cours en 2H

Une petite présentation disponible ici en PDF. 



# 2. TD l'après-midi : 14h-17h

## 2.1. Cartographier le logement étudiant


La base logement 2018
https://www.insee.fr/fr/statistiques/5542867?sommaire=5395764#consulter 

Logement 2013 
https://www.insee.fr/fr/statistiques/2409491?sommaire=2409559#documentation-sommaire 
https://www.insee.fr/fr/metadonnees/source/operation/s1251/presentation 

Le fond de carte des IRIS
https://geoservices.ign.fr/contoursiris 

Récupérer les données : 
- ftp://Contours_IRIS_ext:ao6Phu5ohJ4jaeji@ftp3.ign.fr/CONTOURS-IRIS_2-1__SHP__FRA_2020-01-01.7z 
- utiliser le lien vers mon sharedoc humanum : 
https://sharedocs.huma-num.fr/wl/?id=ht5q6bIZKgLjsqUURxvnxvbb8xDHSN9T


## 2.2. Cartographier le traffic maritime en 1789


Données en ligne sur l'API de PORTIC
data.portic.fr

- Prendre raw_flows
- Filtrer pour ne retenir que certains attributs et l'année 1789 au format CSV

http://data.portic.fr/api/rawflows/?format=csv&date=1789&params=departure_uhgs_id,departure_fr,destination_uhgs_id,destination_fr,destination_partner_balance_supp_1789,destination_substate_1789_fr,destination_state_1789_fr,tonnage,outdate_fixed,commodity_purpose,commodity_purpose2,commodity_purpose3,commodity_purpose4,all_cargos,nb_cargo


- Prendre les ports
- en format geojson
- en format CSV

