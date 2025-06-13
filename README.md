# TP : Déploiement de WordPress avec MySQL via Docker Compose

Ce projet est un travail pratique dans le cadre du cours de **Projet Informatique**, consistant à déployer une application **WordPress** connectée à une base de données **MySQL**, le tout orchestré avec **Docker Compose**.

---

## Objectif du TP

- Déployer une application multi-conteneurs avec Docker
- Utiliser Docker Compose pour orchestrer les services
- Accéder à WordPress via un navigateur web
- Comprendre l’architecture conteneurisée

---

## Architecture du projet

Le projet est composé de **deux services** :
- `wordpress` : le CMS WordPress, accessible via le port `8080`
- `db` : une base de données MySQL version 5.7

Les données de la base sont persistées grâce à un volume Docker.

---

## Fichiers importants

- `docker-compose.yaml` : définit les services, variables d’environnement, volumes et ports exposés.

---

## Lancer le projet

### Étapes :

```bash
# Se placer dans le dossier du projet
cd wordpress-projet

# Démarrer les conteneurs en arrière-plan
docker compose up -d
---


## Réalisé par

- **Nom :** [Toure youssouf]
- **Classe :** [LPRGL3B]