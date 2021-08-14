  # socle_git
## TItre niveau 2 par #
* liste non ordonner avec *

1. liste ordonner 

---
### titre de niveau 3 avec 3 fois #
___
 ligne orizontal avec 3 tiret underscore
Formation en **gras** avec double *

---
# NOTES

---
*git log -3 --author "pabios" ==> recherche les 3 dernier commit de pabios

### les branche
* elle s'appelle maintenant main au lieu de master sur github
* git branch -v (branch en cours )
* git rebase recuperer les elmt d'une branche a dans une branche b en gardant l'historique des commit

### creer une branche 
*git branch -b 
*git checkout -b nom_nouvelle_branche_a_y_basculer

##suprimer une branche 
*git branch -d nomBranche_a_supprimer

### Revenir a un commit donner
* git checkout plus l'identifiant du commit 
* git checkout 56bfa580eabcde1e331a94aae28617ba9b803034

# git stah 
### garder les modification qu'on ne veut pas push
*git stash nonFichier ==> garder les modification du fichier
*git stash clear ==:> supprimer tout les stash




### du code avec 3 foi  `coller  le language 
```html
<html>
<head> </head>
<body>
	<p> je suis un paragraphe </p>
</body>
 </html>
<<<<<<< HEAD
---
# NOTES

---
=======

>>>>>>> dev
# git ignore
creer le file .gitignore et a l'interieur j'ignore tout les fichier qui se termine par .py avec *.py
___
* AVEC git diff nonFichier voir les modification sur le file
* ```git rm nomFicher``` supprime le file du depot 
Apres une suppression d'un fichier commiter on le supprime en tapant git rm nomFichier
(ennuler la modification avec ```git reset HEAD nomFichier```)
```git 
git restore fichier_deja_supprimer ==> remetre a jour le repertoir courant


[lien](http://guish.site) lien avec [ ecrire lien ](et le lien ici )
