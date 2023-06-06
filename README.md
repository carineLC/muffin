# Jour 6

### <a href="https://github.com/Joz84/ten-hours-of-html-css" target="_blank">Retour au menu principal</a>

## Lien vers la <a href="https://joz84.github.io/day-f.github.io/" target="_blanck">démo</a>

## 5 utilisations de la balise a

### Le lien vers une page d'un autre site (l.76)
```html
<a href="https://www.marmiton.org/recettes/recette_muffins-tres-simples_166385.aspx" target="_blanck" class="btn-pink">En savoir plus</a>
```

### Le lien vers une autre page de son propre site (l.25)
```html
<a href="team.html" class="link">Team</a>
```

### Lien vers une ancre dans la page (l.24)
il faut au préalable identifier la position dans la page où le lien doit renvoyer. pour cela on utilise l'attribut "id".
<br> Par exemple ici nous avons mit cette ancre à la ligne 87 :

```html
<div id="presentation"></div>
```

On utilise alors cette ancre dans la valeur de href du lien en mettant un "#" devant le nom :

```html
 <a href="#presentation" class="link">Présentation</a>
```

### Le lien vers une messagerie email (l.43)
```html
<a href="mailto:contact@mihivai.com" target="_blanck"><i class="fas fa-envelope"></i> : contact@mihivai.com</a>
```
### Le lien vers la création d'un appel téléphonique (.45)
```html
<a href="tel:0618237331" target="_blanck"><i class="fas fa-phone-square-alt"></i> : 06 18 23 73 31</a>
```

## Du code open source : <a href="https://codepen.io/" target="_blanck">Code Pen</a>  
Code Pen est un site permettant au developpeurs de partager librement du code HTML/CSS/JS. Attention le site étant open source, il est courant de trouver du code inexploitable.
<br>
Dans le cadre de ce court nous utiliserons code pen pour intégrer des animations sur notre site.
Pour l'exemple nous allons intégrer le codepen suivant: https://codepen.io/Joz84/pen/YoqNKe

La fenêtre est divisée en 4 parties.
<br>
Les trois parties du présentent le code.
<br>
La partie du bas presente le resultat de ce code.

La partie haute présente, de guauche à droite, les langages suivants : 
* HTML dans la 1ère fenêtre. 
* CSS dans la seconde fenêtre. 
* JS dans la 3ème fenêtre.

Il suffit de coller le HTML dans le fichier index.html là où l'on souhaute mettre l'animation. Dans notre exemple à de la ligne 229-231.
<br>
Le CSS dans le fichier CSS (lignes 190-300). Nous avons modifié les lignes 195, 204 pour que le composant s'adapte au site.

<br>
Le JS dans à la fin du fichier index.html dans une balise <script>...</script> (lignes 277-320)

