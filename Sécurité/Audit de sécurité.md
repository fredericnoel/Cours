Ce cours a pour vocation de faire passer les étudiantes et étudiants d'une visions « sécurité technique » à une posture d'auditeur S.S.I.
Les objectifs sont les suivants : 
- évaluer ;
- prouver ;
- hiérarchiser ;
- recommander ;
- documenter.
# Introduction à l'audit de sécurité
## Définition opérationnelle
Un audit de sécurité est une démarche structurée d’évaluation du niveau de maîtrise des risques liés au système d’information, fondée sur :
- des référentiels reconnus ;
- des preuves vérifiables ;
- une analyse de risques contextualisée ;
- une restitution exploitable par la direction.
Un bon audit permet de décider :
- où investir ;
- quoi corriger en priorité ;
- quel risque accepter.
## Différence entre audit, contrôle, test et scan
| Démarche | Finalité                | Livrable             |
| :------- | :---------------------- | :------------------- |
| Scan     | Détection automatisée   | Rapport brut         |
| Pentest  | Exploitation            | Vulnérabilités       |
| Contrôle | Vérification ponctuelle | Conformité           |
| Audit    | Vision globale          | Décision stratégique |
En audit, un outil n’est jamais une preuve en soi.
## Responsabilité de l'auditeur
L’auditeur est responsable de :
- la méthode ;
- la traçabilité :
- la neutralité :
- la compréhension métier.
Il n'est pas responsable :
- des failles ;
- des choix de l'organisation.
## Exemple réaliste
Cas d'un audit S.S.I. d'un établissement d'enseignement supérieur :
- pression « R.G.P.D. » ;
- S.I. hétérogène ;
- faible maturité en sécurité informatique ;
- budget limité.
# Plan d'audit
## Le périmètre : point de rupture classique
Le périmètre est en soi un contrat implicite. Tout ce qui n'est pas explicitement écrit :
- sera contesté ;
- sera rejeté ;
- ne pourra pas être reproché.
### Typologies de périmètre
- fonctionnel (applications) ;
- technique (infrastructure, réseau) ;
- organisationnel (processus) ;
- géographique ;
- temporel.
Éviter les généralité du genre « audit du S.I. de l'entreprise » (trop vaste), être plus précis : audit des mécanismes d'authentification, d'habilitation et de sauvegarde du L..M.S. et de la base de données étudiants, hors postes personnels et prestataires externes.
## Définition des objectifs d'audit
Un objectif doit être :
- précis ;
- mesurable ;
- relié à un risque.
Exemple d'objectif : évaluer la capacité de l’organisation à garantir la confidentialité et l’intégrité des données de l'ensemble du personnel en cas d’incident ou d’erreur humaine.
## Profondeur d'audit : lecture multi-couches
Un audit croise systématiquement :

| Niveau          | Question           |
| --------------- | ------------------ |
| Politique       | Est-ce formalisé ? |
| Organisationnel | Est-ce appliqué ?  |
| Technique       | Est-ce effectif ?  |
| Réel            | Est-ce contourné ? |
Exemple : si la politique des mots de passe est en phase avec les exigences définies dans la politique de sécurité, elle devient inutile si les utilisateurs ne sont pas formés ou n'adhèrent pas aux bonnes pratiques.
## Formalisation du plan d'audit
Contenu attendu :
- objectifs ;
- périmètres ;
- exclusions ;
- hypothèses ;
- référentiels ;
- méthodes de preuve ;
- limites ;
- planning.
Le plan d'audit définit un cadre et permet également à l'auditeur de se protéger en cas de litige.
# Grille de contrôle
## Rôle réel de la grille 
La grille n'est pas un tableau à remplir ou une checklist « administrative ».
Elle doit être considérée comme un outil de démonstration, une preuve de méthode et éventuellement comme un support d'ordre juridique.
## Construction d'une grille avancée
Chaque contrôle droit répondre à :
- pourquoi ce contrôle existe ;
- quel risque il couvre ;
- comment il est vérifié ;
- quelle preuve est attendue.
Exemple de contrôle enrichi :

