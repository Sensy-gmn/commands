git init -> initialise git pour le projet
git config -> configurer votre profile pour utiliser git
git clone <URL_DU_REPO> -> clone sur votre machine le projet d'un repo distant
git remote add origin <URL_DU_REPO> -> permet de lier un projet de votre machine à un repo distant

git add file/path/file.ext -> ajoute un fichier modifié/créé au prochain commit
git add . -> ajouter tous les fichiers modifiés/créés au prochain commit

git branch -> affiche la liste des branches en indiquant celle sur laquelle vous etes positionné
git branch branchename -> créer un branche
git checkout branchname -> permet de se positionner sur la branche donnée (créér la branche si elle n'existe pas)

git commit -m "le message du commit" -> permet de créér un commit en indiquant un message pour le commit

git push -> pousse les modifications listées dans le commit vers le repo distant
git pull -> récupérer les modifications qui sont sur le repo distant

git stash -> écarte certaines modifications du prochain commit
git stash apply -> replace les modifications qui ont été stash

git status -> retourne l'état du repertoire

git rebase -> rebase une branche sur une autre
git merge -> permet de fusionner une branche sur une autre

git log -> affiche l'historique des commit

git revert -> revenir sur la version précédente

git blame <VERSION> -> affiche version et son auteur

git rm —cached -r <FILE_PATH> → supprime le fichier spécifié du repo
