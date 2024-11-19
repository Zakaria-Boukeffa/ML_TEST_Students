# Prédiction des Performances des Étudiants

## Description

Ce projet utilise des techniques de Machine Learning pour prédire les scores moyens des étudiants en fonction de diverses caractéristiques. L'objectif est d'analyser et de modéliser les facteurs qui influencent les performances académiques des étudiants.

## Prérequis

Pour exécuter ce projet, vous aurez besoin des packages Python suivants :

- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn

Vous pouvez installer les packages requis en utilisant pip :

```bash
pip install -r requirements.txt
```

## Données

Les données utilisées dans ce projet proviennent du dataset "Students Performance Dataset (Cleaned)" disponible sur Kaggle :

https://www.kaggle.com/datasets/muhammadroshaanriaz/students-performance-dataset-cleaned

### Pour utiliser ces données :

1. Téléchargez le fichier CSV depuis le lien Kaggle ci-dessus.
2. Créez un dossier nommé `Data` dans le répertoire principal du projet.
3. Placez le fichier CSV téléchargé dans le dossier `Data`.
4. Dans le notebook ou le script Python, assurez-vous que le chemin vers le fichier est correct :

```python
df = pd.read_csv('Data/Cleaned_Students_Performance.csv')
```

Amusez-vous  et bon coudage (;