| Thématique   | Détail                               |
| ------------ | ------------------------------------ |
| Contrôle     | Gestion des comptes actifs           |
| Risque       | Accès non autorisés                  |
| Attendu      | désactivation automatique <90 jours  |
| Vérification | Revue des comptes *Active Directory* |
| Preuve       | Export + capture                     |
## Les différents états de conformité
- conforme ;
- conforme avec réserve ;
- partiellement conforme ;
- non conforme ;
- non applicable (à justifier, doit être argumenté).
## Erreurs fréquentes
- appliquer ISO « mot à mot » ;
- ignorer le contexte métier ;
- mélanger conformité et risques.
# Collecte et traçabilité de preuves
## Une preuve doit être
- vérifiable ;
- datée ;
- reproductible ;
- reliée à un contrôle.
## Hiérarchie des preuves
1. Preuve technique directe ;
2. Observation ;
3. Documentation officielle ;
4. Déclaration (peu de valeurs si pas de traces).
### Exemple de chaînage de preuves

| Étape      | Preuve               |
| ---------- | -------------------- |
| Contrôle   | Sauvegarde           |
| Preuve n°1 | procédure écrite     |
| Preuve n°2 | logs de backup       |
| Preuve n°3 | test de restauration |
Une étape manquant rend la chaînage de preuve « fragile » et facile à opposer.
## Registre de preuves (obligatoire)
Pour chacune des preuves :
- ID unique ;
- source ;
- date et heure ;
- contrôle associé ;
- commentaires auditeur.
# Diagnostic risques & menaces
## Le risque n'est pas la vulnérabilité
« Risque d'accès non autorisé aux données » n'est pas la même chose que « mot de passe faible ».
## Construction systématique
Actif → Menace → Vulnérabilité → Impact → Risque

| Étapes        | Description               |
| ------------- | ------------------------- |
| Actif         | Base utilisateurs         |
| Menace        | Ancien salarié            |
| Vulnérabilité | Compte non désactivé      |
| Impact        | Violation RGPD            |
| Risque        | Sanction + atteinte image |
## *Scoring* raisonné
Le score n'est jamais absolu. Il dépend des éléments suivants :
- le contexte ;
- l'exposition ;
- les contrôles existants.

| Risque          | Probabilité | Impact | Score |
| --------------- | ----------- | ------ | ----- |
| Compte orphelin | 3           | 4      | 12    |
## Cartographie
- faible → acceptable ;
- moyen → à surveiller ;
- élevé → action prioritaire ;
- critique → décision immédiate.
# Recommandations
## Une recommandation n'est pas une solution technique
« Renforcer le contrôle des flux sortants afin de réduire le risque d’exfiltration de données » est différent de « installer un firewall ».
## Typologies
- préventive ;
- corrective ;
- détective ;
- organisationnelle.
## Priorisation experte
La priorisation se fait selon :
- le risque résiduel ;
- la faisabilité ;
- la maturité de l'organisation.

| Recommandation                                            | Effort | Risque réduit | Priorité |
| --------------------------------------------------------- | ------ | ------------- | -------- |
| *Multi-factor authentication* (M.F.A.)                    | Moyen  | Élevé         | Haute    |
| Politique de sécurité du système d'information (P.S.S.I.) | Faible | Moyen         | Haute    |
# Rapport d'audit
## Le rapport n'est pas pour les techniciens
Il est destiné aux fonctions suivantes :
- direction ;
- décideurs ;
- juristes.
## Synthèse exécutive
Doit répondre aux questions : 
- sommes-nous exposés ?
- à quoi ?
- à quel niveau ?
- que faisons-nous ?
## Annexes
Les annexes sont nécessaires pour :
- fournir des preuves ;
- détailler les éléments fournis ;
- sécuriser l'audit.
# Atelier final
- défendre le rapport ;
- contester la simulation réalisée ;
- arbitrer niveau budget ;
- définir le niveau d'acceptation du risque.