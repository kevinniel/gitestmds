# documentation

## commandes de base

- ```git init``` : Permet d'initialiser un repository local
- ```git add .``` : Permet d'ajouter les modifications de tous les fichiers à l'indexation
- ```git add <file>``` : Permet d'ajouter uniquement les modification de ```<file>``` à l'indexation
- ```git commit -m "<message>"``` : Permet de sauvegarder l'indexation en spécifiant un message
- ```git push -u origin <branch>``` : Permet d'envoyer les commit locaux sur le repository distant. (la ```<branch>``` par défaut est "master"). **N'est valable que pour le premier push**
- ```git push``` : Permet d'envoyer les commits locaux sur le repository. Ne fonctionne qu'à partir du 2ème push.
- ```git restore <file>``` : Permet de restaurer le fichier ```<file>``` à son étata d'indexation

## Branches
- ```git branch``` : Permet de voir l'ensemble des branches
- ```git branch <nom>``` : Permet d'ajouter une branche du nom de ```<nom>```
- ```git checkout <branch>``` : Permet de changer de branche
- ```git branch -d <branch>``` : Permet de supprimer une branche en local
- ```git push origin --delete <branch>``` : Permet de supprimer une branche distante
- ```git merge <branch>``` : Permet de fusionner la branche ```<branche>```sur la branche actuelle



🖕

