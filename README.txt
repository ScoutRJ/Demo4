Git en lignes de commandes:

Pour pluller la repo du serveur de git:
git clone nom_repo_git


git status
	-rouge: changements fait, mais non commis

git add nom_fichier ou -A (all)
	ajouter les fichiers avant de les commiter

avant de commiter, il faut changer la git.config pour ajouter user.name, user.email

git config --global user.name "ScoutRJ"
git config --global user.email willywonka9732@gmail.com

git commit -m "Commentaire face au commit"
	-m pour message, suivi du message. Sinon, on doit ajouter un message en console par vim

git push (-u origin master pour la premiere fois pour spécifier la branche master)
username: "username"
password: "password"

git pull (pour updater le dépot local à partir du centrale)
