## TODO

* Faire la partie 2 avec les scaler sur methode supervisé

- Tester les les classification en excluant des données sur les battements de coeurs ( données temporel etc..)

- => cela amenera a peut etre définir des modèles avec des nouveaux hyperparamètre

## INFO

Asmae :

prend les 4 mêmes modèles avec les mêmes hyperparmètres pour la partie 3 

=> le but  étant d'optimiser les performance avec l'ACP

( j'utilise le score accuracy car je sais que tu en a besoin dans la partie 3 mais j'ai créé un nouveau score basé sur la matrice de confusion, le score est obtenu en utilisant la fonction "conf_matrix_score", dedans il faut passer en parametre les etiquettes cible et les etiquettes predite (les Y).

Pq : le score lié a la matrice de confusion que j'ai créé permet de mieux mettre en valeur la matrice de confusion comparé a l'accuracy score qui donne juste le pourcentage de bonne prédiction/classification. J'ai utilisé ce score pour améliorer mes modèles (régler les hyperparamètres)
