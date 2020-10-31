> [Retour à README](README.md)

# Tuto commandes git
Si vous faites des changements dans la doc, créé une nouvelle branche : 
Commandes à faire dans la console du repo "Doc" : 

 ### *Mettre à jour la branche active*
   > **git pull**
        
 ### *Recupérer toutes les nouvelles branches*
   > **git fetch --prune**
 
 ### *Creer et aller sur une nouvelle branche créée*
  > **git checkout -b "nom_de_la_branche"**

 ### *Aller sur une branche déjà existante*
  > **git checkout "nom_de_la_branche"**
 
 ### *Quand vous avez fini vos modif :*
  #### *affiche les fichiers modifiés/créé/suppr*
  > **git status**
  #### *ajouter les fichiers modifiés (. pour tous les ajouter, mais à éviter, sinon mettre le nom du fichier)*
  > **git add . ou 'lefichiermodifé'**
  #### *ajouter un commentaire pour le commit (faire syntétique)*
  > **git commit -m "un commentaire"**
  #### *envoyer les changements en ligne (demande possiblement une connexion, si la branch n'est pas existante, la console va vous donner la commande a effectuer)*   
  > **git push**
