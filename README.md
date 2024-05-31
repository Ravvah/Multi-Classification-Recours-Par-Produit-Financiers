# Multi-Classification-Recours-Par-Produit-Financiers

## Le but est de classer chaque recours de client par le produit financier associé. On procèdera à une classification supervisée


On procedera à un premier nettoyage des données (données manquantes, premieres indications sur notre jeu de donnée)

Ensuite on effectuera un second processing en effectuant l'encodage des labels, la comparaison entre differentes méthodes de vectorization (embedding) du texte.

On procedera ensuite à la comparaison de plusieurs modèles 

Voici un aperçu des approches utilisés

``` 
Projet de Classification Multi-Classes
|
|---> Analyse exploratoire des données ( Le projet est ici pour l'instant )
|
|---> Approche d'Embedding
|        |
|        |---> Voyage 02
|        |       |---> Prétraitement des données
|        |       |---> Génération d'Embeddings
|        |
|        |---> TF-IDF
|                |---> Prétraitement des données
|                |---> Génération d'Embeddings
|
|---> Encodage des Labels
|        |
|        |---> One-Hot Encoding (pour presque tous les modèles)
|        |---> Aucun encodage nécessaire pour certains modèles
|
|---> Modèles de Classification
|        |
|        |---> XGBoost
|        |       |---> Sans équilibrage des classes
|        |       |---> Avec sur-échantillonnage
|        |       |---> Avec sous-échantillonnage
|        |
|        |---> Perceptron Multi-Classe
|        |       |---> Sans équilibrage des classes
|        |       |---> Avec sur-échantillonnage
|        |       |---> Avec sous-échantillonnage
|        |
|        |---> Modèle Non Paramétrique Discriminant (ex : k-NN)
|                |---> Sans équilibrage des classes
|                |---> Avec sur-échantillonnage
|                |---> Avec sous-échantillonnage
```
