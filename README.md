# Backend Bancaire

Ce projet est un système backend bancaire développé en Java. Il fournit diverses fonctionnalités pour gérer les comptes bancaires, les transactions et les informations des utilisateurs.

## Fonctionnalités

- **Gestion des comptes** : Créer, mettre à jour et supprimer des comptes bancaires.
- **Gestion des transactions** : Enregistrer des dépôts, des retraits et des transferts entre comptes.
- **Gestion des utilisateurs** : Enregistrer, mettre à jour et supprimer des informations d'utilisateur.
- **Sécurité** : Authentification et autorisation sécurisées pour les utilisateurs.

## Technologies Utilisées

- **Java** : Langage principal utilisé pour le développement.
- **Spring Boot** : Framework pour créer des applications Java autonomes et de production.
- **Maven** : Outil de gestion des dépendances et de construction du projet.

## Structure du Répertoire `src`

Le répertoire `src` contient l'ensemble du code source du projet. Voici l'utilité de chaque dossier :

- **src/main/java** : Contient le code source principal de l'application.
  - **controller** : Contient les classes de contrôleurs qui gèrent les requêtes HTTP entrantes et dirigent les réponses appropriées.
  - **model** : Contient les classes de modèles qui représentent les entités de la base de données.
  - **repository** : Contient les interfaces de dépôt qui interagissent avec la base de données.
  - **service** : Contient les classes de services qui implémentent la logique métier de l'application.
  - **security** : Contient les classes liées à la sécurité, telles que la configuration de l'authentification et de l'autorisation.

- **src/main/resources** : Contient les fichiers de configuration et les ressources statiques.
  - **application.properties** : Fichier de configuration principal pour l'application Spring Boot.

- **src/test/java** : Contient les tests unitaires et les tests d'intégration pour le projet.

## Prise en Main

### Prérequis

- Kit de développement Java (JDK) 8 ou supérieur
- Maven 3.6 ou supérieur

### Installation

1. Cloner le dépôt :

   ```sh
   git clone https://github.com/jihane-malek/banking-backend.git
   cd banking-backend
