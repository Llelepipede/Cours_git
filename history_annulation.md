COMMANDE: git

$ git diff [--cached,] [HEAD][-(number)]  
-> affiche les differences entre le wd et l'index
->[--cached] affiche les differences entre l'index et le dernier commit
->[HEAD] affiche les differences entre les ancien git d'eloignement 'number'

$ git restore [--staged] (file.name)
-> restore l'etat du depot git
->[--staged] restore l'etait de l'index

$ git reset [--soft, --hard] HEAD-1
-> annule le dernier commit
->[--soft] place l'annulation dans l'index
->[--hard] suprime les modifications

$ git revert [commit.number]
-> ecrase le commit ^ pour mettre l'actuel
