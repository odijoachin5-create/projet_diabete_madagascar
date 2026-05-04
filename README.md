# Prediction du Risque de Diabete - Madagascar

## Objectif
Analyser les donnees patients d'un hopital malgache et predire le risque de diabete.

## Technologies
- Python (pandas, scikit-learn, statsmodels)
- PostgreSQL 18
- Machine Learning (Random Forest, Gradient Boosting)

## Pipeline
1. Extraction SQL depuis PostgreSQL
2. Nettoyage des donnees
3. Analyse exploratoire (EDA)
4. Tests statistiques et odds ratios
5. Modele ML avec cross-validation
6. Dashboard de visualisation

## Resultats
- AUC-ROC > 0.75
- Facteurs de risque identifies : age, nombre de consultations
