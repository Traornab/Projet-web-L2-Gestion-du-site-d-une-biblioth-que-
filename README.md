# Application Web de Gestion d'une Bibliothèque

## Description
Cette application web permet de gérer une bibliothèque en ligne. Elle offre une interface intuitive pour les utilisateurs, qu'ils soient administrateurs ou membres premium. Les fonctionnalités incluent une page d'accueil, une connexion sécurisée, et des options pour gérer les livres et les utilisateurs.

## Table des Matières
- [Installation](#installation)
- [Utilisation](#utilisation)
- [Fonctionnalités](#fonctionnalités)
- [Contributions](#contributions)
- [Licence](#licence)

## Fonctionnalités
Page d'accueil :

Présentation de la bibliothèque et des services offerts, avec des liens vers les différentes sections de l'application.
Page de connexion :

Authentification unique qui redirige l'utilisateur vers la partie admin ou premium en fonction des droits définis dans la base de données.
Partie Admin :

Gestion des utilisateurs :
Ajouter, modifier ou supprimer des utilisateurs (admin et premium).
Gestion des livres :
Ajouter, modifier ou supprimer des livres dans la base de données.
Visualiser les caractéristiques des livres (titre, auteur, éditeur, stock, etc.).
Recherche dynamique :
Utiliser JavaScript pour rechercher des livres en temps réel, avec des suggestions instantanées basées sur l'entrée de l'utilisateur.
Partie Utilisateur :

Recherche de livres :
Utiliser JavaScript et AJAX pour rechercher dynamiquement des livres.
Détails du livre :
Afficher des informations détaillées sur chaque livre : description, auteur, éditeur, etc.
Réservation de livres :
Possibilité de réserver un livre s'il est disponible en stock.
Gestion des réservations :
Renouveler une réservation avant la date d'échéance.
Retourner un livre réservé.
Différences entre utilisateurs :
Les membres premium peuvent garder des livres plus longtemps que les utilisateurs standards, offrant ainsi plus de flexibilité.


## Installation
Pour installer ce projet, clonez le dépôt et installez les dépendances nécessaires :
```bash
git clone https://github.com/Traornab/Projet-web-L2
cd votre-repo
npm install


