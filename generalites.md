COMMANDE: git

$ git init
-> crée un dépot git dans .

$ git status
-> affiche les detatil du wd, de l'index et du dépot

$ git add (file.to.add)
-> ajoute       ^     a l'index

$ git commit [-m, none] ["commit name"]
->[none] crée un commit avec avec un nom et son commentaire
->[-m] marque le texte entre "" en tant que nom du commit

$ git log
-> montre l'historique de git

$ git config [--global] user.[name ,mail] "mail ou psuedo"
->[name] configure le nom de l'utilisateur git
->[mail] configure le mail de l'utilisateur git

$ git rm [--cached] (file.name)
->[--cached] supprime   ^  de l'index

$ git mv (file.name) (new.name)
-> renomme   ^      en    ^

$ git ls-files
-> affice les fichiers suivis

$ git blame (file.name)
-> recherche les auteurs des modifications
