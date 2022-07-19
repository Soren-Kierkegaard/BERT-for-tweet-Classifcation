# BERT-for-tweet-Classifcation

Classifier des tweets en fonction de si ils relatent ou non de vrais désastre

Créer purement pour appréhender ce nouveau type de modèle issu des modèles Transformers et comparaison avec d'autres approche section : [ Fine-tuned BERT ]
1. SVM TF-IDF
2. Word2vect
3. Embedding et Convolution (améliorable/perfectible dans l'architeture)
4. BERT (fine-tuned)

Les 2 premières partie concerne ktrain et ne fonctionne pas dût à un problème au sein de la Biliothèque, je pense.

# Repository Files:
```
├── REAMDE.md
├── code.ipynb
├── model.png
└── data *.xlxs/csv
```

# Architecture

- Modèle BERT
-   https://fr.wikipedia.org/wiki/BERT_(modèle_de_langage)
-   https://arxiv.org/abs/1810.04805 

# Attention !

Même sur GPU (pas testé sut TFU) le modèle peu être très long à entrainé (testé sur 10 époches ~ 5H)

Coded in July 2021@
