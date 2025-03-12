# 🚨 **Détection de Fraude par Carte de Crédit (Credit Card Fraud Detection)** 💳

Bienvenue dans le projet **Détection de Fraude par Carte de Crédit** ! Ce projet utilise des techniques d'apprentissage automatique et des modèles de machine learning pour prédire les transactions frauduleuses dans un ensemble de données de cartes de crédit. Le dataset utilisé dans ce projet est le **"Credit Card Fraud Detection Dataset"** provenant de Kaggle, plus précisément du [dataset de Nelgiriyewithana](https://www.kaggle.com/datasets/nelgiriyewithana/credit-card-fraud-detection-dataset-2023).

## 📊 **À propos du Dataset**

Ce dataset contient des informations sur les transactions par carte de crédit et vise à classer chaque transaction comme étant légitime ou frauduleuse. Le dataset inclut les caractéristiques suivantes :

- **Montant de la transaction** : Le montant de la transaction effectuée avec la carte de crédit.
- **Caractéristiques anonymisées (V1, V2, ..., V28)** : Ce sont des caractéristiques anonymisées utilisées pour protéger la confidentialité des informations personnelles. Elles sont dérivées à partir des données réelles de cartes de crédit.
- **Classe** : La variable cible indiquant si la transaction est frauduleuse (1) ou non (0).

## 🛠️ **Technologies utilisées**

- **Python 3.x**
- **Scikit-learn** : Pour l'implémentation des modèles de machine learning.
- **Pandas** : Pour la manipulation des données.
- **Matplotlib / Seaborn** : Pour la visualisation des données et des résultats.
- **lightgbm / Random Forest / Logistic Regression** : Modèles utilisés pour la détection des fraudes.
- **Keras / TensorFlow** : Si des réseaux neuronaux sont utilisés dans le projet.

## 🎯 **Objectif du projet**

L'objectif principal de ce projet est de développer un modèle qui peut identifier les transactions frauduleuses dans un ensemble de données de cartes de crédit. Nous explorons différentes techniques de machine learning pour obtenir le meilleur modèle en termes de précision, rappel et F1-score.

## 📦 **Installation**

### Prérequis

Assurez-vous que vous avez Python 3.7 ou une version plus récente et **pip** installés sur votre machine.

### Cloner le projet

Clonez ce dépôt sur votre machine locale avec la commande suivante :
```bash
git clone https://github.com/votre-utilisateur/Credit-Fraud-Detection.git
cd Credit-Fraud-Detection
```
Installer les dépendances
Exécutez la commande suivante pour installer les dépendances nécessaires :
``` bash
pip install -r requirements.txt
```
🚀 Lancer l'application
Une fois les dépendances installées, vous pouvez lancer l'application Streamlit en exécutant :

        ```bash
        streamlit run app.py
