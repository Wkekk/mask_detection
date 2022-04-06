# Implémentation de l'algorithme VGG16 avec Keras

## Les données et l'objectif

L'objectif de ce brief est la création d'une IA capable de reconnaitre si une personne porte un masque chirurgical ou non. Pour cela nous avons utilisé une banque de photos de personnes avec et sans masque pour entraîner cette IA. Les données ont été séparées entre photos et labels. Afin d'améliorer le data set nous avont mis en place une data augmentation (via keras également) en pivotant et zoomant sur certaines images.

## L'algorithme

Nous avons mis en place l'algorithme du VGG16 en utilisant keras et en créant un modèle avec une couche VGG, une couche flatten et 3 couches dense. Une fois le modèle mis en place nous auvegardons sa meilleure version afin de pouvoir l'utiliser en test live avec caméra.

## Les test live

pour les tests live il faut éxecuter le fichier `live.py` qui permet l'activation de la caméra et la reconnaissance du port de masque ou non.

## Les difficultées rencontrée lors de se projet

Un manque de vision clair de notre part à quelque peu entravé notre départ sur la mise en place de l'algorithme, la partie traitement des données ayant été faites plutôt facilement et ne comportais pas de grande difficulté. 
Quelque problème d'adptation à google colab ont aussi été visible, c'était la premièere fois que nous utilisions se support, mais une fois habitué celà n'as pas posé plus de soucis que ça (note personnelle : pour ma part des problème d'interaction avec mon drive ont été notées mais ont pu être surpassées également sans trop de difficulté) 