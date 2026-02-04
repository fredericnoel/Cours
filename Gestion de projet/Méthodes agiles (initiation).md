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
# Rôles et artefacts SCRUM
Cette partie s’intéresse à qui fait quoi dans SCRUM et avec quels supports concrets.
Sur le terrain, la majorité des échecs SCRUM ne viennent pas des outils, mais :
- d’une mauvaise compréhension des rôles ;
- de responsabilités floues ;
- d’artefacts mal utilisés ou détournés de leur objectif initial.
Pour un développeur web, comprendre ces éléments est essentiel afin de :
- savoir ce qui relève de sa responsabilité ;
- éviter les conflits inutiles ;
- adopter une posture professionnelle attendue en entreprise.
## Les rôles SCRUM : une organisation volontairement simple
SCRUM définit trois rôles, et uniquement trois. Cette simplicité est volontaire. Ajouter des rôles intermédiaires ou hybrides est une dérive fréquente qui complique inutilement le fonctionnement de l’équipe.
Les rôles SCRUM sont :
- le *Product Owner* ;
- le *Scrum Master* ;
- l’équipe de développement.
Chaque rôle a un périmètre clair. Lorsqu’un rôle empiète sur un autre, des tensions apparaissent rapidement.
## Le *Product Owner* : responsable de la valeur, pas de la technique
Le *Product Owner (PO)* est responsable de la valeur du produit. Son rôle est de décider quoi développer et dans quel ordre, en fonction des besoins des utilisateurs et des enjeux métier.
### Ce que fait réellement un Product Owner sur le terrain
Dans un projet web, le Product Owner :
- collecte les besoins des utilisateurs ou du client ;
- transforme ces besoins en éléments compréhensibles pour l’équipe ;
- priorise le travail en fonction de la valeur apportée ;
- arbitre lorsque tout ne peut pas être fait.
Le PO est propriétaire du Product Backlog. Il est responsable de son contenu, de son ordre et de sa clarté.
### Ce que le Product Owner ne fait pas
Sur le terrain, une confusion fréquente consiste à assimiler le Product Owner à :
- un chef de projet classique ;
- un manager de l’équipe ;
- un expert technique.
Le PO ne décide pas comment le travail est réalisé. Il exprime le besoin, pas la solution technique.
Pour un développeur, cela implique :
- de ne pas attendre du PO des choix techniques ;
- mais de collaborer avec lui pour comprendre la valeur attendue.
## Le *Scrum Master* : garant du cadre, facilitateur au quotidien
Le Scrum Master est souvent le rôle le plus mal compris, en particulier par les juniors.
### Le rôle réel du *Scrum Master*
Sur le terrain, le Scrum Master :
- s’assure que SCRUM est compris et appliqué ;
- facilite les échanges au sein de l’équipe ;
- aide à résoudre les obstacles organisationnels ;
- protège l’équipe des interruptions inutiles.
Il agit comme un facilitateur, pas comme un chef.
### Les dérives fréquentes
Dans certaines organisations, le Scrum Master est :
- confondu avec un manager hiérarchique ;
- utilisé comme un chef de projet déguisé ;
- chargé de faire du reporting pour la direction.
Ces dérives nuisent au fonctionnement de SCRUM et à l’autonomie de l’équipe.
Pour un développeur, comprendre le rôle du Scrum Master permet :
- de savoir à qui remonter les blocages ;
- de ne pas attendre de lui des décisions techniques ;
- de mieux utiliser son aide au quotidien.
## L’équipe de développement : responsabilité collective
L’équipe de développement regroupe toutes les personnes nécessaires à la réalisation du produit.
Dans un projet web, cela peut inclure :
- développeurs *front-end* ;
- développeurs *back-end* ;
- intégrateurs ;
- testeurs ;
- *etc.*
### Auto-organisation et responsabilité
SCRUM repose sur l’auto-organisation. Cela signifie que l’équipe décide comment le travail est réalisé.
La responsabilité est collective :
- il n’y a pas de « ma tâche » isolée du reste ;
- le sprint est réussi ou échoué collectivement.
Pour un développeur junior, c’est un point fondamental :
- la qualité du travail de chacun impacte toute l’équipe ;
- l’entraide est une nécessité, pas une option.
## Les artefacts SCRUM : rendre le travail visible
Les artefacts SCRUM servent à rendre le travail visible et compréhensible. Ils sont des supports de communication avant d’être des outils de suivi.
Les principaux artefacts sont :
- les *User Stories* ;
- le *Product Backlog* ;
- le *Sprint Backlog* ;
- la *Done Pill*.
## Les *User Stories* : penser valeur avant solution
Une *user story* exprime un besoin du point de vue utilisateur. Elle évite de raisonner uniquement en termes techniques.
Une *user story* est souvent formulée sous la forme :
	En tant que [type d’utilisateur],
	je veux [objectif],
	afin de [bénéfice].
### Bonnes pratiques sur le terrain
Sur le terrain, une bonne user story :
- est compréhensible sans explication technique ;
- apporte une valeur claire ;
- est suffisamment petite pour être réalisée dans un sprint.
## Le *Product Backlog* : mémoire vivante du produit
Le Product Backlog est la liste ordonnée de tout ce qui pourrait être développé pour le produit.
Il n’est ni figé, ni exhaustif dès le départ.
Sur le terrain :
- le *backlog* évolue en permanence ;
- les priorités changent ;
- certaines stories sont supprimées.
Le *backlog* reflète les choix du *Product Owner* à un instant donné.
## Le Sprint Backlog : engagement de l’équipe
Le Sprint Backlog contient :
- les *user stories* sélectionnées pour le sprint ;
- les tâches nécessaires pour les réaliser.
Il représente un engagement collectif de l’équipe.
Une erreur fréquente consiste à surcharger le sprint *backlog*. Sur le terrain, un sprint réussi est un sprint réaliste, pas un sprint ambitieux sur le papier.
## La *Done Pill* : visualiser l’avancement réel
La *Done Pill* est un outil visuel permettant de voir rapidement :
- ce qui est terminé ;
- ce qui est en cours ;
- ce qui reste à faire.
Son intérêt principal est la transparence. Elle évite les discours flous sur l’avancement et met en évidence les blocages.