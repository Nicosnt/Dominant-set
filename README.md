# Dominant-set

Ce m´emoire porte sur l’analyse et l’impl´ementation des m´ethodes propos´ees par le papier suivant : A New Graph-Theoretic Approach to Clustering and Segmentation publié par Massimiliano Pavan et Marcello Pelillo à l’occasion de la Conference on Computer Vision and Pattern Recognition en 2003.

Il s’agit d’une méthode issue de la théorie des graphes qui généralise la notion de clique maximale aux graphes pondérés. Elle est utilisée pour trouver un sous-ensemble compact, cohérent et bien séparé de sommets dans un graphe, c’est-à-dire un ensemble dominant (Dominant Set).




Le code Weight.mlx code permet de calculer les poids de tout sous ensemble de cardinal n rentré en paramètre

la fonction weight prend en entrée 2 éléments : 
1. la matrice d'adjacence du graphe
2. le cardinal du sous-ensemble à considérer

la fonction weight renvoit les éléments suivant pour chaque sous-ensemble de cardinal n choisi :

- subset : le sous-ensemble considéré (la première colonne correspond aux relations du sommet 1 aux autres, la colonne 2 du sommet 2 etc...)
- W(S) : le poids total du sous-ensemble
- w_S(i) : le poids relatif du sommet i par rapport au sous-ensemble pour tout élément de ce sous-ensemble
