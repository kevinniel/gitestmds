# documentation

## commandes de base

- ```git init``` : Permet d'initialiser un repository local
- ```git add .``` : Permet d'ajouter les modifications de tous les fichiers à l'indexation
- ```git add <file>``` : Permet d'ajouter uniquement les modification de ```<file>``` à l'indexation
- ```git commit -m "<message>"``` : Permet de sauvegarder l'indexation en spécifiant un message
- ```git push -u origin <branch>``` : Permet d'envoyer les commit locaux sur le repository distant. (la ```<branch>``` par défaut est "master"). **N'est valable que pour le premier push**
- ```git push``` : Permet d'envoyer les commits locaux sur le repository. Ne fonctionne qu'à partir du 2ème push.
- ```git restore <file>``` : Permet de restaurer le fichier ```<file>``` à son étata d'indexation
- ```git clone <repo_url>``` : Permet de créer un repository local et d'automatiquement télécharger le contenu du repository distant disponible à l'adresse ```<repo_url>```

## Branches
- ```git branch``` : Permet de voir l'ensemble des branches
- ```git branch <nom>``` : Permet d'ajouter une branche du nom de ```<nom>```
- ```git checkout <branch>``` : Permet de changer de branche
- ```git branch -d <branch>``` : Permet de supprimer une branche en local
- ```git push origin --delete <branch>``` : Permet de supprimer une branche distante
- ```git merge <branch>``` : Permet de fusionner la branche ```<branche>```sur la branche actuelle

## Fork & PR

- Fork : 
    - se fait sur l'interface distante
    - copie le repo distant d'une personne dans VOS repo distants en gardant le lien
    - mise à jour possible grâce au bouton "sync fork"
    - vous pouvez travailler dessus comme vous le souhaitez
- PR : 
    - permet de proposer des modifications, qui doivent être discuter et / ou acceptées


## Autre
- .gitignore
    - Permet de lister les fichiers / dossiers à ne pas intégrer dans GIT
- issues
    - Permet de relever un problème / une question
    - Peut etre automatiquement fermée par un commit en précisant "Fix" et le numéro de l'issue en message de commit (ex : "Fix #20" ferme l'issue #20)
- alias
    - Permet de créer des raccourcis pour les commandes shell. Ex : ```alias .="cd .."```
- git flow
    - https://git-flow.readthedocs.io/fr/latest/presentation.html
- gitmoji
    - https://gitmoji.dev/
- Nommage des commits
    - https://www.conventionalcommits.org/en/v1.0.0/

# TP

## Groupes : 

- G1 - https://github.com/thibode/bashcoursgroupe1
    - Thibault Dequidt (Responsable)
    - Paul Rinfray
    - Eliott Le Duc
    - Leo Teixeira
- G2 - https://github.com/yoshiTorisutan-web/MDS_BASH_GRP2
    - Leon Cha
    - Damien Dubernet
    - Tristan Bossard (Responsable)
    - Clément Paquentin
- G3
    - Louis Maze
    - Lazare Mouzet (Responsable)
    - Maxence Cailleau
    - Leo Gautret
- G4 - https://github.com/theomax13/shellGroupe4
    - Elhoucine Essayad
    - Théo Maxime (Responsable)
    - Yassine Bouhi
    - Anaelle Thiers
- G5 - https://github.com/BastiennM/shellGroup5
    - Nathan Gaulard
    - Nathan Greffier
    - Leo Crasnier
    - Bastien Metais (Responsable)

## Énoncé

Réaliser un cours de Shell (Bash) en markdown 😁

## Organisation

Vous devez définir un chef de groupe, qui sera responsable du repository ET de la gestions des Pull Requests (rôle lead dev).

Chaque groupe doit travailler sur 1 repository unique (propriété du lead dev) et tous les membres du groupe doivent être mis en tant que Collaborateur.

Le Lead Dev devra commencer par organiser des issues et des Milestones. Chaque issue devra être assignée et un temps de réalisation devra être renseigné.

## Livrables

1 repository contenant : 

- 1 fichier readme.md, qui correspond à un sommaire de tous les cours que vous allez réaliser.
- 1 dossier par milestone (qui contiendra les markdown)
- 1 fichier markdown par cours (rangés dans les dossiers des milestones). Chaque cours devra être explicite, présenter la commande / fonction concernée, et intégrer un ou plusieurs exercices pour permettre de pratiquer ! (1 cours = 1 notion)



