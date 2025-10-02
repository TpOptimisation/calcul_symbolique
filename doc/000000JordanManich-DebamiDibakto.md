Entropie Croisée Catégorielle
Description

Ce projet explore l’entropie croisée catégorielle en utilisant Python et SymPy. Il combine la théorie et la visualisation graphique pour illustrer :

Les gradients et la Hessienne (convexité) de l’entropie croisée.

La représentation graphique de la fonction de perte pour un exemple de classification.

La tangente à une ellipse pour deux variables explicatives.

L’application sur deux petits jeux de données :

Iris : classification (2 attributs, 50 observations).

Wine Quality : régression (2 attributs, 50 observations).

Structure du Notebook

Import des bibliothèques : Pandas, NumPy, SymPy, Matplotlib.

Chargement des jeux de données : Iris et Wine Quality.

Calcul du gradient et de la Hessienne de l’entropie croisée.

Étude de convexité via la Hessienne.

Visualisation des courbes de l’entropie croisée pour des observations.

Tangente à une ellipse pour visualiser la relation entre deux variables.

Visualisation finale : ellipse et tangente tracées, courbes de perte pour toutes les observations Iris.

Comment utiliser

Cloner le dépôt ou télécharger le notebook.

Placer les fichiers de données :

iris.data dans ./data/iris/

winequality-red.csv dans ./data/wine+quality/

Ouvrir le notebook avec Jupyter Notebook ou JupyterLab.

Exécuter les cellules dans l’ordre pour observer :

Gradients et Hessienne.

Graphiques de l’entropie croisée.

Tangente sur l’ellipse.
