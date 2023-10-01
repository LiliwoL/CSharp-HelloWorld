# TP de d�couverte de C# et Visual Studio: Hello World !

## Description

Vous allez construire une application graphique dot�e d�un unique bouton qui affiche le message � Hello World ! � lorsque l�on clique dessus.

## Contenu

Prise en main de Visual Studio, cr�ation d�une application Windows Form, cr�ation d��v�nements.

## Instructions :

- Commencez par lancer Visual Studio et cr�ez un projet Windows Form.
- La fen�tre que vous obtenez ressemble � cela :


1. L�ensemble des composants disponibles que vous pouvez ajouter � votre projet. 
Il peut s�agir de composants visuels (un bouton) ou non (un timer).

2. La zone de conception, ou vous construisez l�interface graphique et �ditez le code source.

3. La zone de d�bogage : tous les messages de compilateur sont indiqu�s ici.

4. L�explorateur de solution : tous les fichiers (codes, configurations, ressources, ...) qui composent votre solution.

5. Liste des propri�t�s (nom, texte, taille, couleur, ...) du composant s�lectionn�.


> La fl�che verte, au milieu en haut, permet de **construire** et **d�ex�cuter** le projet

> Le petit �clair dans la zone 5 permet d�acc�der � tous les �v�nements (MouseClick, MouseMove,
KeyPressed, Paint, ...) g�r�s par le composant s�lectionn� et de d�finir de nouveaux comportements.


En plus des raccourcis habituels des applications Windows (Copier-Coller,...), Visual Studio propose de nombreux raccourcis dont les deux plus importants sont certainement:
- **Ctrl+Espace** pour la compl�tion automatique et l�aide en ligne
- **Ctrl + .** pour l'ajout automatique des directives using


- Modifiez les propri�t�s de l�objet form1 (la fen�tre principale), donnez lui un nouveau nom, une nouvelle couleur de fond, et un nouveau curseur par d�faut.

- Ajoutez maintenant un bouton � votre fen�tre.

- Modifiez son nom et appelez le HelloButton, modifiez �galement le texte affich� dans le bouton.

- Ajoutez un �v�nement Click � votre bouton (faites un double cliques sur le bouton ou cherchez l��v�nement dans la liste des �v�nements g�r�s par l�objet) :

- Ajoutez du code dans la fonction <nom_du_composant>_Click pour afficher le message � Hello World ! � 
	(utilisez la m�thode statique Show de la classe MessageBox).

- V�rifiez que tout fonctionne bien !