# Projet-de-pr-vision-des-prix-des-vols
## Introduction
Ce projet vise à développer un modèle de prévision des prix des vols pour faciliter la planification des voyages.

## Objectifs du Projet
- Développer un modèle de prévision des prix des vols avec une précision minimale de 80%.
- Analyser l'impact des variables telles que la date, l'heure, le nombre d'escales et la compagnie aérienne sur les prévisions.

## Contenu du Projet
1. [Planification Complète du Projet](#planification-complète-du-projet)
2. [Rapport de Mi-Parcours](#rapport-de-mi-parcours)
3. [Rapport Final](#rapport-final)
4. [Fichiers R Markdown et HTML](#fichiers-r-markdown-et-html)

## Planification Complète du Projet
### Contexte du Projet
Les fluctuations des prix des vols posent un défi important pour les voyageurs. La prévision précise de ces prix peut grandement faciliter la planification des voyages.

...

## Rapport Final
### Récapitulation des Résultats
- Le modèle atteint  l'objectif initial de 80%.
- Les variables significatives incluent la durée, le nombre de jours restants, la classe économique, et la classe affaires.

### Méthodologie
1. **Modèles de Régression :**
   - Utilisation de régression linéaire pour modéliser les relations linéaires.
   - Entraînement et évaluation du modèle sur un ensemble d'entraînement et de test.

2. **Ensemble d'Arbres de Décision :**
   - Exploration des modèles d'arbres de décision pour capturer des relations non linéaires.

3. **Ingénierie des Caractéristiques :**
   - Création d'indicateurs de classe et gestion des valeurs manquantes.

### Visualisations
- Histogramme de la distribution des prix.
- Graphique interactif montrant la distribution des prix en fonction des compagnies aériennes et des plages de prix sélectionnées.

### Évaluation de la Performance
- MSE (Mean Squared Error) pour évaluer la performance du modèle.

### Conclusion
Le projet a atteint ses objectifs avec succès en développant un modèle performant pour la prévision des prix des vols. Les analyses détaillées soulignent l'importance des variables telles que la durée du vol et le nombre de jours restants.

## Fichiers R Markdown et HTML
Le fichier R Markdown (`.Rmd`) contient le code et la documentation détaillée de l'analyse. Pour générer le rapport final, vous pouvez tricoter le fichier R Markdown pour créer un fichier HTML. Vous pouvez accéder au rapport final ( voir dans les documents ajoutés).


## Comment Utiliser ce Projet
### Installation
1. Assurez-vous d'avoir R et RStudio installés sur votre machine.
2. Téléchargez les fichiers du projet depuis ce lien :
3. Ouvrez le fichier R Markdown dans RStudio.

### Exécution du Projet
1. Exécutez le code dans le fichier R Markdown pour reproduire l'analyse.
2. Pour générer le rapport final au format HTML, utilisez l'option "Knit" dans RStudio.

### Dépendances
Assurez-vous d'avoir les bibliothèques suivantes installées :
```R
install.packages(c("tidyverse", "caret", "glmnet"))
