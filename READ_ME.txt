To do list 

Ecran d acceuille:
  ecran d accauille qui disparait appres avoir appuyer sur "space" et avce les regles de jeux 
Project report:(kenza)
  A report explaining the game's design, including:
  Descriptions of main components.
  Pseudocode outlining the key logic (e.g., game loop, collision detection).
  Complexity analysis of key components, such as:
  Player and enemy movement logic.
  Collision detection for bullets.
  Game loop efficiency.





Game_log:
  A partir de end game, faire d'autre fonctions pour implementer : 
  
  Enregistrer le score dans un fichier en append en demandant le nom du joueur dans un input turtle 
  
  Dans le fichier : score, nom, date, level validé =(courant -1) 
  
  Relirer tout le fichier, le mettre dans une liste , le trier selon le score, et afficher les 5 best scores 
  
  Choix de l'algo de tri à faire : pas bcp de ligne 
  
  https://www.geeksforgeeks.org/time-complexities-of-all-sorting-algorithms/ 
  
  https://www.geeksforgeeks.org/heap-sort/ 

 

Dans start : 
  modifier les strategies de descente selon le level; pas uniquement la vitesse mais aussi les directions 

level:
  Modifier le nbre d'alien qui descende 
  Gerer une tempo au changement de level et afficher next level : le faire fonctionner

Alien
  Faire un design d'explosion sur set_crash
  Alien projectile à partir niveau 2 

closition:
  Ameliorer la zone de contact entre alien et bullet, peut etre un pb qd bullet sur le cote gauche (contact qd un peu trop loin d'alien) 

Check collision 

  Ajout des blocs fixe et gerer que les bullets ne puisse pas les traverser et que les aliens se crashent dessus (choisir si impact sur le score ou pas), en fonction des levels : 1 bloc  à partir niveau 3 puis 2 blocs niveau 5 
  
  À une certaine vitesse il faudra bloquer la vitesse de descente sinon cela devient injouable et jouer sur les trajectoires et les blocs 

 
demo:
  Attention au temps de demo (2/3 mn) poura voir le temps de tout montrer, il faut maitriser les tempos et timing de descente 

Commenter le text  
