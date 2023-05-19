#Cheat Sheet git

##Premièr lancement

git config --global user.email "example@youremail.com" -->  j'entre mon email
git config --global user.name "username" --> j'entre mon nom d'utilisateur

##Versionner son travail

git init --> initialiser le dépôt

git clone "_lien-HTTPS-du-dépôt_" --> permet de récupérer une copie en local du dépôt sur lequel nous allons travailler
code . --> ouvre l'éditeur de code dans le dossier du dépôt

git status --> permet de voir l'état du dépôt en cours d'utilisation

git add "_example.ex_" --> permet d'ajouter un document dans son dépôt
git commit -m "_message_"--> sauvegarde les éléments qui sont maintenant près à être partagés dans le dépôt distant*

git push origin main --> permet d'envoyer tous les fichiers qui ont été commit dans le dépôt distant
git pull --> permet de récupérer les modifications que d'autres personnes, qui ont accès à la modification du et/ou des fichiers
