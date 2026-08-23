# Le Guide HTML/CSS pour Débutants

Site web *one page* présentant un guide d'introduction au HTML et au CSS, destiné à des apprenants débutants.

## À propos

Projet réalisé dans le cadre d'une évaluation individuelle HTML/CSS, durant ma formation Développeur Web et Web Mobile. La consigne : créer, pour une école en ligne fictive ("Digital Student"), un site pédagogique en HTML5/CSS3 respectant une charte graphique imposée, les bonnes pratiques de sémantique HTML, d'accessibilité et de responsive design — réalisé en autonomie, sans JavaScript.

## Structure du site

Le site est organisé en 5 sections principales :
1. **Introduction** — présentation du guide
2. **Pourquoi apprendre HTML/CSS ?** — argumentaire pédagogique
3. **Les balises de base** — tableau récapitulatif des balises essentielles avec exemples
4. **Tips & bonnes pratiques** — conseils pour un code propre et structuré
5. **Contact** — formulaire (prénom, email, message, newsletter)

## Fonctionnalités et bonnes pratiques mises en œuvre

- Structure HTML entièrement sémantique (`header`, `nav`, `main`, `section`, `article`, `footer`)
- Un seul `<h1>` par page, hiérarchie de titres respectée
- Formulaire de contact structuré et accessible (`label for`, attributs `required`, `minlength`/`maxlength`, types d'input appropriés)
- Échappement des caractères HTML pour l'affichage de code non interprété (`<pre>`, `<code>`, `&lt;`/`&gt;`)
- Navigation au clavier avec états `:focus-visible` sur tous les éléments interactifs
- Attributs ARIA (`aria-label`, `aria-hidden`, `aria-expanded`)
- Mise en page responsive avec Flexbox et CSS Grid, deux breakpoints (tablette : 768px, mobile : 480px)
- Variables CSS (`:root`) pour centraliser la charte graphique
- Nesting CSS pour une meilleure lisibilité des sélecteurs imbriqués
- Transitions douces sur les éléments interactifs (boutons)
- Respect strict de la charte graphique imposée (couleurs, typographies : Montserrat, Nunito Sans, Open Sans)

## Stack technique

- HTML5 sémantique
- CSS3 (Flexbox, Grid, variables CSS, nesting, media queries)
- Google Fonts (Montserrat, Nunito Sans, Open Sans)

## Aperçu

**Vue desktop**

![Page d'accueil](screenshots/accueil.png)
![Tips & bonnes pratiques](screenshots/tips+formulaire+footer)

**Vue mobile**

![Accueil - mobile](screenshots/accueil-version-mobile.png)
![Tips & bonnes pratiques - mobile](screenshots/tips-bonnepratique-version-mobile.png)
![Footer - mobile](screenshots/footer-version-mobile.png)

**Formulaire de contact**

![Formulaire de contact](screenshots/formulaire-contact.png)

## Ce que j'ai appris

- Structurer une page complète avec des balises sémantiques plutôt qu'un enchaînement de `<div>`
- Construire un formulaire accessible avec labels associés et validations natives HTML
- Organiser un CSS avec des variables réellement exploitées, plutôt que déclarées pour la forme
- Importance de l'accessibilité clavier (`:focus-visible`) dans une navigation web
- Gérer le responsive design à travers plusieurs breakpoints sans dupliquer inutilement le code