gérant dev : debiz et comlobet

Stockages des documents dans ce repo.
Clone le repo en local et faire un LiveSearch sur VScode.

Si vous faites des changements dans la doc :

    Faites une nouvelle branche : 

dans la console du repo "Doc"
 -> mettre à jour la branche active
        git pull
 -> recupérer toutes les nouvelles branches
        git fetch --prune
 
 -> Creer et aller sur une nouvelle branche créée
        git checkout -b "nom_de_la_branche"

 -> Aller sur une branche déjà existante
        git checkout "nom_de_la_branche"
 
 -> quand vous avez fini vos modif :
        ### affiche les fichiers modifiés/créé/suppr
            git status 
        ### ajouter les fichiers modifiés (. pour tous les ajouter, mais à éviter, sinon mettre le nom du fichier)
            git add . ou 'lefichiermodifé'
        ### ajouter un commentaire pour le commit (faire syntétique)
            git commit -m "un commentaire"
        ### Envoyer les changements en ligne (demande possiblement une connexion, si la branch n'est pas existante il va dire en console la commande pour y faire)    
            git push