# Gestion de projet
## Introduction générale
La gestion de projet est une compétence essentielle dans tous les métiers du numérique.
Qu’il s’agisse de créer un site web, de développer une application mobile, de concevoir une API, d’intégrer un nouvel outil métier ou de moderniser un système d’information existant, chaque initiative technique nécessite une méthode, des outils et une organisation claire.

Contrairement à une tâche quotidienne ou à un travail récurrent, un projet est une démarche unique, limitée dans le temps et orientée vers un objectif précis.
Dans les entreprises, les projets informatiques représentent souvent des investissements importants, tant en temps qu’en ressources, et leur réussite dépend autant de la technique que de l’organisation.

Ce cours a pour objectif de donner aux étudiants les bases fondamentales de la gestion de projet dans un contexte numérique et informatique. Il s’appuie sur les principes classiques du management de projet, sur les spécificités des projets SI, et sur l’utilisation concrète d’outils modernes de gestion comme Trello, Asana ou Jira.
L’objectif est qu’à la fin de cette journée, vous soyez capables de comprendre la structure d’un projet, de participer à son organisation, de suivre son avancement et de dialoguer efficacement avec une équipe projet.
## Comprendre ce qu'est un projet
Un projet est une démarche temporaire qui vise à produire un résultat précis.
Il présente trois caractéristiques essentielles :
- un objectif clair, défini dès le départ ;
- une temporalité limitée, avec une date de début et une date de fin ;
- des contraintes, notamment en termes de budget, de ressources, de qualité et de technologies.

Dans le domaine informatique, ces contraintes sont souvent renforcées par des exigences supplémentaires : sécurité, performance, compatibilité, héritage technique, interactions avec d’autres systèmes, ou encore respect de réglementations comme le RGPD.

Un projet se distingue d’une activité continue.
Une activité continue, comme la maintenance d’un serveur ou l’administration quotidienne d’un site, n’a pas de fin définie.
Un projet, lui, se termine lorsque l’objectif est atteint : par exemple livrer une nouvelle application, mettre en ligne un intranet ou mettre en production une API.
### Les particularités des projets SI
Les projets liés aux systèmes d’information (SI) sont parmi les plus complexes, car ils impliquent :
- plusieurs équipes ;
- des environnements techniques divers ;
- des contraintes fortes en matière de sécurité et de performance ;
- des impacts importants sur les utilisateurs.

