# 📖 Projet 1 : Blog Collaboratif en Markdown

## 📌 Présentation

Ce projet a été réalisé dans le cadre de ma formation sur l’utilisation de **Git** et **GitHub**.  
L’objectif était de simuler un travail collaboratif entre deux développeurs, en créant un blog contenant deux articles rédigés en **Markdown**.

---

## 📌 Objectifs du projet

- Utiliser **Git** pour gérer le versioning d’un projet.
- Créer et gérer plusieurs **branches**.
- Rédiger deux articles collaboratifs :
  - Article 1 : *Introduction aux bases de Git*
  - Article 2 : *Présentation de la plateforme GitHub*
- Provoquer et résoudre un **conflit de fusion** volontairement dans le `README.md`.
- Fusionner les branches dans une branche `merge-blog`.
- Réaliser une **Pull Request** vers `main`.
- Créer une **Issue** pour proposer un article 3.

---

## 📌 Organisation du projet

- 📂 Branche `article-1` : Rédaction de l'article 1
- 📂 Branche `article-2` : Rédaction de l'article 2
- 📂 Branche `merge-blog` : Fusion des deux articles et résolution des conflits
- 📂 Branche `main` : Intégration finale

---

## 📌 Détails des articles

- `article-1.md` : Introduction aux bases de Git
- `article-2.md` : Présentation de GitHub

Chaque article est écrit en Markdown et respecte la structure classique d’un article technique.

---

## 📌 Commandes Git utilisées

Quelques commandes essentielles du projet :

```bash
git init
git add .
git commit -m "message"
git push origin nom_branche
git checkout -b nouvelle_branche
git merge branche_a_fusionner
git pull origin main --rebase
