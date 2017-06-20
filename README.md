# test


# annuler les changement d'un fichier
git checkout <nom_fichier>

# annuler un commit pusher sur le distant en gardant une trace
Git revert

# Ajouter un patch
git add --patch README.md

# nettoyage des fichiers qui ne sont pas dans l'index
git clean -f

# Revert + clean
git reset --hard HEAD^

# Créer une branche
git checkout -b <nom_branche>


# Aller sur la nom_branche
git checkout <nom_branche>


# mettre la nouvelle branche sur le depot distant
git push origin <nom_branche>


# supprimer une branche local
git branch -d <nom_branche>


# supprimer une branche sur le remote
git push origin --delete <nom_branche>


# Initialiser un flow
git flow init


# Information sur git flow
rechercher sur google git flow cheatsheet