Le management de projet SI, tel qu’enseigné dans les modules dédiés (ex. 4MI), repose sur des principes fondamentaux :
- comprendre le besoin métier ;
- maîtriser les contraintes techniques ;
- définir un périmètre fonctionnel clair ;
- anticiper les risques ;
- planifier les ressources ;
- et intégrer le projet dans l’environnement global de l’entreprise.
Ces éléments forment la base incontournable de tout projet informatique sérieux.
## Le cycle de vie d’un projet numérique
Pour structurer un projet, on le découpe en phases successives.
Ce cycle de vie se retrouve dans toutes les méthodologies : Waterfall, Cycle en V, Agile… seule la manière de passer d’une phase à l’autre change.
### La phase de cadrage
La phase de cadrage est la plus importante. Elle permet de poser les fondations du projet.
Elle comprend :
- l’analyse du besoin (que veut-on accomplir et pourquoi ?)
- l’identification des utilisateurs (qui va utiliser l’outil ?)
- la définition du périmètre (ce qui fait partie du projet et ce qui n’en fait pas partie) ;
- les contraintes (sécurité, RGPD, délais, technologie imposée, budget, _etc._)
- l’analyse des risques (risques techniques, organisationnels, qualité, dépendances externes).
- une première estimation des charges (travail nécessaire) et du planning.
Le livrable principal de cette phase est une note de cadrage, parfois accompagnée d’une expression de besoin.
### La conception
Une fois le cadrage validé, on entre dans la conception. Cette phase est souvent divisée en deux catégories.
#### Conception fonctionnelle
Elle définit ce que l’application doit faire du point de vue des utilisateurs :
- parcours utilisateurs ;
- règles métier ;
- prototypes ou maquettes (souvent réalisés avec Figma) ;
- cas d’usage ;
- gestion des erreurs ;
- contraintes ergonomiques.
C’est un travail souvent réalisé conjointement avec un Product Owner et un UX/UI designer.
#### Conception technique
Elle décrit comment l’application va être construite :
- logique d’architecture logicielle ;
- base de données et schémas ;
- API à consommer ou exposer ;
- règles de sécurité à respecter ;
- exigences de performance ;
- technologies choisies (_framework_, langage, serveur, _etc._) ;
- intégration au SI existant.
### La réalisation
Cette phase correspond au développement. Elle inclut :
- le travail de développement (front-end, back-end, fullstack, mobile selon le projet) ;
- l’intégration continue (CI) ;
- les tests unitaires ;
- les tests d’intégration ;
- la documentation technique ;
- la gestion du versioning (Git).
La réalisation mobilise principalement les développeurs, les testeurs (QA) et parfois les DevOps.
Les règles de qualité (revues de code, tests automatisés, conventions de code) jouent un rôle essentiel.
### Le déploiement
Une fois l’application développée, elle doit être préparée pour l’usage réel.
Le déploiement comprend :
- la recette fonctionnelle par les utilisateurs ;
- la correction des anomalies ;
- la préparation des environnements (pré-production puis production) ;
- le plan de déploiement ;
- la communication auprès des utilisateurs ;
- la formation si nécessaire.
Dans les projets SI, on utilise souvent des outils DevOps pour automatiser les déploiements (CI/CD).
### La maintenance
Une fois l’application en production, le projet n’est pas terminé. Il entre en phase de maintenance :
- maintenance corrective (correction des bugs) ;
- maintenance préventive (mise à jour des dépendances) ;
- maintenance évolutive (ajout de nouvelles fonctionnalités).
La maintenance représente souvent une grande partie du coût total du projet.
## Les outils de gestion de projet
Les outils numériques facilitent la planification, l’organisation et le suivi.
## Trello, le Kanban simple
Trello fonctionne avec des tableaux organisés en colonnes : « À faire », « En cours », « En test », « Fait ». Chaque tâche est une carte qui peut être déplacée d’une colonne à l’autre.
Trello permet d’ajouter :
- des étiquettes ;
- des checklists ;
- des deadlines ;
- des pièces jointes ;
- des membres assignés.
C’est un outil visuel, simple et très utilisé dans les projets étudiants et petites équipes.
### Asana, gestion plus structurée
Asana propose davantage de fonctionnalités :
- dépendances entre tâches ;
- sous-tâches ;
- vue calendrier ;
- vue timeline ;
- niveaux de priorité.
Il est très utilisé dans les équipes orientées organisation et planification.
### Jira, la référence des projets SI
Jira est l’outil le plus utilisé dans les entreprises travaillant en Agile, notamment avec Scrum ou Kanban.
Il permet de :
- gérer les user stories ;
- organiser les sprints ;
- suivre les anomalies ;
- visualiser un *burndown* chart ;
- gérer un *backlog* de produit.
Son intégration avec Confluence, Bitbucket ou GitLab en fait un outil incontournable.
### MS Project, gestion classique
Utilisé dans les projets en cycle en V ou en Waterfall, MS Project permet :
- de construire des diagrammes de Gantt avancés ;
- de gérer des dépendances complexes ;
- d’affecter des ressources à des tâches ;
- de calculer la charge réelle.
Cet outil est fréquent dans les grandes organisations.
## Objectifs et livrables d’un projet
### Formuler un objectif SMART
Un objectif SMART est :
- **S**pécifique ;
- **M**esurable ;
- **A**tteignable ;
- **R**éaliste ;
- **T**emporel.
### Les livrables dans un projet SI
Les livrables sont les documents ou productions produits à chaque phase du projet. Ils peuvent être :
- cahier des charges fonctionnel ;
- cahier des charges technique ;
- maquettes ;
- documentation utilisateur/technique ;
- scripts de migration ;
- jeux de tests ;
- guide utilisateur ;
- plan de déploiement ;
- retours d’expérience.
Chaque livrable contribue à garantir la qualité et la traçabilité du projet.
## L’équipe projet et la gestion des ressources
### Les rôles dans un projet SI
Un projet informatique implique généralement :
- le chef de projet
    - coordonne l’équipe ;
    - pilote le planning ;
    - gère les risques ;
    - assure le reporting ;
    - fait le lien avec les parties prenantes.

- le _Product Owner (PO)_
    - représente le métier ;
    - définit les besoins ;
    - priorise le backlog ;
    - valide les fonctionnalités.

- le Scrum Master (dans un contexte de gestion de projet avec Scrum)
    - facilite les rituels Agile ;
    - résout les obstacles ;
    - veille à la bonne application de Scrum ;

- les développeurs
    - front-end, back-end ou fullstack selon le périmètre ;
    - le designer UX/UI ;
    - imagine les parcours utilisateurs ;
    - produit les maquettes ;
    - réalise les prototypes.

- le DevOps
    - automatise le déploiement ;
    - gère les environnements ;
    - supervise les performances.
- le QA/testeur
    - crée les plans de tests ;
    - exécute les tests ;
    - remonte les anomalies.
