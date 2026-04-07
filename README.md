# Preprocessing-et-les-Pipelines-avec-Scikit-learn.
L'objectif global est d'apprendre à préparer des données pour le Machine Learning, puis à automatiser ce processus avec des Pipelines.
<br>
Pour résumer les grandes parties de ce tp  :<br>
    <b>Chargement du dataset "diamonds" et split Train/Test (80%/20%)<br>
    Encodage des 3 colonnes catégorielles (cut, color, clarity) avec OrdinalEncoder en respectant l'ordre naturel des diamants<br>
    Normalisation avec MinMaxScaler pour ramener toutes les valeurs entre 0 et 1<br>
    Transformation du test set avec l'encodeur déjà entraîné<br>
    Simplification avec Pipeline pour enchaîner Encodage → Normalisation en une seule étape<br>
    Pipeline composée avec ColumnTransformer pour traiter différemment les colonnes catégorielles et numériques<br>
    Exercices : 3 pipelines de complexité croissante combinant OneHotEncoder, PolynomialFeatures, SelectKBest et MinMaxScaler<br>
    
