# Logement Social IDF

La version de production actuelle est hébergée [ici](https://lapostolet.fr)

Logement social IDF est une application web qui permet de consulter des données à propos de l'état du logement social dans les communes d'Ile de France.

![](screenshot.png)

## Fonctionnalités

* Indiquer les communes d’île de France n’ayant pas une proportion assez importante de logements sociaux par rapport au nombre d’habitant selon la loi solidarité et renouvellement urbains du 13 décembre 2000
* L’utilisateur peut aussi sélectionner n’importe quelle ville d’île de France sur la carte, ou en indiquant son nom dans la barre de recherche, afin d’obtenir certaines informations, comme le nombre d’habitants, ou le nombre de logements sociaux.  
* Après avoir sélectionné une ville l’utilisateur peut aussi avoir le temps de trajet ainsi que l’itinéraire entre le point sélectionné et la station Chatelet, afin d’avoir une idée de l’isolement de la ville. 
* En dessous de la carte, on peut voir une liste d’articles de lois concernant les logements sociaux en France

## Provenance des données

Les données des logements sociaux ont été récupérées sur le site data.gouv.fr et ont été importées dans le projet dans le répertoire donné. Des APIs ont aussi été utilisées : les API adresse.data.gouv.fr et navitia.io du STIF. 

## Bibliothèques et outils

Le framework CSS Material Design Lite a été utilisé pour le style de l’interface. 
Pour la carte, Leaflet et jQuery ont été utilisés pour le code client.
