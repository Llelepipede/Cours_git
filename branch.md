COMMANDE: git

$ git branch (branch.name, none)
->(none) affiche les branches
-> crée une branche avec le nom indiqué

$ git checkout [-b] (branch.name)
-> deplace HEAD sur      ^
->[-b] crée la branche et ce déplace dessus

$ git merge (branch.name)
-> relie la branche cible au HEAD

$ git stash [list, apply, drop]
-> remise un code non fini
->[list] liste les stash
->[apply] recupere le code remise
->[drop] supprime la remise

$ git tag [-a, -l] (version) [-m] (version.name)
-> ajoute une banniere legere de type 'version'
->[-a] applique une banniere de type 'version'
->[-l] recherche les tags de type 'version'
->[-m] nomme la version 'version.name'
->[none] affiche les tags

$ git --bare init
-> cree un serveur git

$ git remote [add, -v, show] (serv.name) (serv.directory)
-> affiche les depots distant
->[add] ajoute le serveur distant sous le nom 'serv.name'
->[-v] liste les serveurs
->[rm] supprime le depot
->[rename] renomme le depot
->[show] inspect le depot

$ git push (serv.name) (branch.name)
-> transmet au serveur la branches cible

$ git fetch (serv.name)
-> recupere la branche distante sans fusion

$ git pull (serv.name)
-> fetch + merge


