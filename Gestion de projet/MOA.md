# MOA (maîtrise d'ouvrage, étude d'avant-projet)
Ce module a pour objectif de permettre de :
* comprendre et analyser les besoins métier et fonctionnels ;
* évaluer la faisabilité d’un projet numérique ;
* formaliser ces éléments dans un cahier des charges fonctionnel et technique ;
* participer à la définition d’une architecture technique ;
* comparer et justifier des solutions techniques adaptées au contexte.
## Analyse des besoins
### Comprendre les besoins métier et fonctionnels
L’étude d’avant-projet commence par l’analyse des besoins.\
La maîtrise d’ouvrage a pour rôle de comprendre le problème à résoudre, indépendamment des solutions techniques possibles.
Le besoin métier correspond aux objectifs de l’organisation : amélioration d’un processus, fiabilisation de l’information, optimisation d’un fonctionnement existant.\
Le besoin fonctionnel traduit ce besoin métier en capacités attendues du système numérique.
Cette distinction est essentielle pour éviter de confondre besoin et solution.
### Identifier les attentes des utilisateurs
L’analyse des besoins implique l’identification :
* des utilisateurs finaux ;
* des responsables métier ;
* des parties prenantes impliquées dans le projet.
Chaque acteur exprime des attentes différentes.\
La MOA doit les recueillir, les comprendre et les structurer, tout en identifiant les attentes implicites ou non formulées.
### Utiliser des méthodes d’analyse des besoins
Le recueil des besoins repose sur des méthodes adaptées au contexte :
* enquêtes ;
* interviews ;
* analyse documentaire ;
* observation des pratiques existantes.
Ces méthodes permettent d’obtenir une vision fiable et structurée de la situation actuelle et des attentes futures.
### Recueillir et formaliser les besoins
Les apprenants identifient et formalisent les besoins métier et fonctionnels liés à un système de gestion des ressources humaines.\
Livrable : rapport structuré d’analyse des besoins.
## Faisabilité technique
### Évaluer la compatibilité avec l’existant
Tout projet numérique s’inscrit dans un environnement existant.\
La faisabilité technique consiste à analyser la compatibilité du projet avec les systèmes déjà en place et les contraintes associées.
### Analyser les contraintes techniques
Les contraintes peuvent être :
* techniques ;
* organisationnelles ;
* liées aux ressources disponibles.
Elles doivent être identifiées et prises en compte dès l’avant-projet.
### Estimer les coûts et délais
La MOA doit être capable d’évaluer de manière globale :
* les coûts liés au projet ;
* les délais de mise en œuvre ;
* l’impact sur les ressources humaines et matérielles.
### Identifier les risques techniques
L’analyse de faisabilité inclut l’identification des risques :
* risques liés aux technologies ;
* risques d’intégration ;
* risques de sécurité ou de performance.
Ces risques doivent être documentés et anticipés.
## Cahier des charges
### Rédaction d’un cahier des charges fonctionnel
Le cahier des charges fonctionnel décrit ce que le système doit faire, sans entrer dans les détails de la solution technique.
Il comprend notamment :
* le contexte et les objectifs du projet ;
* le périmètre fonctionnel ;
* l’identification des utilisateurs et parties prenantes ;
* la description des fonctionnalités attendues ;
* les règles de gestion associées ;
* les exigences fonctionnelles liées à la sécurité et à la performance ;
* les critères de validation.
Il constitue une référence commune entre la MOA et les acteurs du projet.
### Rédaction d’un cahier des charges technique
Le cahier des charges technique formalise les contraintes et exigences techniques identifiées lors de l’étude de faisabilité.
Il précise :
* l’environnement technique existant ;
* les contraintes d’intégration ;
* les exigences de sécurité ;
* les exigences de performance ;
* les risques techniques identifiés ;
* les critères de conformité technique.
Il ne décrit pas encore l’architecture détaillée, mais cadre les exigences que la solution devra respecter.
## Spécifications techniques
Les cspécifications techniques interviennent après la rédaction du cahier des charges.\
Il ne remet pas en cause les choix fonctionnels et techniques cadrés précédemment, mais vise à décrire plus précisément la traduction technique du projet, tout en restant à un niveau compatible avec une étude d’avant-projet.
Ce chapitre permet de faire le lien entre :
* les besoins et contraintes exprimés par la MOA ;
* et la future phase de réalisation (MOE).
### Concevoir l’architecture technique
La conception de l’architecture technique consiste à proposer une organisation globale du système, cohérente avec :
* les fonctionnalités attendues (Chapitre 3) ;
* les contraintes techniques identifiées ;
* les exigences de sécurité et de performance.
À ce stade, l’objectif n’est pas de produire une architecture exhaustive, mais :
* d’identifier les grands composants du système ;
* de préciser leur rôle ;
* de montrer comment ils interagissent.
L’architecture technique doit permettre de répondre aux questions suivantes :
* comment le système est-il structuré ?
* quels sont les grands blocs fonctionnels et techniques ?
* Commentc les données circulent-elles ?
La MOA veille à ce que l’architecture proposée soit :
* compréhensible ;
* réaliste ;
* compatible avec l’existant.
### Décrire les interfaces avec les autres systèmes
Un projet numérique s’intègre rarement de manière isolée.\
Cette section vise à identifier et décrire les interfaces nécessaires avec les systèmes existants.
Il s’agit notamment de préciser :
* quels systèmes échangent des données avec la solution ;
* la nature des échanges (données entrantes, sortantes) ;
* les dépendances fonctionnelles et techniques.
Cette description permet :
* d’anticiper les contraintes d’intégration ;
* d’identifier les risques associés ;
* de sécuriser la cohérence globale du système d’information.
La MOA s’assure que les interfaces sont :
* clairement identifiées ;
* cohérentes avec les besoins fonctionnels ;
* compatibles avec les contraintes techniques recensées.
### Définir les normes et standards à respecter
Cette partie consiste à formaliser les normes et standards applicables au projet, en lien avec l’organisation et l’environnement technique.
Les normes et standards permettent de :
* garantir la qualité du système ;
* faciliter la maintenance et l’évolution ;
* assurer la cohérence avec le reste du SI.
La MOA précise ici :
* les standards techniques à respecter ;
* les conventions applicables ;
* les exigences liées aux bonnes pratiques en vigueur dans l’organisation.
Ce cadrage évite les choix arbitraires lors de la réalisation.
### Préciser les choix technologiques
Sur la base de l’architecture, des interfaces et des normes définies, cette section permet de formaliser les choix technologiques retenus.
Les choix technologiques doivent être :
* cohérents avec les besoins fonctionnels ;
* compatibles avec les contraintes techniques ;
* justifiés par rapport aux exigences de sécurité et de performance.
La MOA ne cherche pas à imposer une implémentation détaillée, mais à :
* cadrer les orientations techniques ;
* justifier leur pertinence ;
* assurer leur faisabilité.
## Études comparatives
Ce chapitre vise à amener à évaluer plusieurs solutions techniques possibles, avant de retenir celle qui répond le mieux aux besoins et contraintes du projet.
Il s’inscrit pleinement dans la logique MOA :
* analyser ;
* comparer ;
* décider ;
* justifier.
### Comparer les solutions techniques possibles
Cette section consiste à identifier plusieurs solutions techniques envisageables pour répondre au cahier des charges.
Chaque solution doit être analysée selon des critères communs, issus :
* des besoins fonctionnels ;
* des contraintes techniques ;
* des exigences de sécurité et de performance.
L’objectif est de poser un cadre de comparaison clair et structuré.
### Évaluer les avantages et inconvénients de chaque solution
Pour chaque solution étudiée, les analyser :
* les points forts ;
* les limites ;
* les impacts techniques et organisationnels.
Cette analyse doit rester factuelle et argumentée, en lien direct avec :
* la faisabilité ;
* les risques identifiés ;
* la compatibilité avec l’existant.
### Choisir la solution la plus adaptée aux besoins
Le choix de la solution ne repose pas uniquement sur des critères techniques, mais sur :
* l’adéquation globale avec les objectifs du projet ;
* la prise en compte des contraintes ;
* la capacité à répondre aux besoins identifiés.
Cette étape permet de montrer que le rôle de la MOA est aussi d’arbitrer.
### Justifier le choix technique retenu
La justification du choix est un élément central du livrable final.
Elle doit :
* expliquer pourquoi une solution a été retenue ;
* montrer en quoi elle répond mieux que les autres aux besoins et contraintes ;
* démontrer la cohérence du raisonnement suivi.
Cette justification permet de sécuriser la décision et de la rendre compréhensible pour l’ensemble des parties prenantes.