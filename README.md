# Projet-Java

# Sujet

[Le sujet 2021](https://github.com/MehdiBoutab/Agricultural-development-game-and-war-game/blob/main/sujet2021.pdf)

# Livrables

## Livrable 1
Nous avons réalisé le diagramme nécessaire qui représente les deux jeux .

### Atteinte des objectifs
faire les classes nécessaire et deviser le travail entre les membres de groupe .

### Difficultés restant à résoudre

## Livrable 2
Nous avons réalisé la classe :
 * Player qui représente un joueur et chaque joueur possède un nombre limité d'or.
 * Game qui représente le jeu 
 * Unit 
 * Map qui représente la table du jeu.
 * Tile qui représente les différents tuiles 

### Atteinte des objectifs

### Difficultés restant à résoudre

## Livrable 3
- Cette semaine on fait un changement du nom de la classe d'unité en Personnage (personnage) pour mieux correspondre à la description donnée dans l'énoncé.
- Suppression de la classe de soldat car elle est remplacée par simplement un int dans la classe Army
- Changement du nom de certaines méthodes pour mieux s'adapter au diagramme UML
Suppression des méthodes répétées dans les classes héritées
### Atteinte des objectifs
faire presque toutes les classes nécessaire pour le jeu
### Difficultés restant à résoudre
pouvoir affichée l'interface graphique (map)

on a pu réaliser les deux condition pour pouvoir créer "Map" qui sont 
 • le plateau doit comporter au minimum deux tiers de tuiles de type océan 
 • toutes les tuiles de type montagne, plaine, désert ou forêt doivent au moins avoir une tuile adjacente qui n’est pas
de type océan.
On a fait un changement au niveau de packetage .
Pour faire les tests il suffit de lancer le jeu en Map et on obtient :

<details>
  <summary>
    output du terminal:
  </summary>

    1: war; 2: farm
    Choose game type:> 
    1
    User chosen: game.WarGame
    (1,1) has 4 ocean tiles.

    (2,1) has 3 ocean tiles.

    (3,1) has 3 ocean tiles.

    (4,1) has 4 ocean tiles.

    (5,1) has 3 ocean tiles.

    (6,1) has 3 ocean tiles.

    (1,2) has 3 ocean tiles.

    (2,2) has 2 ocean tiles.

    (1,3) has 3 ocean tiles.

    (2,3) has 3 ocean tiles.

    (3,3) has 3 ocean tiles.

    (4,3) has 3 ocean tiles.

    (5,3) has 3 ocean tiles.

    (6,3) has 3 ocean tiles.

    (1,4) has 3 ocean tiles.

    (2,4) has 2 ocean tiles.

    (1,5) has 3 ocean tiles.

    (2,5) has 3 ocean tiles.

    (3,5) has 3 ocean tiles.

    (4,5) has 4 ocean tiles.

    (5,5) has 3 ocean tiles.

    (6,5) has 3 ocean tiles.

    (1,6) has 3 ocean tiles.

    (2,6) has 2 ocean tiles.

    ROUND: 1 OF 10

    fayssal has 15 gold; and 0 workers.

    aya has 15 gold; and 0 workers.

    mehdi has 15 gold; and 0 workers.

    ziko has 15 gold; and 0 workers.

    *===* testMap *===*

        0    1    2    3    4    5    6    7  

    0 [O, *] [O, *] [O, *] [O, *] [O, *] [O, *] [O, *] [O, *] 

    1 [O, *] [F, *] [M, *] [O, *] [F, *] [M, *] [D, *] [O, *] 

    2 [O, *] [M, *] [O, *] [O, *] [O, *] [O, *] [O, *] [O, *] 

    3 [O, *] [P, *] [P, *] [D, *] [M, *] [M, *] [D, *] [O, *] 

    4 [O, *] [D, *] [O, *] [O, *] [O, *] [O, *] [O, *] [O, *]

    5 [O, *] [P, *] [M, *] [O, *] [M, *] [M, *] [F, *] [O, *] 

    6 [O, *] [F, *] [O, *] [O, *] [O, *] [O, *] [O, *] [O, *]

    7 [O, *] [O, *] [O, *] [O, *] [O, *] [O, *] [O, *] [O, *] 

    It's fayssal's turn: 

    ROCK: 0; CORN: 0; SAND: 0; WOOD: 0; 

    1 => DEPLOY; 2 => EXCHANGE; 3 => SKIP

    make your choice :> 1

    chose a position :> 1,1 // c'est dans ce niveau où normalement le joeur prend la position dans la cellule (1,1) mais ça ne fonctionne pas pour l'instant : 

    ROUND: 1 OF 10

    fayssal has 15 gold; and 0 workers.

    aya has 15 gold; and 0 workers.

    mehdi has 15 gold; and 0 workers.

    ziko has 15 gold; and 0 workers.

    *===* testMap *===*

        0    1    2    3    4    5    6    7  

    0 [O, *] [O, *] [O, *] [O, *] [O, *] [O, *] [O, *] [O, *] 

    1 [O, *] [F, *] [M, *] [O, *] [F, *] [M, *] [D, *] [O, *] 

    2 [O, *] [M, *] [O, *] [O, *] [O, *] [O, *] [O, *] [O, *] 

    3 [O, *] [P, *] [P, *] [D, *] [M, *] [M, *] [D, *] [O, *] 

    4 [O, *] [D, *] [O, *] [O, *] [O, *] [O, *] [O, *] [O, *] 

    5 [O, *] [P, *] [M, *] [O, *] [M, *] [M, *] [F, *] [O, *] 

    6 [O, *] [F, *] [O, *] [O, *] [O, *] [O, *] [O, *] [O, *] 

    7 [O, *] [O, *] [O, *] [O, *] [O, *] [O, *] [O, *] [O, *] 

    It's aya's turn: 

    ROCK: 0; CORN: 0; SAND: 0; WOOD: 0; 

    1 => DEPLOY; 2 => EXCHANGE; 3 => SKIP
</details>


## Livrable 4
* les méthodes non nécessaires ont étés supprimes
* les méthodes répétés entre les superclasse et les surclasses ont étés supprimé
* utilisation des méthodes abstract pour definir des fonctionnalités communs antre les surclasses
* division de la classe player en 2 subclasses PlayerWar et PlayerFarm.
* le programme maintenant nous donne comme output: <br /> 
  ![une gif contenant l’exécution](https://gitlab-etu.fil.univ-lille1.fr/lakehala/l2s4-projet-2021/-/raw/master/images/2021-04-09%2010-25-34.gif)
* création d'un diagramme uml final
* ajoute des commentaires pour toutes les méthodes
* extraction des constantes (ctrl+1 sur eclipse) pour mieux organiser le code
* ajout des tests map, game, gameWar
* suppression des fichier non nécessaires du depot git.
### Atteinte des objectifs
finir la classe Map
### Difficultés restant à résoudre
On a eu des difficultés au niveau de tuiles pour qu’elles doivent au moins avoir une tuile adjacente qui n’est pas
de type océan.
=====
* l'execution des tests se fait dans eclipse avec success.
* une version minimalist complete du projet est disponible.
* en lancant WarGame/FarmGame on peut tester les 2 programmes de chaque jeu.
## Dernier Livrable
* La classe Map a été supprimer et remplacer pas la class Board
* supression de certains classes comme DesertTile.java, ForrestTile.java, Array.java,.. 
* Ajouter des methodes d'actions pour FarmGame et WarGame
* ajoute des commentaires pour toutes les méthodes
* Pouvoir réaliser  toutes les actions demandées dans le sujet .
* ajouter des tests pour chaque methode dans les classes 
* création d'un diagramme uml final
* creer un makefile pour compiler les commandes .

### Atteinte des objectifs
* pouvoir réaliser toutes les actions necessaire pour le jeu de wargale et farmgame .
### Difficultés restant à résoudre
* Dans ce livrable On a eu des difficultés au niveau des actions et dans ce cas on a essayé de simplifier les choses au maximum juste pour pouvoir réaliser les actions de chaque jeu .
# Journal de bord
====
## Semaine 1
on a essayé de faire le diagramme UML qui représente notre projet pour mieux comprendre et faciliter le travail.
## Semaine 2
On a eu du mal pour comprendre si certaine classes sont nécessaire où pas comme la classe soldiers et army et c'est quoi la nature de chaqu'une 
## Semaine 3
Dans l’évolution de faire des nouvelles methodes pour pouvoir affficher le plateau avec les tuiles et les joueurs. 
## Semaine 4
dans cette semaine on a finit la classe Map pour pouvoir continuer le reste des condition pour chaque jeux . 
## Semaine 5

## Semaine 6

## Semaine 7
* suppression des méthodes nécessaires/repetees.
* changement de la visibilité de quelque variables de publique vers privees/protected
* correction du design des classes utilises dans le projet
  
## Semaine 8
* todo: actions des caractères
* todo: les tests de quelques classes
* todo: ajoute de couleurs a la class map pour chaque système d'exploitation.
* test de map qui s'affiche maintenant avec des couleurs:  
![map](https://gitlab-etu.fil.univ-lille1.fr/lakehala/l2s4-projet-2021/-/raw/master/images/map_with_color.png)

    * des fois les couleurs ne marchent pas a cause du manque du support code ASCII dans la console utilisée.
* après ajoute de couleurs et ajout de l'analyse de l'entrée utilisateur:
![gif contenant un test après modifications](https://gitlab-etu.fil.univ-lille1.fr/lakehala/l2s4-projet-2021/-/raw/master/images/2021-04-10%2005-03-41.gif)
* démonstration actions support:
![gif support](https://gitlab-etu.fil.univ-lille1.fr/lakehala/l2s4-projet-2021/-/raw/master/images/2021-04-11%2018-12-54.gif)
* demonstration actions attack:
![gif attack](https://gitlab-etu.fil.univ-lille1.fr/lakehala/l2s4-projet-2021/-/raw/master/images/2021-04-11%2018-17-04.gif)
## Semaine 9
* suppression de la classe Map et la remplacer avec Board( juste pour ne pas confondre entre l'élément Map qui existe déja en java ).
* Ajouter quelque méthode dans classe Board.java comme : la fonction random qui est pour avoir un x et un y qui vont introduire une cas au départ au hasard et construire au tour de cette case
* Supprimer les classe DesertTile.java, ForrestTile.java, MountainsTile.java, OceanTile.java et PlainsTile.java et mettre toutes ces classes dans une seule class Tile.java  pour pouvoir coder les tuiles dans la classe Tile directement .
* Supprimer la classe Army.java car on a vu qu’elle sert a rien et on a pu la remplacer avec l’attribut nbUnits dans la classe Tile qui pour ajouter 1 soldats où retirer 1 soldats dans le jeu .
## Semaine 10
* Dans cette semaine on a basé sur les actions
* Créer la classe Util.java pour pouvoir jouer et choisir entre les deux jeux et mettre les actions nécessaires pour chaque jeu
* Modifier la classe Player : supprimer quelques méthodes et ajouter d’autres comme addgol, lostTile si la tuile est attaquée par exemple
* Modifier la classe WarPlayer et ajouter des fonctions d’action spécialement au jeu de guerre comme deployWar(), recoltFood() et distribFood() 
* Modifier la classe Game :ajouter la fonction displayGame() qui est pour afficher le jeu, et ajouter les méthode  pour pouvoir afficher le résultats et indiquer si le jeu est terminé.
* Modifier la classe WarGame : dans cette classe où toutes les règles du jeu de guerre sont définies 
## Semaine 11
* Modifier la classe FarmGame
* Faire les tests nécessaire pour chaque méthode 
* Créer le Makefile de fichier et génerer le Readme 
## L'éxecution du projet :
* Pour tester la fonctionnalitée du jeu de guerre, il faut se mettre dans le fichier ../l2s4-projet-2021/src/main
et lancer WarMain.java dans exclipse 
* Pour tester la fonctionnalitée du jeu d'agricole , il faut se mettre dans le fichier ../l2s4-projet-2021/src/main
et lancer FarmMain.java dans exclipse 
* ===> C'est a vous de jouer <=====
* Pour générer les tests il faut les génerer sue Eclipse 

![demoFarm](https://gitlab-etu.fil.univ-lille1.fr/lakehala/l2s4-projet-2021/-/raw/master/images/Demo_FarmGAme.gif)

![demoWar](https://gitlab-etu.fil.univ-lille1.fr/lakehala/l2s4-projet-2021/-/raw/master/images/demo_warGame.gif)
