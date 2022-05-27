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

## TP : Qui suis-je ?

- Expliquer la syntaxe (balise, balise auto fermante, indentation)
- Passer sur codeSandBox, template créer avec la structure : https://codesandbox.io/s/premiere-page-857siy?file=/index.html

**A partir d'ici on essai de les faire pratiquer un maximum, 2 ou 3 nouvelles balises qu'on montre, ils appliquent les balises, le but étant qu'ils s'amusent et de minimiser le magistral**

- On explique les balises déjà présentent dans la structure
- On introduit les balises : ``` <h1>, <p>, <a>, <img> ```
- exemple à coder devant eux, ils font leur propre version une fois les balises expliquées :

```html
<h1>Bailly Benjamin</h1>
<p>Je m'appelle Bailly Benjamin, je suis formateur dans l'organisme de formation O'clock, j'ai 28 ans, je suis marié et j'ai 2 enfants</p>
<p>
    <a href="https://stackoverflow.com/">Lien du site que je consulte le plus tout les jours</a>
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