### Gestion des ressources
La gestion des ressources consiste à s’assurer que :
- les bonnes compétences sont disponibles ;
- au bon moment ;
- avec les bons outils ;
- dans le budget prévu.
Les ressources peuvent être humaines, matérielles (serveurs, licences logicielles) ou temporelles.
### La communication dans un projet
Une communication efficace est essentielle. Elle doit être :
- claire ;
- régulière ;
- structurée ;
- adaptée au public (technique ou non technique).

Les outils utilisés sont :
- messages courts (Teams, Slack) ;
- compte-rendus ;
- réunions d’avancement ;
- tableaux de suivi (Trello, Jira).
## Suivi et contrôle du projet
### Suivre l’avancement
Le suivi peut se faire via :
- Kanban (visualisation du flux) ;
- Gantt (planning) ;
- _burndown chart_ (Agile) ;
- indicateurs (retards, charge consommée, nombre de tâches en cours).
Il permet d’anticiper les dérives et de réajuster le planning si nécessaire.
### Contrôler la qualité
La qualité s’assure par :
- des revues de code ;
- des tests unitaires ;
- des tests fonctionnels ;
- une recette utilisateur ;
- des critères d’acceptation définis en amont.
### Gestion des changements
Dans un projet, tout changement doit :
- être exprimé clairement ;
- faire l’objet d’une analyse d’impact ;
- être estimé en charge ;
- être validé ;
- être planifié.
Une mauvaise gestion des changements peut mettre en péril l’ensemble du projet.
## Gestion des risques
### Identifier les risques
Les risques peuvent être :
- techniques (panne, bug critique, technologie instable) ;
- humains (départ d’un développeur, indisponibilité) ;
- planning (sous-estimation) ;
- organisationnels (communication insuffisante) ;
- qualité (livrables non conformes) ;
- externes (dépendance à une API tierce).
### Évaluer les risques
Chaque risque est évalué selon :
- sa probabilité ;
- son impact.
On utilise parfois une note de 1 à 9 ou une représentation visuelle en matrice.
### Traiter les risques
- éviter ;
- réduire ;
- transférer ;
- accepter.
La gestion proactive des risques est cruciale dans les projets SI.
## Communication de projet
La communication est un facteur majeur de réussite. Elle doit permettre :
- de partager l’avancement ;
- de clarifier les décisions ;
- d’anticiper les problèmes ;
- de synchroniser les équipes.

Le reporting est un outil simple mais indispensable. Il doit contenir :
- l’avancement réel ;
- les points marquants ;
- les blocages ;
- les risques ;
- les demandes d’arbitrage.
## Méthodologies de gestion de projet
### Waterfall
Méthode séquentielle où chaque étape doit être terminée avant de passer à la suivante.
Adaptée lorsque les besoins sont très stables et bien documentés.
### Cycle en V
Le cycle en V lie chaque phase de conception à sa phase de tests :
- spécifications fonctionnelles ↔ tests d’acceptation ;
- spécifications techniques ↔ tests système ;
- conception détaillée ↔ tests d’intégration ;
- développement ↔ tests unitaires.
Il est très utilisé dans les systèmes complexes où la qualité est critique.
### Agilité : Scrum et Kanban
#### Scrum
Se base sur des sprints courts et réguliers (souvent 2 semaines).
Rituels majeurs :
- sprint planning ;
- daily ;
- sprint review ;
- retrospective.

Artefacts :
- backlog produit ;
- backlog sprint ;
- increment.
#### Kanban
Méthode visuelle et continue.
Principes :
- limites du travail en cours (WIP) ;
- flux continu ;
- optimisation du temps de cycle.
### DevOps
DevOps combine développement et exploitation pour accélérer les cycles. Il s’appuie sur :
- l’intégration continue (CI) ;
- le déploiement continu (CD) ;
- l’automatisation ;
- la supervision en temps réel.
Il est essentiel dans les projets modernes de grande ampleur.
## Conduite du changement et retour d’expérience
### Conduite du changement
Un nouvel outil modifie les habitudes des utilisateurs.
La conduite du changement vise à faciliter cette transition à travers :
- la communication ;
- la formation ;
- l’accompagnement ;
- le support ;
- la documentation.
### Retour d’expérience (REX ou RETEX)
En fin de projet, un REX/RETEX permet de :
- analyser ce qui a bien fonctionné ;
- identifier les erreurs ou difficultés ;
- capitaliser pour les projets futurs.
Le REX/RETEX est un outil essentiel d’amélioration continue.
## Conclusion
Ce parcours couvre les bases indispensables pour comprendre et participer efficacement à un projet numérique ou informatique.
Il s’agit d’un socle fondamental pour les futures pratiques professionnelles, et un préalable essentiel avant d’aborder des modules plus avancés comme la gestion Agile, les architectures logicielles, ou encore la coordination d’équipes dans des environnements DevOps.