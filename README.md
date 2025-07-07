# Multi-Classification-Recours-Par-Produit-Financiers

## Le but est de classer chaque recours de client par le produit financier associé. On procèdera à une classification supervisée sur du texte (NLP)

Projet secondaire interrompu pour le moment.

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
|        |---> Transformers
|        |       |---> Prétraitement des données
|        |       |---> Génération d'Embeddings
|        |
|        |---> Skip-Gram avec Negative Sampling
|                |---> Prétraitement des données
|                |---> Génération d'Embeddings
|
|---> Modèles de Classification
|        |
|        |---> XGBoost
|        |
|        |---> Modèle Bi-Encoder SBERT
```
