# Postgres et Docker

## Description

Création d'un conteneur Postgres à l'aide d'un docker-compose 

## Prérequis

- Docker

- Vscode

- Git 

## Démarrage

1. Avant de lancer le projet, copier puis renommer le fichier ".env.sample" en ".env" à la racine du projet
   
2. Ouvrir un terminal à la racine de ce projet, au même niveau que le fichier docker-compose et taper :

``` shell
docker-compose up -d
```

3. Ouvrir un onglet dans un navigateur et taper dans la barre de recherche : http://localhost:8080

4. Afin de pouvoir vous connecter à adminer, rentre le nom de l'utilisateur (jules), le mot de passe (azerty) et le nom de la bdd (par exemple exercice_db_postgres ). Penser aussi à changer le système sur PostgreSQL