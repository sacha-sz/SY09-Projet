# Coûts Médicaux Américains - SY09
## Auteurs
- [Tobias S.](https://github.com/TobiasInfo)
- [Guillaume H.](https://github.com/GuillaumeHERMOSO)
- [Sacha SZ](https://github.com/sacha-sz)
## Description du projet
Ce projet explore les coûts médicaux américains en analysant diverses variables influençant ces coûts. L'analyse se concentre principalement sur des facteurs tels que l'âge, l'IMC (Indice de Masse Corporelle), le nombre d'enfants, le statut tabagique, le sexe et la région.
## Contenu du projet
### 1. Analyse Exploratoire des Données (EDA)
- **Dataset** : 2 772 lignes et 7 colonnes, réduit à 1 337 lignes après élimination des doublons.
- **Variables** :
  - Quantitatives : Âge, IMC, Nombre d’enfants, Charges.
  - Qualitatives : Sexe (Label Encoding), Statut Tabagique (Label Encoding), Région (One Hot Encoding).
### 2. Analyses Univariée et Multivariée
- **Analyse univariée** :
  - Impact des facteurs clés tels que l'âge, l'IMC et le statut tabagique sur les coûts médicaux.
- **Analyse multivariée** :
  - Étude des corrélations entre différentes variables et identification de l'importance du statut tabagique et de l'IMC en relation avec l’âge sur les coûts médicaux.
### 3. Modélisation
- **Régression Linéaire** :
  - Modèles pour fumeurs (R²=0.53) et non-fumeurs (R²=0.02).
- **Régression Linéaire Multiple** :
  - Modèle global avec R²=0.82.
### 4. Classification
- Segmentation des charges en trois catégories :
  - Faible : Moins de 10 000 $ / an.
  - Médian : Entre 10 000 $ et 30 000 $ / an.
  - Élevé : Plus de 30 000 $ / an.
## Résultats et Perspectives
- **Résumé** :
  - Les coûts médicaux sont fortement influencés par le statut tabagique, l'IMC et l'âge.
  - Meilleurs modèles : 
    - Prédiction : Régression Multiple avec 3 paramètres (Statut Tabagique, IMC, Âge).
    - Classification : Random Forest.
- **Perspectives** :
  - Amélioration des modèles de prédiction avec plus de données.
  - Applications pratiques pour les compagnies d’assurance :
    - Optimisation des offres et personnalisation en fonction des profils de risques.
    - Ciblage des campagnes de prévention et des interventions médicales.
## Utilisation
Clonez ce dépôt et explorez les notebooks pour une analyse détaillée des données et des modèles développés.
