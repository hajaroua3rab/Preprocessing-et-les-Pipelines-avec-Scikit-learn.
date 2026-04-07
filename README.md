# Preprocessing-et-les-Pipelines-avec-Scikit-learn.
L'objectif global est d'apprendre à préparer des données pour le Machine Learning, puis à automatiser ce processus avec des Pipelines.
<br>
Pour résumer les grandes parties de ce tp  :<br>
    <b>Chargement du dataset</b> "diamonds" et split Train/Test (80%/20%)<br>
    <b>Encodage des 3 colonnes catégorielles</b>  (cut, color, clarity) avec OrdinalEncoder en respectant l'ordre naturel des diamants<br>
    <b>Normalisation avec MinMaxScaler</b>  pour ramener toutes les valeurs entre 0 et 1<br>
    <b>Transformation du test set</b>  avec l'encodeur déjà entraîné<br>
    <b>Simplification avec Pipeline </b> pour enchaîner Encodage → Normalisation en une seule étape<br>
   <b>Pipeline composée avec ColumnTransformer</b>  pour traiter différemment les colonnes catégorielles et numériques<br>
    <b>Exercices : </b> 3 pipelines de complexité croissante combinant OneHotEncoder, PolynomialFeatures, SelectKBest et MinMaxScaler<br>
    
