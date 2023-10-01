# TP de découverte de C# et Visual Studio: Hello World !

## Description

Vous allez construire une application graphique dotée d’un unique bouton qui affiche le message « Hello World ! » lorsque l’on clique dessus.

## Contenu

Prise en main de Visual Studio, création d’une application Windows Form, création d’évènements.

## Instructions :

- Commencez par lancer Visual Studio et créez un projet Windows Form.
- La fenêtre que vous obtenez ressemble à cela :


1. L’ensemble des composants disponibles que vous pouvez ajouter à votre projet. 
Il peut s’agir de composants visuels (un bouton) ou non (un timer).

2. La zone de conception, ou vous construisez l’interface graphique et éditez le code source.

3. La zone de débogage : tous les messages de compilateur sont indiqués ici.

4. L’explorateur de solution : tous les fichiers (codes, configurations, ressources, ...) qui composent votre solution.

5. Liste des propriétés (nom, texte, taille, couleur, ...) du composant sélectionné.


> La flèche verte, au milieu en haut, permet de **construire** et **d’exécuter** le projet

> Le petit éclair dans la zone 5 permet d’accéder à tous les évènements (MouseClick, MouseMove,
KeyPressed, Paint, ...) gérés par le composant sélectionné et de définir de nouveaux comportements.


En plus des raccourcis habituels des applications Windows (Copier-Coller,...), Visual Studio propose de nombreux raccourcis dont les deux plus importants sont certainement:
- **Ctrl+Espace** pour la complétion automatique et l’aide en ligne
- **Ctrl + .** pour l'ajout automatique des directives using


- Modifiez les propriétés de l’objet form1 (la fenêtre principale), donnez lui un nouveau nom, une nouvelle couleur de fond, et un nouveau curseur par défaut.

- Ajoutez maintenant un bouton à votre fenêtre.

- Modifiez son nom et appelez le HelloButton, modifiez également le texte affiché dans le bouton.

- Ajoutez un évènement Click à votre bouton (faites un double cliques sur le bouton ou cherchez l’évènement dans la liste des évènements gérés par l’objet) :

- Ajoutez du code dans la fonction <nom_du_composant>_Click pour afficher le message « Hello World ! » 
	(utilisez la méthode statique Show de la classe MessageBox).

- Vérifiez que tout fonctionne bien !