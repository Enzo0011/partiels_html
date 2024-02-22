# Sliders, les mondes parallèles ;-)

Ce projet de diaporama interactif permet de parcourir une série d'images avec des légendes et offre plusieurs fonctionnalités pour améliorer l'expérience utilisateur.

## Fonctionnalités

### Navigation dans le Diaporama
- **Navigation Manuelle** : Les utilisateurs peuvent naviguer entre les images du diaporama en utilisant les boutons suivants :
  - **Précédent** : Affiche l'image précédente dans le diaporama.
  - **Suivant** : Affiche l'image suivante dans le diaporama.
- **Lecture Automatique** : Le diaporama peut démarrer une lecture automatique, changeant d'image toutes les 2 secondes.
- **Navigation Aléatoire** : Affiche une image aléatoire du diaporama.

### Barre d'Outils
- **Affichage/Caché** : La barre d'outils peut être affichée ou cachée en cliquant sur le lien "Barre d'outils". L'icône change de direction (haut/bas) selon l'état de la barre d'outils.

### Interaction au Clavier
- Les utilisateurs peuvent également naviguer entre les images en utilisant les touches fléchées gauche et droite du clavier.

## Mise en Œuvre

### Technologies Utilisées
- **HTML** : Structure de base du diaporama et de la barre d'outils.
- **CSS** : Styles pour le diaporama, y compris la rotation des images, le fond blanc avec ombre fine pour les images actives, et le design de la barre d'outils.
- **jQuery** : Logique pour la navigation du diaporama, la gestion des événements de la barre d'outils, et l'interaction au clavier.

### Structure du Projet
- **index.html** : Le fichier principal contenant la structure du diaporama et la barre d'outils.
- **css/slider.css** : Contient tous les styles CSS pour le diaporama et la barre d'outils.
- **jQuery** : Utilisé pour ajouter l'interactivité au diaporama (Inclus via CDN dans le fichier HTML).
- **js/script.js** : Contient tout la logique en javascript.

## Démarrage
Pour utiliser le diaporama, ouvrez le fichier `index.html` dans un navigateur moderne. Aucune installation supplémentaire n'est nécessaire.
