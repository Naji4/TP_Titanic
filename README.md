# Exercice de Travail Pratique – Analyse du Titanic avec R  

Ce repository contient un exercice de travail pratique réalisé dans le cadre de la matière **Techniques pour la Science des Données**. L'objectif est d'analyser le comportement des données de la base de données **Titanic** en utilisant **R**.  

## Données  
Les données utilisées proviennent du package **{titanic}** disponible sur R. Elles peuvent être chargées directement via la commande suivante :  

```r
install.packages("titanic")
library(titanic)
data("titanic_train")
```

## Technologies utilisées  
- **R** et **RStudio**  
- Librairies courantes pour l'analyse de données : `tidyverse`, `ggplot2`, `dplyr`, `titanic`  

## Objectifs de l'analyse  
- Nettoyage et préparation des données  
- Exploration des variables (âge, classe, sexe, etc.)  
- Visualisation des tendances et relations  
- Modélisation et prédiction des survivants (optionnel)  

## Comment exécuter le projet  
1. Cloner ce repository :  
   ```bash
   git clone https://github.com/Naji4/TP_Titanic.git
   ```
2. Ouvrir le fichier **Titanic_analysis.R** dans RStudio  
3. Installer les packages nécessaires :  
   ```r
   install.packages(c("titanic", "tidyverse", "ggplot2", "dplyr"))
   ```
4. Charger les données et exécuter les scripts pour explorer les résultats  

## Contributions  
Les contributions sont les bienvenues. Vous pouvez ouvrir une issue ou soumettre une pull request si vous souhaitez améliorer l'analyse.  

## Licence  
Ce projet est sous licence MIT.  
