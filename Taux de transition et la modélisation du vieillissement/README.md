# Méthodes ABC pour l'estimation de taux de transition en épidémiologie et pour la modélisation du vieillissement.

Ce dépôt contient les implémentations et les exemples d'utilisation de la méthode Approximate Bayesian Computation - Sequential Monte Carlo (ABC-SMC) appliquée à l'estimation des paramètres d'un modèle mathématique décrivant le vieillissement de populations de Drosophila melanogaster

# **Objectif**

L'objectif est d'estimer les paramètres d'un modèle probabiliste de vieillissement lorsque la fonction de vraisemblance est difficile, voire impossible, à calculer directement.

Le modèle décrit deux phases du vieillissement :

  - Phase Non-Smurf, correspondant à une mouche dont la barrière intestinale est intacte
  - Phase Smurf, caractérisé par une perte de cette barrière et une augmentation importante du risque de décès

La méthode ABC-SMC permet d'estimer les paramètres du modèle en :

  - simulant des populations à partir du modèle mathématique
  - comparant les simulations aux données observées à l'aide de différentes fonctions de distance 
  - conservant les paramètres produisant les simulations les plus proches des observations

# **Application**

Les méthodes proposées permettent notamment :

  - l'estimation des paramètres de transition F, G, H (loi de Gompertz-Makeham) 
  - l'estimation des paramètres de mortalité K1, K2, D (taux de mortalité exponentiellement décroissant) 
  - la validation du modèle sur des données simulées 
  - l'application de l'algorithme ABC-SMC à des données expérimentales réelles 
  - l'analyse de la dynamique des populations Non-Smurf, Smurf et des individus décédés 

# **Contenu du dépôt**

  - Notebooks : - Simulation de la dynamique des populations
                - Utilisation de l'ABC-SMC afin d'estimer les paramètres sur les données simulées et réelles
                - Analyse et visualisation des histogrammes des paramètres acceptés  

# **Prérequis**

CODE_PARTIE_1_2 : 
  - language R
  - librairie tmvtnorm


CODE_PARTIE_3 : 
  - language R
  - librairie tmvtnorm
  - librairie readxl
  - librairie dplyr
  - librairie ggplot2





