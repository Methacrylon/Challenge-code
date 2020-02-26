# Score de bowling

[Lien de la vidéo de présentation](https://youtu.be/99EPKQn92ok)

## Objectif

Calculer le score de bowling selon le nombre de quilles touchées à chaque lancer.

## Règles de calcul

Pour une frame normale, on additionne le résultat de chaque lancer

Pour un spare, on compte 10 pour la frame plus le lancer suivant
Exemple : 
3/ 45
donne 10 + 4 pour le premier et 4 + 5 pour le deuxième, donc 23 en tout.

Pour un strike, on compte 10 plus les deux lancers suivants
Exemple :
X 45
donne 10 + 4 + 5 pour le premier et 4 + 5 pour le deuxième, donc 28 en tout.


## Entrées

Liste des résultats des 10 lancers.

Format : Dans la console, on passe 10 "frames" séparées par un espace.

Exemple : 34 45 3- 4- 5/ X 4/ 3/ 54 32

## Sorties

Score total
