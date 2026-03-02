# Portfolio Web – Houda El jirari

## Présentation

Ce projet consiste en la conception et le développement d’un portfolio web personnel réalisé en **HTML5** et **CSS3**, dans le cadre du module *Technologies Web et Web Sémantique*.

Ce portfolio met en avant mon parcours académique ainsi que mes compétences en :

- Intelligence Artificielle  
- Réseaux & Infrastructure  
- Cybersécurité  

L’objectif principal est de concevoir un site web structuré, moderne et responsive en appliquant les bonnes pratiques du développement front-end.

---

## Objectifs du projet

- Utiliser une structure sémantique HTML5
- Mettre en place une mise en page moderne avec CSS Grid et Flexbox
- Appliquer une palette de couleurs cohérente
- Concevoir un site responsive adapté aux écrans mobiles
- Organiser un code propre, clair et maintenable
- Utiliser Git & GitHub pour la gestion de version

---

## Structure du projet

```
portfolio/
├── index.html
└── style.css
```

### index.html

Contient les sections suivantes :

- Header (Hero)
- Barre de navigation
- Section À propos
- Section Projets académiques
- Section Compétences techniques détaillées
- Section Outils utilisés
- Section Contact
- Footer

Les balises sémantiques HTML5 utilisées :

- `<header>`
- `<nav>`
- `<section>`
- `<article>`
- `<footer>`

---

## Design & Choix techniques

Le design est orienté **Tech / Intelligence Artificielle moderne**, avec :

- Une palette de couleurs définie via `:root` (variables CSS)
- Un dégradé moderne dans la section Hero
- Des cartes interactives avec effets hover
- Des badges stylisés pour représenter les compétences techniques
- Une typographie professionnelle et lisible

Les couleurs sont centralisées via des variables CSS afin de faciliter la maintenance et la modification du thème.

---

## Mise en page

### CSS Grid

Utilisé pour organiser :

- Les cartes des projets
- Les cartes des outils

Permet une mise en page flexible et adaptative.

### Flexbox

Utilisé pour :

- L’alignement de la barre de navigation
- L’organisation des badges de compétences

---

## Responsive Design

Le site est entièrement responsive grâce à :

- `grid-template-columns: repeat(auto-fit, minmax(...))`
- Une media query pour les écrans inférieurs à 768px

Exemple :

```css
@media (max-width: 768px) {
    nav ul {
        flex-direction: column;
    }
}
