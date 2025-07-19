# Technologies envisagées :

## Front-end
- Framework : React.jspour une interface interactive.
- Bibliothèque de cartographie : Leaflet.js pour l'intégration de la carte.
- Interface utilisateur : Material UI pour une interface moderne et responsive.

## Back-end
- Langage : Node.js (avec NestJS) 
- Base de données : PostgreSQL (pour des relations plus complexes entre les données).
- Authentification : JWT pour une gestion sécurisée des utilisateurs.

## API
- OpenStreetMap pour les données cartographiques.
- (Optionnel) API de stockage d'images (Cloudinary, AWS S3) pour l'ajout de photos.

## Sécurité et Authentification 
- Gestion des comptes utilisateurs avec possibilité de connexion via Google, Facebook, ou par email.
- Sécurisation des données personnelles via HTTPS et chiffrement.

# Développement de l'interface utilisateur 

## Page d'accueil 
- Présentation générale du projet avec une carte interactive affichant les voyages déjà ajoutés.
- Possibilité d'ajouter un nouveau voyage depuis un bouton central.

## Page de voyage
- Interface détaillée où l'utilisateur peut consulter les informations de son voyage, ajouter des photos et descriptions.
- Visualisation de la carte avec l'itinéraire parcouru et les points d'intérêt sur la carte.

## Page de statistiques
- Graphiques et diagrammes représentant les informations des voyages passés (pays visités, types de voyage, durée, etc.).
- Comparaison des différents types de voyages effectués (aventure, détente, affaires, etc.).

# Page de profil utilisateur
- Informations personnelles, voyages passés et planifiés.
- Réglages de confidentialité et de sécurité.
