# Memory

Le but est de coder un mini-jeu en HTML / CSS / JS.  
Il s’agit du jeu “memory” :

* Des cartes sont disposées face cachée à l'écran.

* Le joueur doit cliquer sur deux cartes. Si celles-ci sont identiques, la paire est validée. Sinon, les cartes sont retournées face cachée, et le joueur doit sélectionner une nouvelle paire de cartes.

* Le joueur gagne s'il arrive à découvrir toutes les paires avant la fin du temps imparti.

![jeu memory](docs/images/jeu-memory.png)

Ready? C'est parti !

## Instructions

1. [On installe](docs/1_on-installe.md)
2. [On retourne](docs/2_on-retourne.md)
3. [La face visible](docs/3_la-face-visible.md)
4. [Une paire ?](docs/4_une-paire.md)
5. [Veni, vidi, vici](docs/5_veni-vedi-vici.md)
6. [Compte à rebours](docs/6_compte-a-rebours.md)

Pour ceux qui ont envie de pousser le bouchon, c'est par ici : [BONUS](docs/7_bonus.md)

## Conseils

Si la tâche semble harassante, pas d’inquiétude ! Chaque étape est détaillée pour avancer petit à petit. Ne vous précipitez pas, et faites les choses bien. Quelques conseils :

* Lisez tout l’énoncé dès le début, pour savoir où vous allez.

* Prenez le temps de coder, en commentant votre code dès qu’il est nécessaire, pourquoi pas en copiant la consigne en commentaire.

* Gardez des fonctions simples, qui ne font qu’une seule chose, pour mieux vous y retrouver.

* Plus les premières étapes seront bien codées, plus la suite sera facile !

* Quelques liens vous sont glissés à chaque étape pour vous donner des indices, mais aussi vous permettre de bien comprendre ce qui est demandé.

---

Amusez-vous bien, et allez le plus loin possible ! ✌️

## Notions à utiliser

### HTML

- [Appeler une feuille de style CSS](https://developer.mozilla.org/fr/docs/Web/HTML/Element/link) [#](https://github.com/O-clock-Galaxy/correction-evaluation-js-memory/blob/master/index.html#L6)
- [Appeler un script Javascript](https://developer.mozilla.org/fr/docs/Web/HTML/Element/script) [#](https://github.com/O-clock-Galaxy/correction-evaluation-js-memory/blob/master/index.html#L23)

### CSS

- [Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) [#](https://github.com/O-clock-Galaxy/correction-evaluation-js-memory/blob/master/css/style.css#L20)
- [Sélecteur au survol de la souris d'un élément avec `:hover`](https://developer.mozilla.org/fr/docs/Web/CSS/%3Ahover) [#](https://github.com/O-clock-Galaxy/correction-evaluation-js-memory/blob/master/css/style.css#L70)
- [Sprites](https://www.alsacreations.com/tuto/lire/1068-sprites-css-background-position.html) [#](https://github.com/O-clock-Galaxy/correction-evaluation-js-memory/blob/master/js/app.js#L125)

### JavaScript

- [Conditions `if`](https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Instructions/if...else)
- [Boucles `for`](https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Instructions/for) [#](https://github.com/O-clock-Galaxy/correction-evaluation-js-memory/blob/master/js/app.js#L101)
- [Tableaux](https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Objets_globaux/Array)  [#](https://github.com/O-clock-Galaxy/correction-evaluation-js-memory/blob/master/js/app.js#L159)
- [Création d'éléments DOM avec `jQuery("<div />")`](http://api.jquery.com/jQuery/#jQuery2)  [#](https://github.com/O-clock-Galaxy/correction-evaluation-js-memory/blob/master/js/app.js#L117)
- [Ajout d'éléments DOM enfants avec `jQuery.append()`](http://api.jquery.com/append/)  [#](https://github.com/O-clock-Galaxy/correction-evaluation-js-memory/blob/master/js/app.js#L132)
- [Manipulation des classes d'un élément DOM avec jQuery](https://api.jquery.com/category/manipulation/class-attribute/) [#1](https://github.com/O-clock-Galaxy/correction-evaluation-js-memory/blob/master/js/app.js#L192)  [#2](https://github.com/O-clock-Galaxy/correction-evaluation-js-memory/blob/master/js/app.js#L230)
- [Ajout d'événements sur un élément DOM avec jQuery](https://api.jquery.com/on/) [#](https://github.com/O-clock-Galaxy/correction-evaluation-js-memory/blob/master/js/app.js#L140)
- [Afficher ou cacher un élément DOM avec jQuery](https://api.jquery.com/category/effects/basics/) [#](https://github.com/O-clock-Galaxy/correction-evaluation-js-memory/blob/master/js/app.js#L194)
- [Modifier le style d'un élément DOM avec jQuery](http://api.jquery.com/css/) [#](https://github.com/O-clock-Galaxy/correction-evaluation-js-memory/blob/master/js/app.js#L125)
- [Exécuter un code après laps de temps](https://developer.mozilla.org/fr/docs/Web/API/WindowTimers/setTimeout) [#](https://github.com/O-clock-Galaxy/correction-evaluation-js-memory/blob/master/js/app.js#L226)
- [Afficher un message avec `window.alert`](https://developer.mozilla.org/fr/docs/Web/API/Window/alert) [#](https://github.com/O-clock-Galaxy/correction-evaluation-js-memory/blob/master/js/app.js#L283)
- [Animation avec jQuery](http://api.jquery.com/animate/)
