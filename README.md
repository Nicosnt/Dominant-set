# Dominant-set

Ce code permet de calculer les poids de tout sous ensemble de cardinal n rentré en paramètre

la fonction weight prend en entrée 2 éléments : 
1. la matrice d'adjacence du graphe
2. le cardinal du sous-ensemble à considérer

la fonction weight renvoit les éléments suivant pour chaque sous-ensemble de cardinal n choisi :

- subset : le sous-ensemble considéré (la première colonne correspond aux relations du sommet 1 aux autres, la colonne 2 du sommet 2 etc...)
- W(S) : le poids total du sous-ensemble
- w_S(i) : le poids relatif du sommet i par rapport au sous-ensemble pour tout élément de ce sous-ensemble
