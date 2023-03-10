# documentation

## commandes de base

- ```git init``` : Permet d'initialiser un repository local
- ```git add .``` : Permet d'ajouter les modifications de tous les fichiers à l'indexation
- ```git add <file>``` : Permet d'ajouter uniquement les modification de ```<file>``` à l'indexation
- ```git commit -m "<message>"``` : Permet de sauvegarder l'indexation en spécifiant un message
- ```git push -u origin <branch>``` : Permet d'envoyer les commit locaux sur le repository distant. (la ```<branch>``` par défaut est "master"). **N'est valable que pour le premier push**
- ```git push``` : Permet d'envoyer les commits locaux sur le repository. Ne fonctionne qu'à partir du 2ème push.
- ```git restore <file>``` : Permet de restaurer le fichier ```<file>``` à son étata d'indexation