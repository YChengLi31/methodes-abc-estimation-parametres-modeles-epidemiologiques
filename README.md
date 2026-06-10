# Méthodes d'Approximate Bayesian Computation (ABC) pour l'estimation de paramètres dans des modèles épidémiologiques.

Ce dépôt contient un projet réalisé en collaboration avec Damien Grandey et encadrée par Mme Kaakaï sur des implémentations et des exemples d’utilisation des méthodes d’Approximate Bayesian Computation (ABC) appliquées à l’estimation de paramètres dans des modèles épidémiologiques.

# **Objectif**

L’objectif est d’estimer des paramètres de modèles épidémiologiques complexes (par exemple un modèle de type SIR) lorsque la fonction de vraisemblance est difficile ou impossible à calculer.

Les méthodes ABC permettent de contourner ce problème en :

- simulant des données à partir du modèle,
- comparant ces simulations aux données observées via des statistiques résumées,
- conservant les paramètres qui produisent des simulations proches des observations.

# **Application**

Les méthodes présentées peuvent être utilisées pour :

- l’estimation du taux de transmission (β)
- l’estimation du taux de guérison (γ)
- l’étude de dynamiques épidémiques simulées
- la comparaison de modèles

# **Contenu du dépôt**

- Notebook : simulation les résultats pour le cas 1 (données simulées) et cas 2 (données réelles)
- data : jeux de données simulées

# **Prérequis**

Cas 1 :  
- Language R
- librairie deSolve

Cas 2 : 
- Language R
- librairie deSolve
- librairie tmvtnorm




