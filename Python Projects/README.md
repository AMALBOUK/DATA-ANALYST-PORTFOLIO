# Classification d'images de vêtements Using Deep Neural Network

Dataset: https://www.tensorflow.org/datasets/catalog/fashion_mnist

Fashion MNIST est un jeu de données qui contient 70 000 images en niveaux de gris répartie sur 1 des 10 catégories. Les images montrent des vêtements, d'articles de Zalando , en basse résolution (28 x 28 pixels). La base de données est repartie en un ensemble de 60.000 exemples d'apprentissage et d'un ensemble de 10.000 exemples de test. Cette base de données vise à remplacer le jeu de données MNIST (de chiffres écrit à la main) plus assez complexe dans une logique d'apprentissage automatique.

L'objectif de ce mini projet est la prédiction de la variable cible en utilisant dans un premier temps les algorithmes de Machine Learning traditionnels et dans un second lieu les différentes architectures réseaux de neurones afin de pouvoir comparer les performances obtenues pour les différents modèles utilisés. 

Ci-après les différentes étapes de ce projet:

1. Importation et exploration du dataset

2. Utilisation des différents algorithmes Machine Learning traditionnels:
    
    2.1 Traditional Machine Learning (Régresssion Logistique)

    2.2 Traditional Machine Learning (SVM non linéaire avec un kernel RBF)

3. Utilisation des différentes architectures réseaux de neurones:

    3.1 Classificateur 1: Fully Connected 3 layers NN

    3.2 Observation de l'effet Early Stopping sur le classificateur 1

    3.3 Classificateur 2: CNN avec une architecture LeNet

4. Comparaison des performances obtenues pour les différents modèles utilisés
