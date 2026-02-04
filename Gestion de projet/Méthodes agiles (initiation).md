#Agile #SCRUM #Projet
# Introduction générale
Dans le développement web moderne, les projets se déroulent rarement comme prévu.
Les besoins évoluent, les priorités changent, les contraintes techniques apparaissent en cours de route, et les utilisateurs découvrent souvent ce qu’ils veulent… une fois qu’ils voient quelque chose fonctionner. Pendant longtemps, les projets informatiques ont été gérés avec des méthodes dites « classiques », fondées sur une planification exhaustive en début de projet. On essayait de tout prévoir à l’avance : fonctionnalités, délais, budget, architecture. Cette approche peut fonctionner dans des contextes très stables, mais elle montre rapidement ses limites dans les projets web, où l’incertitude est permanente.
SCRUM est né de ce constat. Il ne s’agit pas d’une méthode miracle, ni d’une recette magique garantissant le succès d’un projet. SCRUM est un cadre de travail conçu pour aider les équipes à avancer malgré l’incertitude, à livrer régulièrement de la valeur, et à s’adapter en continu.
Dans ce cours, SCRUM n’est pas présenté comme un idéal théorique, mais comme un outil utilisé au quotidien par des équipes de développement. L’objectif n’est pas de former des experts certifiés SCRUM, mais de permettre à un futur développeur web de :
-  comprendre comment fonctionnent réellement les projets agiles ;
- savoir quelle est sa place dans une équipe SCRUM ;
- éviter les erreurs classiques observées chez les juniors ;
- être opérationnel dans un contexte professionnel.
# Fondamentaux de SCRUM
## Pourquoi SCRUM
La méthode SCRUM existe parce que les projets web sont complexes et imprévisibles. Dans un projet typique, il est très fréquent que :
- le client change d’avis après avoir vu une première version ou au cours du projet ;
- certaines fonctionnalités initialement prévues se révèlent inutiles ou d'autres n'ont pas été prévues ;
- des contraintes techniques apparaissent tardivement (techniques, réglementaires) ;
- des délais se resserrent en cours de route (concurrence en avance, pression des financeurs).
Les méthodes classiques supposent que le besoin est parfaitement connu dès le départ. En pratique, ce n’est presque jamais le cas. Résultat : retards, tensions, livraisons décevantes, dette technique accumulée dans l’urgence.
SCRUM propose une autre logique : plutôt que de chercher à tout prévoir, on accepte l’incertitude et on avance par petites étapes contrôlées.
Chaque étape permet de :
- de produire quelque chose de concret ;
- d’obtenir du *feedback* ;
- d’ajuster la suite du travail.
Sur le terrain, SCRUM permet surtout d’éviter l’« effet tunnel ».
## Les valeurs SCRUM : comportements observables
SCRUM repose sur cinq valeurs.
### L'engagement
L’engagement signifie que l’équipe s’engage collectivement sur un objectif réaliste.
Il ne s’agit pas de promettre l’impossible pour faire plaisir, mais d’assumer ce qui est faisable dans un sprint donné.
Sur le terrain, l’absence d’engagement se traduit souvent par :
- des sprints systématiquement non terminés ;
- des excuses permanentes ;
- une perte de crédibilité de l’équipe.
### Le courage
Le courage consiste à dire la vérité sur l’avancement réel du travail. Dire qu’une tâche n’est pas terminée est un acte professionnel, pas un échec. Dans beaucoup d’équipes, le manque de courage conduit à masquer les problèmes jusqu’à ce qu’il soit trop tard pour réagir.
### Le focus
Le focus signifie que l’équipe se concentre sur ce qui a été décidé pour le sprint.
Ajouter du travail en cours de sprint est une dérive fréquente qui détruit la qualité et la motivation.
### L'ouverture
L’ouverture implique d’accepter le feedback, même lorsqu’il est inconfortable. Sur le terrain, cela concerne autant le produit que la manière de travailler.
### Le respect
Le respect est la condition de base du travail en équipe. Sans respect, il n’y a ni collaboration, ni amélioration continue possible.
## Vue d’ensemble de la méthodologie SCRUM
SCRUM fonctionne par cycles courts, appelés **sprints**. Chaque sprint a une durée fixe et produit un incrément, c’est-à-dire une version fonctionnelle du produit.
À la fin de chaque sprint :
- le travail est présenté ;
- le *feedback* est recueilli ;
- l’organisation de l’équipe est améliorée.
Ce fonctionnement permet :
- de réduire les risques ;
- de détecter les problèmes plus tôt ;
- de livrer régulièrement de la valeur.
SCRUM ne supprime pas les difficultés, mais il permet de les rendre visibles et traitables.
## Vocabulaire SCRUM essentiel
### Sprint
Un sprint est une période de travail à durée fixe.
Sur le terrain, la durée est souvent de une à deux semaines. Le sprint impose un cadre : on travaille avec ce qui a été décidé, sans remettre en cause l’objectif en permanence.
### Backlog
Le backlog est une liste priorisée de ce qui reste à faire. Il évolue en permanence et reflète les priorités du produit à un instant donné.
### User Story
Une user story décrit un besoin du point de vue utilisateur. Elle permet de rester centré sur la valeur plutôt que sur la solution technique.
### Incrément
L’incrément est le résultat concret du sprint. Il doit être utilisable, même s’il est partiel.
### La vélocité
La vélocité représente la quantité de travail réellement terminée par une équipe durant un sprint.
Sur le terrain chaque équipe a sa propre vélocité. Elle évolue avec le temps et l'expérience. Elle sert uniquement à aider l'équipe à mieux planifier.
L’utiliser pour comparer des équipes ou évaluer des individus est une erreur fréquente et contre-productive.
### La dette technique
La dette technique apparaît lorsqu’une solution rapide est privilégiée au détriment d’une solution « propre ».
Exemples courants :
- duplication de code ;
- absence de tests automatisés ;
- nommage approximatif ;
- correctifs rapides non refactorés.
À court terme, la dette technique permet d’aller plus vite.
À long terme, elle ralentit fortement le projet et augmente les risques.
### *Definition of Done (DoD)* 
La *Definition of Done (DoD)* définit précisément quand un travail est considéré comme terminé.
Dans SCRUM, une tâche « presque finie » n’existe pas. Soit elle respecte la DoD, soit elle n’est pas terminée.
Une DoD typique dans un projet web peut inclure :
- code fonctionnel ;
- tests passés ;
- intégration effectuée ;
- documentation minimale rédigée.
La DoD est commune à toute l’équipe et évite les malentendus.
### Les critères d’acceptance
Les critères d’acceptance définissent les conditions de validation d’une *user story*. Ils sont écrits avant le développement et servent de référence objective. Sans critères clairs, les discussions de validation deviennent subjectives et conflictuelles.
### Burndown chart
Le burndown chart représente l’avancement du travail au cours du sprint.
Sur le terrain, il sert à :
- détecter une dérive tôt ;
- adapter l’organisation ;
- éviter les mauvaises surprises en fin de sprint.
Ce n’est ni un outil de contrôle individuel, ni un outil de sanction.
