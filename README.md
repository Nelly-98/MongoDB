# MongoDB

## Exploration de la Base de données avec PyMongo

Ce projet explore les données d'une base MongoDB en utilisant la bibliothèque pymongo. Le but est de se connecter à la base de données, d'explorer ses collections, d'analyser les données des livres, et de réaliser des requêtes et des agrégations pour extraire des informations pertinentes.
Le code se connecte à une instance MongoDB, récupère et affiche les bases de données, les collections, et extrait des informations pertinentes sur les livres contenus dans la collection "livres". Des requêtes sont également exécutées pour analyser le contenu des livres en fonction de critères spécifiques, tels que les mots-clés dans la description ou le nombre de pages.

## Fonctionnalités :
- Connexion à MongoDB : Utilisation de MongoClient pour se connecter à une base de données MongoDB locale.
- Affichage des bases de données : Affiche toutes les bases de données disponibles.
- Exploration des collections : Lister les collections dans une base de données donnée.
- Affichage d'un document de collection : Afficher un document spécifique d'une collection.
- Comptage de documents : Requêtes pour compter le nombre de livres qui répondent à certains critères.
- Agrégation des données : Agrégation pour obtenir des statistiques sur les pages des livres par catégorie et autres critères.
- Recherche par mot-clé dans les descriptions : Recherche des livres contenant des mots-clés dans leur description.
- Affichage des catégories distinctes : Affiche les catégories distinctes utilisées dans les livres.

## Prérequis

- Python 3.8 ou supérieur
- MongoDB en fonctionnement
- pymongo et dnspython installés

## Contributions

Les contributions sont les bienvenues. Veuillez soumettre vos pull requests pour ajouter des fonctionnalités ou corriger des bugs.


