# leJeuDuPendu

Le célébre jeu du pendu réalisé en C

## Régles du jeu
Le Pendu est un jeu consistant à trouver un mot en devinant quelles sont les lettres qui le composent.

Par exemple, admettons que le mot à découvrir est le mot `MAISON`.
Pour jouer, vous allez proposer à l'ordinateur une lettre. L'ordinateur va ensuite vérifier si cette lettre est contenue dans le mot caché.
À partir de là, deux possibilités :

- la lettre se trouve effectivement dans le mot : dans ce cas, on dévoile le mot avec les lettres qu'on a déjà trouvées ;

- la lettre ne se trouve pas dans le mot : on indique au joueur que la lettre ne s'y trouve pas et on diminue le nombre de coups restants. Quand il ne nous reste plus de coups (0 coup), le jeu est terminé et on a perdu.

## Le code
Plusieurs fichiers sont contenus dans ce répertoire :

- pendu.c : le code correspondant au jeu
- dico.c : le code permettant de donner un mot au hasard pour débuter le jeu
- dico.txt : une liste de mot
