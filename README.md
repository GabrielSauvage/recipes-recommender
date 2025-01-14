# Recipe Recommender

Bienvenue sur notre projet **Recipe Recommender**

## Fonctionnalités

- Filtrage collaboratif utilisant SVD
- Filtrage collaboratif utilisant KNN
- Filtrage par contenu utilisant TF-IDF
- Filtrage par contraintes utilisant Pulp

_Tous les programmes sont dans des fichiers jupyter interactifs._

## 1. Installer les dépendences
 ```bash
 pip install -r requirements.txt
 ```

### Bibliothèques utilisées

- **numpy**
- **pandas**
- **scikit-learn**
- **sqlalchemy**
- **jinja2**
- **pulp**

## 2. Récupérer les données

Sachant que nos datasets sont trop volumineux pour être push sur le GitHub et partagés sur le campus, nous avons décidé
de les stocker dans un google drive temporaire.

1. Pour récupérer ces fichiers, il suffit de les télécharger depuis le lien suivant :
https://drive.google.com/drive/folders/1Rv9DAPzKnchAuBD525Kphb1g4Sdvo835?usp=sharing


2. Une fois téléchargés, il suffit de placer les 2 fichiers CSV dans le dossier `data/raw` du projet.