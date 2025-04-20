# Analyse de Sentiments sur des Critiques de Films – Projet NLP

Ce projet a pour objectif d'analyser des critiques de films et séries afin de déterminer si elles sont **positives** ou **négatives**, en utilisant des techniques classiques de NLP (**Word2Vec**) combinées à une approche moderne basée sur **Transformers** via la bibliothèque Hugging Face.


##  Objectifs

- Nettoyer et prétraiter un échantillon de 1000 critiques.
- Représenter les textes sous forme vectorielle avec **Word2Vec**.
- Appliquer un modèle de classification classique.
- Utiliser le pipeline `sentiment-analysis` de Hugging Face pour une classification automatisée.
- Comparer les performances des deux approches.

---

## Structure du Projet
1. **Exploration** des données (`01_exploration.ipynb`)
2. **Prétraitement** : nettoyage, lemmatisation (`02_preprocessing.ipynb`)
3. **Vectorisation** avec **Word2Vec** (`03_word2vec_model.ipynb`)
4. **Classification** avec un modèle supervisé (`04_classification.ipynb`)
5. **Analyse des sentiments avec Transformers** (`05_transformers_labeling.ipynb`)

## Librairies Utilisées
**NLTK, Gensim (Word2Vec)

**scikit-learn (modèles de classification)

**Hugging Face Transformers (pipeline("sentiment-analysis"))

**Pandas, NumPy, Matplotlib, Seaborn


