# Récapitulatif des commandes utilisées

Ce document liste les commandes Git que vous avez exécutées pendant la mise en place du projet, avec une courte explication pour chacune.

---
---

## 1) Initialisation et clone

- `git init`
  - Initialise un nouveau dépôt Git local dans le dossier courant (crée `.git/`).

- `git clone "https://github.com/Abdou586/eemigit.git"`
  - Clone (copie) le dépôt distant GitHub `eemigit` dans un sous-dossier `eemigit` local.

Exemple dans votre historique :
```powershell
git init
git clone "https://github.com/Abdou586/eemigit.git"
cd eemigit
```

## 2) Ajouter / valider des fichiers (staging & commit)

- `git add .`
  - Ajoute tous les fichiers modifiés/non suivis du répertoire courant à la zone de staging (prépare pour le commit).

- `git commit -m "message"`
  - Enregistre un commit avec le message fourni. Exemple :
    - `git commit -m "Mise en ligne de notre landing page pour application SAAS"`

Note : si vous voulez voir quels fichiers seront ajoutés, utilisez `git status` avant `git add`.

## 3) Envoyer les commits vers GitHub

- `git push origin main`
  - Envoie les commits locaux sur la branche `main` du dépôt distant nommé `origin` (habituellement GitHub).

## 4) Création des branches Otmane et Aln

git checkout -b Otmane

Et 

git checkout -b Aln

## 5) Complexe

  # Récupérer les dernières modifications
  git pull origin main

  # Fusionner la branche
  git merge Otmane et git merge Aln

  # Pousser les changements
  git push origin main
