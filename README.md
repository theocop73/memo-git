Ceci est un Readme memo git:


git status : 
Indique tout les fichiers en attente d'être commit

git add:
ajoute un fichier/dossier dans une "file d'attente"

git commit:
va faire un enregistrement de tout ce qui ce trouve dans la "file d'attente"

git push:
va envoyé les commit vers notre repo distant

git fetch:
télécharge les commits , fichiers du dépot distant

git merge:
permet de selectionner du codes fait sur une branche et de l'intégrer à une autre branche

git pull:
git pull = git fetch + git merge,
utilisée pour faire un fetch du contenu d'un dépôt distant et pour le télécharger, puis pour mettre à jour immédiatement le dépôt local 

git checkout:
va permettre de changer de branche de travail, utilisé avec l'option -b si la branche indiqué n'existe pas elle est créée

git log:
affiche la liste des commits parents depuis un commit donné

  ----------------------------
  
  Qu'est ce qu'un conflit git :
  
  un conflit est une erreur qui arrive lorsque des modifications ont était faite en même temps sur un même fichier produisant l'impossibilité de pull ou de push ce qui à était fait en local.
  
  A quoi ca ressemble :
  
  dans le fichier concerné tout ce qui est en conflit va se retrouver entre  
  <<<<<<<<< "blabla1" =============== "blabla2" >>>>>>>>>>>>
  
  pour le résoudre je dois supprimer tout les caractères spéciaux qui définissent le conflit et ensuite je garde et/ou supprime le contenu que je veux.
  


