# Création d'un site Web HTML5 / CSS3

## Objectif du projet

Le but de ce projet est de concevoir et développer un **site web statique** en utilisant les technologies **HTML5** et **CSS3** étudiées en cours.

Ce travail doit démontrer votre capacité à :

- structurer une page web ;
- appliquer une mise en page cohérente ;
- utiliser correctement les balises HTML5 ;
- mettre en forme un site avec CSS3 ;
- produire un code propre, organisé et valide.

---

## Consignes générales

### 1. Préparation du projet

Avant de commencer le développement, vous devez réaliser un **schéma papier** ou une **maquette** de votre site.

Ce document devra présenter :

- l'organisation des pages ;
- la disposition des éléments ;
- la navigation du site.

Cette réflexion préparatoire devra être remise avec le projet final.

---

## Structure attendue du site

Votre site devra contenir au minimum :

- une page d'accueil `index.html` ;
- un en-tête : `<header>` ;
- un menu de navigation : `<nav>` ;
- un contenu principal : `<main>` ;
- une zone secondaire éventuelle : sidebar ;
- un pied de page : `<footer>`.

---

## Contraintes techniques

### Hébergement

Le site devra être publié en ligne sur un **hébergement gratuit** ou sur un **serveur web**.

### Organisation des fichiers

Le projet devra respecter une structure claire :

```text
/mon-site
|
+-- index.html
+-- css/
|   +-- style.css
+-- images/
|   +-- ...
+-- pages/
```

---

## Exigences obligatoires

### HTML5

- Le code HTML doit respecter la norme **HTML5**.
- Les pages devront être validées via le validateur du W3C :
  <https://validator.w3.org/>

### CSS3

- Le code CSS doit respecter la norme **CSS3**.
- Les couleurs devront être codées en **hexadécimal**.

### Présentation du code

Le code devra être :

- correctement indenté ;
- lisible ;
- commenté ;
- organisé.

Les balises ouvrantes et fermantes devront être alignées correctement.

---

## Mise en page

Le site devra :

- avoir une largeur maximale de **800 px** ;
- utiliser des balises structurantes :
  - `<header>` ;
  - `<nav>` ;
  - `<main>` ;
  - `<section>` ;
  - `<footer>`.

---

## Images

Le site devra contenir au minimum :

- une image insérée avec la balise `<img>` ;
- une image utilisée comme arrière-plan CSS avec `background-image`.

Toutes les images devront être :

- personnelles ;
- libres de droits ;
- ou sous licence Creative Commons.

---

## Liens

Le site devra contenir :

- des liens internes ;
- des liens externes ;
- une personnalisation CSS des liens :
  - `a:hover` ;
  - `a:visited`.

---

## CSS et organisation

Vous devrez utiliser :

- des classes CSS ;
- des identifiants `id` pertinents ;
- des propriétés de mise en page :
  - `margin` ;
  - `padding` ;
  - `border` ;
  - `float` ou `flexbox`.

### Exemples corrects

```html
<div id="menu-principal">
<div class="image-gauche">
```

### Exemples incorrects

```html
<div id="id1">
<div class="classe1">
```

---

## Bonus possibles

Les étudiants qui souhaitent aller plus loin peuvent ajouter :

- un design responsive ;
- des animations CSS ;
- un formulaire ;
- une galerie d'images ;
- un menu dynamique ;
- des effets visuels.

---

## Remise du projet

Le projet devra être remis sous forme :

- d'un dossier compressé `.zip` contenant tous les fichiers du site ;
- de l'adresse du site publié en ligne.

---

## Grille d'évaluation

| Critère | Points |
|---|---:|
| Structure correcte du site : `header`, `nav`, `footer`, etc. | /2 |
| Respect des normes HTML5 | /2 |
| Respect des normes CSS3 | /2 |
| Organisation des fichiers et dossiers | /1 |
| Qualité et propreté du code | /2 |
| Mise en page et design | /3 |
| Utilisation correcte des balises HTML | /2 |
| Utilisation pertinente du CSS | /2 |
| Images et intégration graphique | /1 |
| Navigation et liens | /1 |
| Validation W3C | /1 |
| Hébergement du site en ligne | /1 |
| Originalité et créativité | /2 |
| **Total** | **/20** |

---

## Critères de pénalité

Des points pourront être retirés en cas de :

- code non indenté ;
- liens cassés ;
- images manquantes ;
- absence de validation ;
- non-respect des consignes ;
- travail incomplet ;
- copie d'un site existant.
