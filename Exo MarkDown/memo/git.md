CONFIGURATION
-------------

git config --global user.name "Nom d'utilisateur"

git config --global user.email "utilisateur@mail.com"

git remote add origin https://github.com/GerardoCella7/testGitHub.git ==> Ajoute un referentiel

git remote -v ==> voir les referentiels

git init ==> Dans le dossier pour demarrer avec git

ssh-keygen -t rsa -b 4096 -C "utilisateur@mail.com"


VERSION ET COMMIT
-----------------

git status ==> Pour voir le statut des modification

git add filename ==> Ajout d'un fichier

git commit -m "description" ==> Prepare l'envoie

git commit --amend -m "description modifier" ==> modifie la description


ENVOYEZ
-------

git push &lt;remote> &lt;branch>

git push origin master ==> Envoye dans la branche master


RECEVOIR
--------
git fetch &lt;remote> || git fetch &lt;remote> &lt;branch> ==> Recupere la branche master et merge pas avec le repertoire de travail

git pull &lt;remote> &lt;branch>

git pull origin master ==> Recupere la branche master et merge avec le repertoire de travail


BRANCHE
-------

git branch ==> afficher les branches et * devant la branche utilisée

git branch test ==> creer une nouvelle branche test

git checkout test ==> pour passer sur la branche test

git checkout -b test2 ==> Creer et se place dans test2

git branch -d test ==> supprime la branche !!! S'il y à des commit sa produit un message d'erreur

git branch -D test ==> dans le cas ou il y as des commit et que l'on veus quand meme supprimer sans merge

git diff ==> voir la difference entre la branche en cours et master

git diff test..test2

git checkout test ||

git merge test2   ==> fusionne les deux branches dans test

git checkout test ||

git rebase master ==> fusionne et repositionne test sur master

git checkout master^ ==> deplace le curseur HEAD d'1 niveau dans la branche master

git checkout master^^ ==> deplace le curseur HEAD de 2 niveaux dans la branche master ...

git checkout HEAD~4 ==> deplace le curseur HEAD de 4 niveaux

git checkout &lt;ref> ==> deplace le curseur HEAD sur une ref bien precis

git branch -f master HEAD~3 ==> deplace la branche master de 3 niveaux parents à HEAD

Dans le cas d'un merge par defaut le **git checkout HEAD~** remonte sur l'axe principal 

si l'on veus remonter par l'axe merger il faus utilisé **git checkout HEAD^2** pour lui indiquer la deuxieme branche

on peut enchainer l'écriture **git checkout HEAD~^2~2** Remonte de 2 empreintant la deuxieme branche et remonte encore de 2


ANNULER DES CHANGEMENTS
-----------------------

git reset HEAD~1 ==> Annule le dernier commit (Ne fonctionne qu'en local)

git revert HEAD ==> Annule pour push creer un nouveau commit


DEPLACER LE TRAVAIL
-------------------

git cherry-pick &lt;ref> ==> comme le rebase

git cherry-pick &lt;ref1> &lt;ref2> &lt;ref3> ==> rebase dans l'ordre de declaration

git rebase -i HEAD~4 ==> reagencer les 4 derniers commit


TAG
---

git tag v1 &lt;ref> ==> ajoute le tag v1 au ref

git tag v1 ==> ajoute le tag v1 à HEAD


DESCRIBE
--------

git describe &lt;ref>

git describe ==> HEAD par defaut

renvoye comme reponse &lt;tag>_&lt;numCommits>_g&lt;hash>


FETCH
-----

git fetch

git fakeTeamwork

git rebase

git pull --rebase


DIVERS
------

git log ==> liste tous les commit

si on cree une branche 'gh-pages' sa creer un acces au site web en html statique https://&lt;nom utilisateur>.github.io/&lt;repository>/ ==> https://gerardocella7.github.io/testGitHub/ 

voir https://jekyllrb.com/ pour plus de détails

Voir fichier CNAME pour GitHub pour changer l'adresse pour un nom de domaine perso







A TRAITER
---------

undo

reset

revert

rebase

levels

build level

import level

show commands