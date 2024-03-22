# 32_analyse_sentiment_nlp_part_2

Analyse de Sentiment : Introduction au Traitement Automatique du Langage Naturel - Deuxième Partie

I. Introduction
Dans cette deuxième partie de notre exploration du traitement automatique du langage naturel (TALN), nous aborderons le processus de transformation des mots en vecteurs, mettant en lumière les avantages significatifs de cette vectorisation.

II. Contexte du Projet
Dans le précédent exposé, nous avons examiné les méthodes pour encoder des mots en chaînes de caractères en nombres entiers et pour convertir une séquence de mots en vecteurs One-Hot. L'objectif actuel est de comprendre comment encoder des mots numérisés en nombres entiers sous la forme de vecteurs avec des coordonnées en nombres flottants. Pour clarifier cette idée, nous proposerons une présentation sous forme de notebook (entre 5 et 10 markdown) sur les points clés suivants :

*Word2Vec
*GloVe
*Word Embeddings

Ces approches permettent la transformation des mots, initialement encodés en nombres entiers, en vecteurs aux propriétés remarquables.

III. Mise en Pratique
La prochaine étape consiste à intégrer une couche de Word Embedding en tant qu'entrée dans un perceptron multicouche, en utilisant TensorFlow/Keras. Cette couche transformera les mots, représentés par des nombres entiers dans la base de données IMDb, en vecteurs. Le réseau de neurones doit ensuite être entraîné dans son ensemble pour effectuer l'analyse de sentiment sur la base de données IMDb.

IV. Activité Facultative
Pour les participants avancés, une activité facultative consiste à explorer l'intégration de couches de Word Embedding pré-entraînées (Transfer Learning) telles que Word2Vec, GloVe, ou d'autres. Le Fine-Tuning sur la base de données IMDb sera également réalisé, suivi d'une conclusion.

V. Livrables
Le résultat de ce travail sera présenté sous la forme d'un Jupyter Notebook.

VI. Critères de Performance
Les critères d'évaluation incluent la clarté et la pertinence de la présentation ainsi que la qualité du code Python dans le notebook.
