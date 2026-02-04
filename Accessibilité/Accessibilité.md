#Accessibilité #Handicap 
# Accessibilité

- Fondamentaux, cadre légal, design inclusif et structure
- Médias, formulaires, composants dynamiques & audits

## Introduction : pourquoi l’accessibilité ?

### Comprendre l’importance sociale et humaine

L’accessibilité web n’est pas une option, c’est une nécessité sociétale. Les principaux publics concernés sont les suivants.

#### Personnes avec déficiences visuelles

- cécité → lecteurs d’écran ([NVDA](https://www.nvda.fr/), [JAWS](https://support.freedomscientific.com/JAWSHQ/JAWSHeadquarters01), [VoiceOver](https://www.apple.com/fr/accessibility/features/?vision))
- malvoyance (zoom, contraste fort)
- daltonisme (difficultés à distinguer certaines couleurs).
  Environ 1 français sur 12 est daltonien (la déficience touche majoritairement des hommes).

#### Personnes avec déficiences motrices

- usage limité de la souris (tremblements, paralysie, immobilité)
- navigation exclusivement clavier
- importance des zones interactives larges et bien espacées.

#### Déficiences cognitives

- dyslexie
- mémoire courte, compréhension difficile
- interface claire et simplifiée
- choix des polices et tailles adaptées.

#### Déficiences auditives

- vidéos sans sous-titres (perte d’accès total)
- besoin de transcription textuelle.

### Enjeux professionnels

- les communicants doivent garantir que l’information soit accessible
- les designers et intégrateurs produisent les supports
- les entreprises y gagnent en image, SEO, simplicité d’usage.

**Impacts positifs mesurés**

- +20 % de trafic organique lors de la correction des alt + titres + structure
- baisse du taux de rebond grâce à la lisibilité
- meilleure conversion sur mobile grâce à des éléments clairs et accessibles.

### Exemples réels de problèmes d’accessibilité

- bouton « Envoyer » qui disparaît au focus (utilisateur bloqué)
- placeholder utilisé comme label (champs incompréhensibles)
- menu burger impossible à ouvrir au clavier
- vidéo publicitaire sans sous-titres (message inaccessible).

### À retenir

- l'accessibilité n'est pas pour une « minorité » mais pour toutes et tous
- une interface plus accessible est toujours plus intuitive
- les obligations légales ne concernent pas que les sites publics (influence de tous les secteurs).

## Références officielles : WCAG et RGAA

### Les WCAG en profondeur

Documentation officielle : [https://www.w3.org/TR/WCAG/](https://www.w3.org/TR/WCAG/)

4 principes.

#### *Perceivable*

L’information doit être présentée de façon à pouvoir être perçue par tous :

- texte alternatif pour images
- sous-titres pour vidéos
- structure correcte
- contrastes suffisants.

#### *Operable*

L'utilisateur doit pouvoir agir avec les interfaces :

- navigation au clavier
- éviter les contenus qui nécessitent un temps de réaction rapide
- focus visible
- éviter les pièges (modales non fermables, carrousels automatiques).

#### *Understandable*

Le contenu doit être compréhensible :

- langage simple
- formulaires avec messages d’erreur utiles
- cohérence dans les comportements (un bouton ressemble à un bouton).

#### *Robust*

Compatible avec différentes aides techniques :

- code propre
- [ARIA](https://developer.mozilla.org/fr/docs/Web/Accessibility/ARIA) conforme
- HTML sémantique
- éviter les éléments exotiques ou mal supportés.

### RGAA : l’outil français officiel

Site officiel : [https://accessibilite.numerique.gouv.fr/methode/](https://accessibilite.numerique.gouv.fr/methode/)

Structure RGAA :

- 13 thématiques (images, liens, formulaires, scripts, *etc.*)
- 106 critères + tests associés
- Exigence : AA
- Obligatoire pour les sites publics.

Exemples de thématiques RGAA :

- images
- cadres
- couleurs
- multimédia
- tableaux
- liens
- scripts
- éléments obligatoires
- structuration
- présentation de l’information
- formulaires
- navigation
- consultation.

Tests RGAA :
Chaque critère se teste avec des conditions précises (Exemple,critère 1.1 sur les images → 10 tests successifs).

## Obligations légales

### Contrastes

Contraste minimum : Un ratio de 4.5:1 est requis pour le texte standard.

Cas particuliers :

- boutons avec icône uniquement (icône doit être suffisamment contrastée)
- liens intégrés dans du texte (doivent être facilement identifiables)
- texte sur image (éviter, sinon prévoir overlay sombre ou clair).

Outils supplémentaires :

- [Accessible Colors](https://accessible-colors.com)
- [WhoCanUse (impact couleurs/défauts visuels)](https://www.whocanuse.com/).

### Typographie

Bonnes pratiques :

- Police avec formes distinctes (éviter des polices trop fines)
- Éviter les interlettrages trop serrés
- Taille minimale 16 px sur web.

Pour la dyslexie :

- Arial
- Verdana
- Helvetica
- OpenDyslexic (dans certains cas).

### Couleurs

Règle d’or : ne jamais transmettre une information uniquement par la couleur.

Exemples incorrects :

- « champs obligatoires » en rouge
- « résultats positifs » en vert.

Correct :

- icône + couleur
- texte explicite (« obligatoire »).

### Mise en page inclusive

- alignement à gauche
- longueur de ligne (60–80 caractères)
- éviter les murs de texte (listes, sous-titres, encadrés)
- prévoir suffisamment d’espace entre éléments.

## Navigation : clavier + focus

### Navigation au clavier

Tous les éléments doivent être accessibles via :

- tab → suivant
- shift + Tab → précédent
- enter / Space → activer
- flèches → menus, sliders, onglets.

Pièges fréquents :

- menus avec sous-niveaux non accessibles
- carrousels qui avancent automatiquement
- modales qui laissent le fond actif
- éléments *custom* sans capture clavier.

### Focus visible

Un bon focus doit être :

- visible
- contrasté
- constant
- non masqué par des effets CSS.

Exemples de focus problématiques, la suppression du focus outline :

```
    *:focus { outline: none; }
```

## HTML sémantique

### Pourquoi le HTML sémantique est central pour l’accessibilité

Le HTML sémantique consiste à utiliser des balises qui décrivent le rôle et la structure du contenu (par exemple ```<main>```, ```<nav>```, ```<article>```, ```<section>```, ```<header>```, ```<footer>```, ```<aside>```, ```<figure>```, ```<figcaption>```, ```<time>```, *etc.*).

Cela permet :

- aux technologies d’assistance (lecteurs d’écran, logiciels de commande vocale) de comprendre la structure logique de la page ;
- aux utilisateurs de naviguer par zones (contenu principal, navigation, recherche, etc.) ;
- de respecter plus facilement les critères WCAG/RGAA liés à la structuration de l’information (titres, zones, ordre de lecture).

### Structurer une page avec les éléments sémantiques

Quelques éléments sémantiques clés :

- ```<header>```, en-tête de la page ou d’une section (logo, titre, navigation secondaire)
- ```<nav>```, bloc de navigation principale ou secondaire (menus, sommaires)
- ```<main>```, contenu principal de la page, unique, hors en-tête, navigation, pied de page
- ```<article>```, contenu autonome (article de blog, fiche produit, actualité)
- ```<section>```, regroupement thématique au sein d’une page (chapitre, section logique)
- ```<aside>```, contenu connexe (encadré, bloc “À lire aussi”, pub, sidebar)
- ```<footer>```, pied de page (mentions légales, liens secondaires, contact)
- ```<figure>``` + ```<figcaption>``` (image + légende associée).

### Landmarks HTML & rôles WAI-ARIA

Les **landmarks** (rôles de repérage) permettent aux utilisateurs de lecteurs d’écran de naviguer rapidement vers les zones importantes de la page (en-tête, navigation, recherche, contenu principal, pied de page, *etc.*).
On peut définir des landmarks de deux façons :

- en utilisant les éléments HTML sémantiques (```<header>```, ```<nav>```, ```<main>```, ```<aside>```, ```<footer>```, *etc.*) ;
- en utilisant les rôles WAI-ARIA (par exemple ```role="banner"```, ```role="navigation"```, ```role="main"```, ```role="contentinfo"```, ```role="search"```, ```role="complementary"```, *etc.*).

Les recommandations du W3C pour les landmarks précisent notamment que :

- banner, main, contentinfo, complementary doivent être des landmarks de premier niveau (non imbriqués dans d’autres landmarks structurants) ;
- il faut attribuer les landmarks selon la nature du contenu (ne pas mettre ```role="main"``` sur une simple *sidebar*) ;
- il faut éviter la surabondance de *landmarks*, car trop de rôles créent du bruit dans les lecteurs d’écran.

Exemple : combinaison HTML + ARIA pour les landmarks

```
<body>
    <header role="banner">
        <!-- En-tête du site -->
    </header>
    <nav role="navigation" aria-label="Navigation principale">
        <!-- Menu principal -->
    </nav>
    <main role="main">
        <!-- Contenu principal unique de la page -->
    </main>
    <aside role="complementary" aria-label="Informations complémentaires">
        <!-- Contenu connexe -->
    </aside>
    <footer role="contentinfo">
        <!-- Mentions légales, infos de contact -->
    </footer>
</body>
```

### ARIA : principes d’usage et « First Rule of ARIA »

Le W3C, dans son document « Using ARIA in HTML », énonce la règle de base suivante, connue comme la « First Rule of ARIA » :

> Si vous pouvez utiliser un élément HTML natif ou un attribut avec les sémantiques et comportements nécessaires, faites-le plutôt que de ré-utiliser un élément quelconque en lui ajoutant un rôle, un état ou une propriété ARIA.

Des ressources comme Deque et plusieurs guides d’accessibilité reprennent cette règle : ne pas utiliser ARIA si le HTML natif suffit, puis compléter seulement quand ce n’est pas possible (composants très personnalisés, widgets riches,*etc.*).

À retenir :

- Toujours privilégier du HTML sémantique propre (titres, sections, main/nav/header/footer, listes, boutons, liens)
- Utiliser ARIA en complément, lorsque
  - il n’existe pas d’élément HTML natif adapté (ex. composants « custom » complexes) ;
  - on doit exposer à l’assistance un état (```aria-expanded```, ```aria-pressed```, ```aria-hidden```, *etc.*) ou une relation (```aria-controls```, ```aria-labelledby```, ```aria-describedby```)
- Éviter les abus
  - ne pas surcharger une page de rôles ARIA
  - ne pas mettre ```aria-hidden="true"``` sur des éléments focusables
  - ne pas masquer visuellement un élément censé fournir un libellé aux technologies d’assistance (labels, titres, *etc.*).

### ARIA et structuration des titres (cas particuliers)

Les notes techniques RGAA indiquent que ARIA peut, à titre exceptionnel, être utilisée pour définir des titres via le rôle ```role="heading"``` combiné à ```aria-level```, notamment dans des cas d’interfaces très spécifiques :

> ```<div role="heading" aria-level="2">Titre de section</div>```

Mais le RGAA rappelle qu’il est préférable d’utiliser les éléments de titre natifs (```<h1>```…```<h6>```) dès que possible, car ils sont mieux supportés et plus simples à maintenir.

## Médias

### Images

Types d'images et valeur des attributs ```alt``` à renseigner :

| **Type d'image**    | **Alt**                               | **Exemple**                         |
| ------------------- | ------------------------------------- | ----------------------------------- |
| Décorative          | ```alt=""```                          | Icône de puce de liste              |
| Image informative   | Description                           | Graphique, photo d'un produit       |
| Image fonctionnelle | Action                                | icône “rechercher” → « rechercher » |
| Diagramme           | Description + lien vers version texte | Schéma complexe                     |

### Vidéos

Obligatoire :

- sous-titres synchronisés
- transcription complète
- sous-titres non automatiques ou corrigés manuellement.

Recommandé :

- audio-description pour éléments visuels importants.

Outils :

- [Amara](https://amara.org)
- [YouTube Studio](https://studio.youtube.com/).

### Formulaires

Chaque champ doit être associé à un label visible.

Mauvaise pratique :

> ```<input placeholder="Email">```

Bonne pratique :

```
<label for="email">Adresse email</label>
<input id="email">
```

### Messages d'erreur

Critères :

- explicites
- lisibles
- compréhensibles
- sans jargon technique.

## Composants dynamiques

### Modales

Fonctionnement correct :

- focus piégé dans la modale
- fermeture via Échap
- ```aria-modal="true"```
- ```role="dialog"```.

### Onglets

Navigation attendue :

- flèches pour passer d’un onglet à l’autre
- tab pour entrer dans le contenu
- ```aria-selected``` sur onglet actif.

### Menus

Exigences :

- ```aria-expanded```
- ```aria-haspopup```
- focus sur premier élément lors de l’ouverture.

## Tests rapides & outils

### Tests automatiques

- [Lighthouse](https://github.com/GoogleChrome/lighthouse) (Score « Accessibility »)
- [axe DevTools](https://www.deque.com/axe/devtools/)
- [WAVE](https://wave.webaim.org/)
- Deque WorldSpace Attest
- Siteimprove Accessibility Checker

### Tests manuels essentiels

Liste de tests à réaliser systématiquement :

- navigation complète au clavier
- vérifier les titres → extension HeadingsMap (Firefox, Chrome)
- vérifier contrastes
- vérifier structure du DOM
- érifier focus
- lire la page avec NVDA
- désactiver CSS pour vérifier la structure (Test structure brut).

## Audit RGAA simplifié

### Étapes détaillées

- préparation (identifier pages représentatives)
- analyse initiale (outils automatiques)
- vérification manuelle des critères clés
- notation “Conforme / Non Conforme / Non Applicable”
- priorisation (impact utilisateur / difficulté technique)
- rédaction du rapport
- proposition plan d’action.

### Critères prioritaires

- images (absence d'attributs ```alt```)
- contrastes (texte gris clair ou jaune sur fond blanc)
- navigation clavier (menu burger inaccessible)
- formulaires (labels manquants)
- titres (plusieurs H1, ou pas de H1 du tout).

## Suivi : plan d’action et gouvernance

### *Quick wins*

- texte alternatif systématique
- vérification de la hiérarchisation des titres
- contraste correcte / *dark mode*
- sous-titrage des vidéos prioritaires.

### Plan d’action durable

- audit annuel complet
- formation des équipes
- *Design System* avec composants accessibles
- tests via NVDA à chaque phase majeure.

## Gouvernance interne

- nommer un responsable accessibilité
- référencer les composants accessibles
- compléter le schéma pluriannuel.