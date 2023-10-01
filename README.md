# Sudoku_solver
sudoku python
Le projet sudoku_solvers est fait avec trois méthodes de résolution authomatique pour n'importe quel fichier .txt
J'ai d'abord utilisé la méthode de la force brute et affiché le résultat avec pygame pour observer l'incrementation du résultat
Le code verifie toutes les combinaisons possibles avant de poser un chiffre. Elle commence par remplir la première case vide avec le chiffre 1 puis 2; ...etc. Si le chiffre ne corresponds pas elle retourne en arriere pour ajouster les chiffres précedents.  C'est une méthode qui teste beaucoup de combinaisons ce qui prends enormement du temps.
En terme de codage elle nécessite beaucoup d'informations ce qui rends le code assez complexe et difficile.  
J'ai fait un deuxième fichier avec la méthode du Backtracking et  l'affichage pygame. Cette methode est une amelioration de la méthode de la force brute. Cette méthode remplit les cases du sudoku de manière ordonné et elle revient en arrière si un coflit est détecté pour reajuster les valeurs. Pour obtentir le résultat le temps d'attente est assez long mais moins long que celui de la force brute.
J'ai aussi fait une solution orienté objet cette solution représente le sudoku sous forme d'objets et de classe ce qui permet de modéliser mieux les règles de jeu. Avec cette méthode on crée des classes pour représenter la grille de sudoku, les cases, les lignes et les colonnes. Cella aide à résoudre le sudoku comme un puzzle. 
Cette solution me semble la plus rapide pour afficher le résultat et le code utilisé rends la resolution du sudoku de manière plus intelligente. C'est certainement la méthode la plus efficace pour resoudre un sudoku rapidement.
