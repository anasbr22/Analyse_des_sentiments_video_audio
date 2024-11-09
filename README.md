
# Analyseur de Sentiments

Ce projet est une application d'analyse de sentiments permettant d'analyser les émotions détectées à partir de vidéos, d'images et de flux de caméra en temps réel. L'application utilise une interface graphique Tkinter et des modèles Keras pour le traitement et la classification des émotions.


## Prérequis

Assurez-vous que vous avez Python 3.x installé, ainsi que `pip` pour installer les dépendances requises.



## Utilisation

1. Lancez l'application avec :
    ```bash
    python index.py
    ```
2. Utilisez l'interface pour importer une vidéo ou accéder au flux de la caméra.
3. Les résultats de l'analyse d'émotions seront affichés dans les sections `Résultat Vidéo` et `Résultat Audio`.

## Fonctionnalités

- **Import de Vidéo** : Chargez une vidéo pour analyse des émotions.
- **Analyse en Temps Réel** : Utilisez la caméra pour détecter et analyser les émotions en direct.


## Dépendances

Les bibliothèques suivantes sont nécessaires pour faire fonctionner ce projet :

- `tkinter` : Interface graphique.
- `opencv-python` : Pour la manipulation d'images et la détection de visages.
- `Pillow` : Traitement d'images.
- `moviepy` : Manipulation de fichiers vidéo.
- `pygame` : Contrôle du volume audio.
- `keras` : Pour la création et le chargement du modèle de classification.
- `pycaw` : Contrôle du volume système.

