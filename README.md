# Recipe Recommender

Bienvenue sur notre projet **Recipe Recommender**

## Fonctionnalités

- Filtrage collaboratif utilisant SVD
- Filtrage collaboratif utilisant KNN
- Filtrage par contenu utilisant TF-IDF
- Filtrage par contraintes utilisant Pulp

_Tous les programmes sont dans des fichiers jupyter interactifs._

## 1. Cloner le dépôt
 ```bash
 git clone https://github.com/GabrielSauvage/recipes-recommender.git
 cd recipes-recommender
 ```

## 2. Installer les dépendences
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

## 3. Récupérer les données

Sachant que nos datasets sont trop volumineux pour être stockés sur GitHub et sur le campus, nous avons décidé
de les stocker un google drive temporaire.

1. Pour récupérer ces fichiers, il suffit de les télécharger depuis le lien suivant :
https://drive.google.com/drive/folders/1Rv9DAPzKnchAuBD525Kphb1g4Sdvo835?usp=sharing


2. Une fois téléchargés, il suffit de placer les 2 csv dans le dossier `data/raw` du projet.