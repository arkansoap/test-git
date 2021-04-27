# Présentation

Dépot permettant de tester les fonctionalités de github et les commandes git

## commandes de bases :

- git clone [url] : Pour récupérer un dépot github en local

- touch [fichier] : pour créer un fichier en local 
- mkdir [dossier] : pour créer un dossier en local 

- git add [fichier] : Pour ajouter un fichier en local  (git add . pour ajouter tous les changements)

Pour annuler le git add lorsqu'on n'a pas encore commit : git reset  

- git commit -m "message" : pour préparer l'envoir sur github
- git status : pour checker les fichiers qui vont être envoyés 
- git push -u origin master : pour envoyer sur le dépot github

## Fonctionnement de .gitignore :

- Inscrire le fichier dans le fichier gitignore pour l'ignorer

Un fichier n'est pas ignorer par gitgnore s'il a été créé avant d'être inscrit sur gitignore.\
On utilisera alors : git rm --cached [fichier]

- Pour ignorer tous les fichiers d'un type on utilise *[.type]
- Pour ignorer tous les fichiers d'un type dans tous les dossiers on utilise **/[.type]