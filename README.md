# Prédiction des Maladies Coronaires

## Introduction

L'Organisation mondiale de la santé estime que 12 millions de décès surviennent chaque année dans le monde en raison de maladies cardiaques. Aux États-Unis et dans d'autres pays développés, la moitié des décès sont dus à des maladies cardiovasculaires. Le pronostic précoce des maladies cardiovasculaires est crucial pour permettre aux patients à haut risque de modifier leur mode de vie et ainsi réduire les complications. Ce projet vise à identifier les facteurs de risque les plus pertinents des maladies cardiaques et à prédire le risque global à l'aide de la régression logistique et de la préparation des données.

## Tâche

La tâche principale est de prédire si un patient présente un risque de maladie coronarienne (CHD) sur une période de 10 ans. En plus de cette prédiction, le projet comprend également la création de visualisations des données pour obtenir des informations exploitables.

## Source des Données

Les données utilisées proviennent d'une étude cardiovasculaire en cours sur des résidents de la ville de Framingham, Massachusetts. L'ensemble de données est accessible au public sur Kaggle. Il contient plus de 4 000 observations et 15 variables. Vous pouvez accéder à l'ensemble de données via le lien suivant : [Dataset Cardiovascular Study](https://www.kaggle.com/christofel04/cardiovascular-study-dataset-predict-heart-disea).

## Variables

### Variables Démographiques

- **Sexe** : Homme ou femme ("M" ou "F")
- **Age** : Âge du patient (continu)

### Variables Comportementales

- **Is_smoking** : Si le patient est ou non un fumeur actuel ("YES" ou "NO")
- **CigsPerDay** : Nombre moyen de cigarettes fumées par jour (continu)

### Variables Médicales (Antécédents)

- **BPMeds** : Prise de médicaments contre l'hypertension (nominal)
- **preleventStroke** : Antécédents d'accident vasculaire cérébral (nominal)
- **prevalentHyp** : Hypertension (nominal)
- **Diabetes** : Diabète (nominal)

### Variables Médicales (Actuelles)

- **totChol** : Taux de cholestérol total (continu)
- **sysBP** : Tension artérielle systolique (continu)
- **diaBP** : Tension artérielle diastolique (continu)
- **BMI** : Indice de masse corporelle (continu)
- **heartrate** : Fréquence cardiaque (continue)
- **Glucose** : Niveau de glucose (continu)

### Variable de Prédiction (Cible)

- **TenYearCHD** : Risque de maladie coronarienne à 10 ans (binaire : "1" signifie "Oui", "0" signifie "Non")

## Implémentation

Le projet est implémenté en Java. Les étapes clés comprennent la préparation des données, l'entraînement d'un modèle de régression logistique, et la visualisation des résultats.
