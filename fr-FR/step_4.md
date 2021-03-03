## Garder la trace des échecs

Ajoutons du code pour garder une trace des échecs.

+ Tu vas ajouter 1 à la variable `echec` chaque fois qu'une connexion est faite sur la broche P0. Pour cela, prend un bloc `lorsque la broche P0 est activée` dans « Entrées ».

![capture d'écran](images/frustration-pressPin0.png)

+ Ensuite, ajoute 2 blocs pour afficher une croix pendant 1 seconde lorsque la broche P0 est activée.

![capture d’écran](images/frustration-pin0-x.png)

+ Tu devras ensuite ajouter 1 à la variable `echecs`. Pour cela, prend un bloc `modifier objet de 1` dans « Variables » et remplace `objet` par `echecs`. 

![capture d'écran](images/frustration-pin0-fails.png)

+ Enfin, tu peux ajouter du code pour afficher le nombre d'échecs mis à jour. Voici à quoi devrait ressembler ton code.

![capture d'écran](images/frustration-pin0-code.png)

+ Teste ton code en appuyant sur le bouton A de l'émulateur pour démarrer ton jeu. Chaque fois que tu appuies sur la broche P0, tu devrais voir la variable `echecs` augmenter de 1.

![capture d'écran](images/frustration-pin0-test.png)

+ Clique sur « Télécharger » et transfère ton script sur ton micro:bit. Tu peux appuyer sur la broche P0 en fermant le circuit. Pour cela, place ton pouce droit sur la masse (broche GND) et touche la broche P0 avec ton pouce gauche.

![capture d'écran](images/frustration-pin0-compile.png)