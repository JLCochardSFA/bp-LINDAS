# blueprint-LINDAS

## Méthodologie

* Les requêtes sont exécutées dans LINDAS-PROD et les résultats sont enregistrées dans LINDAS-TEST dans un graphe distinct https://lindas.admin.ch/SFA/datamngt
* Etant donné que certaines données natives de LINDAS-PROD qui devraient servir à la visualisation ne se trouvent pas forcément sur TEST, elles sont copiées (comme je le faisais avec Fuseki)
* Blueprint qui consomme des données de LINDAS-TEST est accessible ici https://blueprint.lindas.zazukoians.org/login
* 

## Caractéristiques à représenter

* Les named graphs avec leurs liens aux organisations et aux datasets
* Les différents types de datasets (cubes, vocabulaires, datasets standards)
* Les personnes responsable de la gestion des datasets
* les pipelines associés à la mise à jour des datasets
* les applications qui consomment le contenu des datasets
* les tailles des cubes et des autres datasets
* les vocabulaires utilisés dans les cubes
* les liens de dépendance entre datasets

## Autres idées

A vérifier leur faisabilité

* A partir des logs des queries, identifier les données qui sont "consommées" et mettre en évidence ces caractéristiques
* Constituer une liste des projets en cours ou des idées de projets et des besoins en données et applications
