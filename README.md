# recette-cookie

Travail autour de Git

De manière de supprimer un fichier dans l'historique : 
git rm --cached (file) permet de supprimer le fichier à partir du prochain commit


git filter-branch --index-filter 'git rm --cached (file)' HEAD
permet de supprimer le fichier dans tous l'historique du projet