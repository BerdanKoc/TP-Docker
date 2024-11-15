# Todo App Flask ReactJS

## Description

Une application Todo développée avec un backend Flask et un frontend ReactJS

## Prérequis

- Docker
- Docker Compose

## Installation

1. **Cloner le depot**

   ```bash
   git clone https://github.com/Remy349/todo-app-flask-reactjs.git
   cd todo-app-flask-reactjs
   ```

2. **Construction et lancement des conteneurs**
   docker-compose up -d --build

3. **Verifier que les services sont lancer**
   docker-compose ps

4. **Accéder à l'application**
   - Frontend: http://localhost
     -PHPMyAdmin: http://localhost:8081

## Configuration

- **Variables d'environnement :**

  - `MYSQL_ROOT_PASSWORD` : Mot de passe root de MySQL
  - `MYSQL_DATABASE` : Nom de la base de données
  - `MYSQL_USER` : Nom d'utilisateur pour la base de données
  - `MYSQL_PASSWORD` : Mot de passe pour l'utilisateur de la base de données

- **Ports utilisés :**

  - `80` : Nginx (frontend et API)
  - `8081` : PHPMyAdmin
