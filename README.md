# 📊 Prédiction d'émojis par embedding de posts sur des réseaux sociaux

Ce projet porte sur la prédiction d'émojis associés à des posts sur des réseaux sociaux (Twitter, Reddit) en utilisant des embeddings produits par le modèle [Word2vec](https://arxiv.org/abs/1301.3781). 

## 🗂️ Structure du Projet

Voici un aperçu de la structure du projet :

```
.
├── dataset/                    # Dossiers contenant les données
│   ├── fichier_filtré_et_limite.csv # Dataset ne contenant qu'un certain nombre d'émojis
│   ├── fichier_transforme.csv
│   ├── phrases_emojis_eng.csv # Dataset anglais
│   ├── phrases_emojis.csv # Dataset français
├── models/                     # Dossiers contenant les modèles 
│   ├── english_posts_embeddings.model
│   ├── french_posts_embeddings.model
├── emoji_prediction.ipynb      # Notebook principal pour le projet
├── requirements.txt            # Fichier des dépendances Python
├── README.md                   # Documentation du projet
```

## 🚀 Comment Lancer le Projet

### 1. Pré-requis

Assurez-vous que les outils suivants sont installés sur votre machine :

- Python 3.8 ou plus récent 🐍
- `pip` pour gérer les dépendances
- Git pour cloner ce dépôt

### 2. Installation

1. Clonez ce dépôt :

   ```bash
   git clone <url-du-depot>
   cd Emoji-Prediction
   ```

2. Créez et activez un environnement virtuel :

   ```bash
   python -m venv .venv
   source .venv/bin/activate   # Sur Linux/Mac
   .venv\Scripts\activate      # Sur Windows
   ```

3. Installez les dépendances :

   ```bash
   pip install -r requirements.txt
   ```

### 3. Utilisation
 Exécutez `emoji_prediction.ipynb` pour entraîner le modèle et effectuer des prédictions. 

### 4. Exemples de Résultats

Vous pouvez consulter les résultats et les visualisations dans le notebook principal.

## 🗞️ Datasets

Les datasets utilisés sont disponibles dans le dossier `dataset/`. Ils contiennent des données pré-traitées pour l'entraînement des modèles. Un dataset en français, un en anglais et un autre en français mais limité en nombre d'émojis sont disponibles.

## 🛠️ Contributeurs

- Antoine Bretzner
- Ryan Belaib




