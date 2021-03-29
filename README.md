# [Exercice] EDA - Recherche d'éléments permettant d'expliquer le prix d'une maison

.
├── .vsode
├── data
│   └── ee654666-9d19-402e-9b80-5b70e4bcfe2d.csv
├── NOTEBOOK
│   └── EDA_CLEAN.ipynb
├── .gitignore
├── main.py
├── README.md
└── requirements.txt



# Contexte du projet

Afin de mieux comprende ce qui influe le prix de vente d'une maison vous avez été missionné pour réaliser une analyse exploratoire de données sur un jeu de données comportant un ensemble de maisons avec leur caractéristiques et leur prix de vente.

La donnée est de bonne qualité. Votre analyse ne se concentrera donc pas sur cette partie mais plutôt sur la partie statistiques, mise en avant de corrélations, visualisations de la distribution des variables afin de mettre en avant certaines variables qui serait suceptible ou non d'expliquer le prix d'une maison.

​

Voici la liste des choses qui vous sont demander:

Importez la donnée
Affichez les 10 première lignes du jeux de données
Utilisez le .info()
Supprimez de façon automatique les variables avec plus de 30% de valeurs manquantes
Affichez avec un describe les informations de SalePrice
Affichez la distribution de SalePrice avec un distplot. Conclure sur la graphique: Que pouvez vous dire?
​

Focus variables quantitatives:

Sélectionnez les variables int64 + float64 afin d'afficher les histogrammes pour l'ensemble de ces variables. Qu'elles sont les variables ayant une distribution proche de SalePrice? Que peut on conclure de ces variables?
Toujours sur les variables int64 + float64: Affichez les 10 variables les plus corrélées avec SalePrice (Avec Pandas il est possible de calculer les corrélation avec .corr()).
Toujours sur les variables int64 + float64: Réalisez un pairplot permettant d'afficher la relation entre SalePrice et les variables sélectionnés. Qu'elle est la forme des plot croisant les 3 variables les plus corrélées avec SalePrice?
Réalisez une heatmap afin de visualiser d'une autre manière les corrélations 2 à 2. Y'a t'il des variables fortement corrélées entre elles? Identifiez les 3 pairs les plus corrélées
Sur cette sélection de variables: ['TotalBsmtSF', '1stFlrSF', '2ndFlrSF', 'GrLivArea', 'FullBath', 'TotRmsAbvGrd', 'GarageCars', 'GarageArea', 'SalePrice'] réalisez un regplot permettant de croiser ces variables avec SalePrice.
En vous inspirant de: https://stackoverflow.com/questions/25579227/seaborn-implot-with-equation-and-r2-text Afficher le jointplot avec le coefficient de pearson pour le croisement SalePrice & GrLivArea.
​

Focus variables qualitatives:

Réalisez un code permettant d'identifier automatiquement les variables de type Object
Sur la liste de variables obtenus, utilisez un countplot sur toutes les variables
Listez au moins 5 variables que ne vous semble pas pertinente pour expliquer le prix d'une maison.
En bonus (pour les plus rapides):

Inspirez vous de: https://www.kaggle.com/dansbecker/your-first-machine-learning-model pour créér votre premier modèle de ML avec le modèle suivant: https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html

# Modalités pédagogiques

2 à 3 jours en individuel


# Livrables

Un notebook répondant à l'ensemble des questions

# Critères de performance

Le notebook doit répondre à l'ensemble des questions de l'énoncé.


# Modalités d'évaluation

Au moins 80% des réponses attendus sont bonnes.