# Projet LAMP Collaboratif
## Lancer le projet
```bash
docker compose up -d
    •PHP accessible : http://localhost
    •Adminer accessible : http://localhost:8080
        •Serveur : db
        •Utilisateur : root
        •Mot de passe : poseidon
        •Base : DB-PRJ

docker compose down -v
docker compose up -d
Le -v est important, il supprime les données MariaDB pour que le init.sql soit rejoué.
