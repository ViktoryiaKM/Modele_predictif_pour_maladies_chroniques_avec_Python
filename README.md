
## Care of Duty – Prédiction des Maladies Chroniques à partir de Données Médicales
*Projet collaboratif réalisé dans le cadre de ma formation à la Wild Code School.

Chaque membre de l'équipe était responsable d'une pathologie spécifique.  
👉 Ma contribution portait sur la **prédiction du cancer du sein**, de l'exploration des données au développement du modèle machine learning.*

## 🎯 Objectif du projet

Développer un système de classification automatique basé sur le machine learning pour prédire la présence ou l'absence de plusieurs maladies chroniques à partir de données médicales.

L'application permet à l'utilisateur d'estimer son risque potentiel pour les maladies suivantes :
- Diabète
- Cancer du sein
- Maladie rénale chronique
- Maladie cardiaque chronique
- Maladie du foie

## 💡 Enjeux

Les modèles prédictifs en santé apportent une vraie valeur :
- **Détection précoce** : intervenir plus tôt, améliorer les chances de traitement.
- **Soins personnalisés** : adapter les traitements aux profils individuels.
- **Optimisation des ressources médicales** : meilleure planification et gestion des soins.

## 🧪 Données
Chaque maladie dispose de son propre jeu de données, avec :
- **Lignes** = patients (malades ou non)
- **Colonnes** = variables médicales (analyses, diagnostics, symptômes…)

Les données présentent des défis typiques :
- Valeurs manquantes
- Données déséquilibrées
- Variables spécifiques à chaque pathologie

## 🔧 Étapes de traitement

### 1. Compréhension des données
Analyse de la signification clinique des variables et identification des redondances ou incohérences.

Lien vers: [Compréhension des variables médicales](https://github.com/ViktoryiaKM/Modele_predictif_pour_maladies_chroniques_avec_Python/blob/main/variables_Caracteristiques_prediction_cancer_sein.pdf)

### 2. Prétraitement
- Nettoyage : suppression/traitement des valeurs manquantes
- Normalisation / standardisation
- Encodage des variables catégorielles

### 3. Analyse exploratoire
- Statistiques descriptives (moyenne, médiane, écart-type…)
- Visualisations : distribution, corrélations, anomalies

### 4. Sélection des variables
Techniques d’analyse multivariée pour identifier les biomarqueurs pertinents, en collaboration avec des connaissances médicales.

Lien vers mon notebook: [Pre-traitement_et_Exploration_dataset_cancer_seins](https://github.com/ViktoryiaKM/Modele_predictif_pour_maladies_chroniques_avec_Python/blob/main/Projet3_01_Pre-traitement_et_Exploration_dataset_cancer_seins.ipynb)

## 🤖 Modélisation prédictive

Pour chaque maladie :
- Test de plusieurs algorithmes (Random Forest, SVM, XGBoost, Logistic Regression…)
- Sélection du meilleur modèle selon les performances (précision, recall, F1-score…)
- Validation croisée

Lien vers mon notebook: [Machine_Learning_tests_algorythmes](https://github.com/ViktoryiaKM/Modele_predictif_pour_maladies_chroniques_avec_Python/blob/main/Projet3_02_Machine_Learning.ipynb))

## 🖥️ Application web

Une interface simple a été développée permettant :
- de saisir de nouvelles données médicales
- d'obtenir une prédiction immédiate du risque de maladie

## Technos utilisées :
- Python / scikit-learn / pandas
- Streamlit ou Flask pour l'app web
- Visualisations avec matplotlib / seaborn
