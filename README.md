# manifestants

Application web pour aider à compter les manifestants à la main.

## Installation

Pour pouvoir importer la vidéo, il te faut héberger cette page sur un serveur web local ou pas.

Télécharge ta vidéo depuis la [page web](https://www.irif.fr/~charbit/ComptageManifs/Comptage.html) du projet met le nom dans la ligne

```javascript
video = p.createVideo('2023-03-07_part58.mp4', () => {
```

Selon la taille de ton écran, tu peux modifier cette partie du code :

```javascript
// set_video_height(600)
set_video_width(1400)
```

## Utilisation

Tu peux controller la vidéo avec les trois boutons ou avec touches `Left`, `Bottom` et `Right`, respectivement.

Clique sur la tête d'un manifestant quand il traverse la ligne rouge. Un marqueur sera affiché durant une seconde.

Tes clics sont enregistrés dans la zone de texte. Fais des sauvegardes fréquentes. Tu peux importer une sauvegarde simplement en collant le contenu et en cliquant sur le bouton `Import`.
