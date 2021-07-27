        Le choix du sujet n’est pas du au hasard : le développement d’une intelligence artificielle est pour nous la principal cause de notre choix. L’intelligence artificielle en question est A* ,qui jusqu’à présent nous est inconnus. Le
principe de cette intelligence est de trouver le chemin le plus cours d’un point de départ jusqu’à son point d’arrivé.
Cela poursuit les différentes implémentation d’intelligence artificielle étudié et nous permet d’approfondir nos connaissance une nouvelle fois sur le sujet.

        
        Architecture du dossier principale :
        
Build : permet de contenir les fichier .class.
src : contient les packages ainsi que les différentes classes.
rapport : contient le rapport sous format pdf.
compilation.sh : Script permettant l’execution du programme.

        Compilation du projet :
        
Ouvrir un terminal dans le dossier principale contenant src ,build et compilation.sh;
Lancer le script de compilation avec la commande ./compilation.sh
L’exécution va générer un plateau aléatoire , qui seras affiché sur la console en mentionnant l’objectif a atteindre
plus bas.

Affichage plateau :

Robots = R,B,V,Y.
Mur = - ou | ou -
Angles = -| , |- etc..
Case vide = .

Le choix d’un menu est alors affiché :
Choissir un choix de jeu :
Choix 1 : Résolution automatique = ’1’
Choix 2 : Résolution saisie clavier = ’2’
Choix 3 : Affichage du chemin le plus court = ’3’
Choix 4 : Quitter le jeu = ’4’

Il faut alors saisir un entier entre 1 et 4. L’entier 1 permet une résolution autonome du plateau affiché en affichant
également les directions empruntées ainsi que le plateau final.
L’entier 2 permet à l’utilisateur de jouer au clavier.
L’entier 3 permet uniquement d’afficher le chemin pour le plateau actuelle.
L’entier 4 permet de quitter le programme.
