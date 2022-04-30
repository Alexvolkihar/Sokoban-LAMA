# Sokoban-LAMA
Jeu Sokoban crée par le groupe LAMA: Antoine LAROCHE, Alexis MABANZA, Logan VIVIEN et Martin PACARY

Langage utilisé: Python
Version: 3.9.0 64-bits

Bibliothèque nécessaire: Pygame
Version: 2.0


Notice d'utilisation:
- Lancer une console de commande dans le dossier du jeu
- Utiliser une des deux commandes suivantes afin de:
    Résoudre le niveau:
        python main.py solve level/testX.txt

    Jouer le niveau:
        python main.py play level/testX.txt

    Où X est un nombre entre 1 et 14.
        Les niveaux 12, 13 et 14 n'ont pas de fin. L'algorithme A doit le remarquer tout seul.
        testX est le nom utilisé pour nos niveaux de jeu, cependant n'importe quel dossier .txt comportant un niveau exploitable
        par le programme peut être joué.
        ATTENTION: Le solveur peut parfois ne pas trouver la solution d'un niveau et se bloquer dans une boucle infinie, ce qui a pour
        effet de surcharger la RAM, utiliser les fichiers avec précaution.

Contrôles de jeu:
Flèche directionnelles: Déplacements du personnage%
