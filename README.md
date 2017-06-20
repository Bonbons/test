# test

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
