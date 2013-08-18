www.ericlesage.org
==================

Premier accès:

    git clone git@github.com:MuSSF/www.ericlesage.org.git

Modifier:

0.Si ajout d'un nouveau fichier (indispensable pour qu'il le voie)

    git add NouveauFichier.html

1.Puis, pour enregistrer les modifications dans la base de données locales : 

    git commit -a -m "Ajout nouveau fichier"
    
2.Enfin pour propager au dépôt (de référence ici) distant :

    git push origin master
    
Voir ce qui a été modifié dans le répertoire courant depuis le dernier commit:

    git status .
    
Supprimer les dernières modifications dans le répertoire courant depuis le dernier commit:

    git checkout .

Télécharger des modifications faites par un autre utilisateur:

    git pull origin master
    
Pour voir la liste des branches :

    git branch -a

Pour obtenir le contenu actuel d'une branche:

    git checkout next-july-2013
    
(où next-july-2013 est le nom de la branche)


Par prudence : envoyer par mail un fichier de diff à Fabrice - qui peut accepter/refuser facilement.

    git diff > mes_modif.patch

Supprimer les modifications avant un nouveau pull:

    git checkout .
