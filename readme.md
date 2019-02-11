# Extension Wordpress

A tout moment, vous pouvez faire une archive de votre dossier (.zip) et l'installer dans votre WordPress pour le tester.    
Aidez vous de la documentation officiel : https://codex.wordpress.org/Main_Page

## Exercice 1
Créer un dossier **LAMANU-cookie-law**. Créer un sous dossier **js**    
Télécharger le script **Tarte au citron** : https://opt-out.ferank.eu/fr/install/    
Copier les fichiers et dossiers de l'archive dans le dossier **LAMANU-cookie-law/js/tarteaucitron/**.    
Créer un fichier PHP du même nom que le dossier principal.    
Ajouter dans ce fichier ces commentaires en modifiant en conséquence :     
```php
/*
Plugin Name: LAMANU-cookie-law
Version: 0.1
Plugin URI: http://www.
Description: WordPress Plugin for european cookie law.
Author: Toto
Author URI: http://www.
*/
```

## Exercice 2
Dans le fichier **LAMANU-cookie-law.php** créer une fonction **LAMANU_scripts** et ajouter l'initialisation du script Tarte au citron.      
Appeler la méthode du Framework WordPress premettant d'appeler la fonction **LAMANU_scripts** dans la balise HEAD du site WordPress.

## Exercice 3
Créer le lien de menu pour avoir une page de configuration dans le Back-Office de Wordpress.     
Dans cette page créer un champ permattant de renseigner l'ID de suivi. Il est de la forme : UA-00000000-0.     
Faire un dossier view. Dans ce dossier créer un fichier option.php. C'est dans ce fichier que va se trouver le contenu de la page de configuration.     
Ecrire le nécessaire pour pouvoir renseigner le champ de l'ID de suivi. Il doit s'enregistrer dans la base de données.

## Exercice 4
Dans le dossier **js**, ajouter un fichier **googleAnalytics.js**. Dans ce fichier mettre ce qu'il faut pour activer la gestion des cookies pour Google Analytics.    
Ajouter dans la fonction **LAMANU_scripts** la partie de gestion de Google Analytics qui attend l'ID de suivi.
