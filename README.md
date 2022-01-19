# H3_Deep_Learning
Deep learning course FastAI

L'objectif d'un algorithme de machine learning est de pouvoir produire un output en recevant un input qu'il n'a possiblement jamais rencontré pendant sa phase d'entrainement.

Les réseaux de neurones permettent de répondre de manière adaptative à des problèmes à la fois généraux et spécifiques. Les réseaux de neurones permettent de calculer l'erreur, et de back-propager l'erreur pour réajuster les poids appliqués au réseau. 

On peut se poser la question de l'overfitting ou surentrainement lorsque l'on obtient une accuracy très élevée. Pour éviter le surentrainement, on sépare les jeux de données en données d'entrainement et données de test. Au besoin on peut même avoir un jeu de validation.

Entrainer des algorithmes robustes par rapport au bruit, au biais, c'est entrainer un algorithme fiable sur les données réelles. Cela permet d'avoir une erreur forte au début mais qui se réduit au fur et à mesure, on peut alors comparait les courbes de train et de test jusqu'à atteindre un fitting idéal et d'éviter l'overfitting.

Transfert Learning : le modèle de base répond à un problème général, mais il est possible de l'entrainer pour répondre à des problèmes spécifiques.

# Glossaire
epoch : etapes, itération d'entrainement
batch size : taille de l'échantillon
bloc de convolution : couches de convolution + pooling


# 02-Dogs
Check if the picture of a dog is a retriever, a doberman or a husky
Binder voila render

Ajout du fichier pkl (fichier de poids) associé au modèle pour permettre le render par Voila.

https://mybinder.org/v2/gh/elisa-desmetz/H3_Deep_Learning/HEAD?urlpath=%2Fvoila%2Frender%2Fdog_classifier.ipynb

# 03-Atelier Karas
Différentes couches, différentes façon de processer les données. Chaque couche d'un réseau de neurone est un neurone i prenant l'output du neurone i-1 et sortant une valeur pour le neurone i+1.
