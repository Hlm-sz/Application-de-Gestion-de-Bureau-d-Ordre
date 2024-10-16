# Application-de-Gestion-de-Bureau-d-Ordre
Ce projet est une application web de gestion de bureau d'ordre développée avec Laravel pour le back-end et ReactJS pour le front-end. Il a été conçu pour aider les entreprises à gérer, suivre et traiter leurs courriers entrants et sortants de manière centralisée et efficace.

# Fonctionnalités principales.
+ Enregistrement des courriers : Créez et enregistrez les courriers entrants et sortants dans un système centralisé.
+ Suivi en temps réel : Suivez l'état des courriers en temps réel pour une traçabilité optimale.
+ Automatisation : Automatisation des processus de gestion des courriers pour réduire les erreurs et améliorer l'efficacité.
+ Gestion des documents : Stockez et consultez les documents associés aux courriers dans un espace dédié.
+ Collaboration inter-départements : Améliorez la communication interne en permettant aux départements de collaborer plus efficacement 
  sur la gestion des courriers.
 
# Technologies utilisées.
+ Laravel : Framework PHP utilisé pour la gestion du back-end.
+ ReactJS : Librairie JavaScript utilisée pour l'interface utilisateur.
+ MySQL : Base de données pour stocker les informations des courriers.

# Installation.
* Clonez le dépôt : git clone https://github.com/Hlm-sz/Application-de-Gestion-de-Bureau-d-Ordre.git
* Installez les dépendances Laravel : composer install
* Installez les dépendances React : npm install
* Configurez le fichier .env pour les variables d'environnement (base de données, mail, etc.).
* Créez les migrations et les tables : php artisan migrate
* Lancez les factories pour générer des données de test : php artisan db:seed
* Allez à la table users dans la base de données et modifiez le rôle d'un utilisateur en "1" pour lui donner les droits administratifs.
* Lancez l'application :
  + Back-end : php artisan serve
  + Front-end : npm run dev


