# Les Bases de Git

## Introduction

Git est un système de gestion de versions distribué très utilisé dans le développement logiciel. Il permet à plusieurs personnes de travailler sur un même projet, de conserver un historique des modifications et de revenir facilement à des versions antérieures si besoin.

## Pourquoi utiliser Git ?

Git présente de nombreux avantages pour les développeurs :

- 🌱 Suivi des modifications sur chaque fichier du projet.
- 👥 Travail collaboratif facilité grâce aux branches.
- ⏪ Possibilité de revenir à un état antérieur du projet.
- 🔀 Fusion des modifications et gestion des conflits.

## Commandes Git essentielles

Voici un aperçu des commandes de base que tout développeur doit connaître :

```bash
git init                # Initialiser un dépôt local
git add .               # Ajouter tous les fichiers au suivi
git commit -m "Message" # Valider les modifications avec un message
git status              # Vérifier l'état des fichiers
git log                 # Consulter l'historique des commits
git branch              # Lister les branches existantes
git checkout nom_branche# Se déplacer dans une branche
git merge nom_branche   # Fusionner une branche dans l'actuelle
git push                # Envoyer les modifications vers GitHub
git pull                # Récupérer les modifications depuis GitHub
