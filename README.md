# manifestants

Application web pour aider à compter les manifestants à la main.

## Installation

Pour pouvoir importer la vidéo, il te faut héberger cette page sur un serveur web (local ou pas).

Télécharge ta vidéo depuis la [page web](https://www.irif.fr/~charbit/ComptageManifs/Comptage.html) du projet et met le nom du fichier dans la ligne

```javascript
video = p.createVideo('2023-03-07_part58.mp4', () => {
```

## Utilisation

Tu peux contrôler la vidéo avec les trois boutons ou avec les touches `Left`, `Bottom` et `Right`, respectivement. Tu peux aussi régler l'offset horizontal et vertical, le zoom et la taille de la vidéo.

Clique sur la tête d'un manifestant quand il traverse la ligne rouge. Un marqueur sera affiché durant une seconde. S'il marche à contressens, alors clique sur le bouton `Going back`.

Tes clics sont enregistrés dans la zone de texte. Fais des sauvegardes fréquentes. Tu peux importer une sauvegarde simplement en collant le contenu et en cliquant sur le bouton `Import`.
