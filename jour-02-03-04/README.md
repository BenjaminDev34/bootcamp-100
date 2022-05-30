# Journée 02 - Découverte HTML-CSS

## Objectifs apprenants
- Comprendre le rôle du html et du css
- Réaliser une page simple en html et css

## Objectifs formateurs
- Captiver l'attention des apprenants à l'aide d'exercices ludiques
- Gérer le rythme des apprenants

### Moyen d'évaluation des objectifs
- Taux de réponses justes aux sondages
- Les exercices sont réalisés
- En fin de journée le formateur s'auto-évalue en questionnant les apprenants

### Contenu - PAS à PAS

## Intro

- **Posible d'utiliser ce petit support :** https://docs.google.com/presentation/d/18SrBw8s0t0CsLqcr7vDyxnQ_Jb8m9XYNLPrP43QAqMw/edit#slide=id.p
- Petit historique rapide du web
- Le rôle du navigateur.
- rapide explication serveur/client
- **Utilisation du support de fabio :**  https://fabioclock.github.io/front-back/
- Profitez-en pour faire un lien avec la journée de la veille en faisant un rappel sur les métiers back/front/fullstack...

## Le HTML ET LE CSS c'est quoi ?

- HTML : https://developer.mozilla.org/fr/docs/Web/HTML
- CSS : https://developer.mozilla.org/fr/docs/Web/CSS
- Aller sur un site internet et enlever le css (extension disable html) pour montrer comment les deux sont complémentaires
- Montrer l'envers du décor à l'aide de l'inspecteur de chrome
- Comment on écrit du html et du css (parler des différents éditeurs de textes)

## Apprendre en codant : Qui suis-je en HTML 

- Expliquer la syntaxe (balise, balise auto fermante, indentation)
- Passer sur codeSandBox, template créer avec la structure : https://codesandbox.io/s/premiere-page-857siy?file=/index.html
- Penser à commender le code, il servira de support pour les apprenants

**A partir d'ici on essai de les faire pratiquer un maximum, 2 ou 3 nouvelles balises qu'on montre, ils appliquent les balises, le but étant qu'ils s'amusent et de minimiser le magistral**

- On explique les balises déjà présentent dans la structure
- On introduit les balises : ``` <h1>, <p>, <a>, <img> ```
- exemple à coder devant eux, ils font leur propre version une fois les balises expliquées :

```html
<h1>Bailly Benjamin</h1>
<p>Je m'appelle Bailly Benjamin, je suis formateur dans l'organisme de formation O'clock, j'ai 28 ans, je suis marié et j'ai 1 enfants</p>
<p>
    <a href="https://stackoverflow.com/">Lien du site que je consulte le plus tous les jours</a>
</p>
<img src="https://images.unsplash.com/photo-1518020382113-a7e8fc38eac9?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=717&q=80" alt="photo de moi">
```   
- Les balises : ``` <h2>, <ol>, <ul> ```

```html 
  <h2>Mes hobbies</h2>
    <ul>
        <li>Handball</li>
        <li>Football</li>
        <li>Tout ce qui finit en ball ...</li>
        <li>Jeux vidéos</li>
    </ul>
    <h2>Mes repas préférés</h2>
    <ol>
        <li>Fondue savoyarde</li>
        <li>Hamburger</li>
        <li>Raclette</li>
    </ol>
```
- Les balises : ``` <em>, <strong> ```
- Pour les balises, plus haut vous pouvez réutiliser le premier paragraphe. **C'est un atelier de découverte, il est possible de faire un point sur la différence style / sémantique mais il n'a pas besoin d'être compris**

## TP : Pancake 

- Afin de faire mettre en pratique tout ce que l'on vient de voir, faire réaliser une page HTML à partir d'une photo aux apprenants (tp_pancake.png).
- Il faut bien laisser le temps au groupe, répondre aux questions.
- Exo bonus pour les plus rapides ...
- A l'aide de votre ami google, cherchez comment faire en css les choses suivantes :
- Mettre une couleur de fond de votre choix sur toute le body https://developer.mozilla.org/fr/docs/Web/CSS/background-color
- Rétrécir l'image à 400 pixel de largeur et 250 pixel de hauteur

**Selon le timing, correction en livecode ou sinon envoi de la correction, profiter du bonus pour faire le lien avec la suite**

## Apprendre en codant : Ameliorons le pancake

- Refaire un point si ce n'est déjà fait sur le css, le fichier style qui est à part et comment il est appelé 
- le background et l'image ont déjà été redimensionné suite à la correction du bonus, si ce n'est pas fait commencer par ça.
- expliquer rapidement la notion de selecteur

```css
body{
    background-color : #e1b382;
}

img{
    width: 400px;
    height: 250px;
}
```

- On aimerait centrer le tout

```css
body{
    background-color : #e1b382;
    text-align : center;
}
```
- Les listes ne rendent pas bien avec le centrage, on va enlever les puces
- En profiter pour faire le point CSS POUR LA FORME et HTML pour la sémantique

```css
ol,
ul {
  list-style: none;
}
```

- Avec la nouvelle couleur de fond la couleur noir fait un peu trop sombre sur nos textes, on va passer les textes en blanc

```css
body {
  background-color: #e1b382;
  text-align: center;
  color: white;
}
```
- Tout mettre en blanc, c'est un peu violent... Mini tp : laisser les apprenants changer la couleur de tout les titres et du lien par la couleur de leur choix
- Bonus, demandé d'enlever le soulignement du lien

```css
h1,
h2,
h3 {
  color: #2d545e;
}
a {
  color: #2d545e;
  text-decoration: none;
}
```

- Changer le css d'un lien, rend le passage de la souris dessus moins dynamique (pas de changement de couleur), il est possible de changer cela
- expliquer hover https://developer.mozilla.org/fr/docs/Web/CSS/:hover
```css
a:hover {
  color: #12343b;
}
```

- Créer une sorte de carte de cuisine en jouant avec la taille du body et la couleur de l'arriere plan (html)

```css
body {
  background-color: #e1b382;
  text-align: center;
  color: white;
  width: 500px;
}
html {
  background-color: #2d545e;
}
```

- Il ne reste plus qu'à centrer et omogénéiser tout ça
- introduire les margins
- introduire les paddings

```css

body {
  background-color: #e1b382;
  text-align: center;
  color: white;
  width: 500px;
  margin-left: auto;
  margin-right: auto;
  margin-top: 100px;
  margin-bottom: 100px;
  padding: 50px;
}

```

## TP : Qui suis-je en le retour

- Laisser les apprenants profiter de leurs nouvelles connaissances en css pour améliorer leur présentation
- N'hésitez pas à vous la raconter avec des animations ou autres 
- Profiter du temps qu'il reste pour échanger avec eux 

**Penser à récuperer le retour des apprenants à la fin sur un temps d'échange, c'est très important, la trame est modulable selon la participation/le niveau du groupe**

