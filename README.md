# Timeliner

Par rapport à la version originale https://github.com/zz85/timeliner cette version implémente :
1. l'affichage du nom associé au timeliner
2. le choix de faire tourner en boucle
3. des paramètres suplémentaires pour chaque layer :
* suppression d'un layer
* identifiant d'un object
* propriété de l'objet
* valeur textuelle 
4. une méthode d'agrégation des actions pour chaque objet

It is written in javascript and meant to work with different javascript libraries or webgl frameworks, in 1d, 2d, or 3d. It is built primary for myself, but feel free to send me suggestions or requests.


## Demo

# [Example](https//samszo.github.io/timeliner/test.html)

![screenshot](screenshot.png)


## Usage

Include the timeliner.js file.

```js
<script src="timeliner.js"></script>
```

or import via ES modules

```js
import { Timeliner } from './build/timeliner.min.js'
```

Load data by code, file upload or loading from saved localStorage.


### Add a keyframe

1. double click on the timeline

or

1. Select a time on the timeline
2. Click on the keyframe

### Add a tween
1. Select time between 2 keyframes
2. Select easing type from the dropdown


## Releases

2.0.1
- custom from initial fork

## TODO
- graph selection of DOM object
- a whole ton more
