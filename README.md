# Workshop_dart
Initiation to dart

<h1>Installation des packages Dart</h1>

<h3>Sur Linux</h3>

```sudo dnf install dart-sdk```

<h3>Sur Ubuntu</h3>

```sudo apt install dart```

<h3>Sur MacOS</h3>

```brew install dart-sdk```

<h4>Pour checker l'installation</h4>

```
dart --version
```

<h2>Exemple d'un Hello World</h2>

```
void main() {
  print("Hello, World!");
}
```

```
dart run hello_world.dart
```

```
Hello, World!
```

<h1>Exercices...</h1>

<h2>Exercice 1</h2>

<h3>Affichage simple de chaines de caractères:</h3>
<p>Ecrivez une fonction qui prend en paramètres deux chaines de caractères et les affiche.</p>

<h2>Exercice 2</h2>

<h3>Affichage simple de chaines de caractères par l'intermédiaire d'une classe:</h3>
<p>Ecrivez une fonction qui prend en paramètre une classe contenant deux chaines de caractères et les affiche.</p>

<h2>Exercice 3</h2>

<h3>Affichage de la stdin (entrée standard):</h3>
<p>Ecrivez une fonction permettant de lire l'entrée standard et d'afficher son contenu jusqu'à ce que l'entrée standard contienne "STOP\n"</p>

<h2>Exercice 4</h2>

<h3>Création d'une liste de Int:</h3>
<p>Ecrivez une fonction qui prend en paramètres deux Ints et renvoie une liste contenant les deux parametres.</p>

<h2>Exercice 5</h2>

<h3>Mini Doop:</h3>
<p>Ecrivez une fonction qui prend en paramètres un Int, un opérateur ("/", "-", "+", "*", "%") et un autre Int et renvoie le résultat de cette opération</p>

<h2>Exercice 6</h2>

<h3>Petit avant goût du polymorphisme:</h3>

<h4>Petit explication simple du polymorphisme</h4>
<p>Le polymorphisme d'héritage</br>
La possibilité de redéfinir une méthode dans des classes héritant d'une classe de base s'appelle la spécialisation. Il est alors possible d'appeler la méthode d'un objet sans se soucier de son type intrinsèque : il s'agit du polymorphisme d'héritage. Ceci permet de faire abstraction des détails des classes spécialisées d'une famille d'objet, en les masquant par une interface commune (qui est la classe de base).</br>

Imaginons un jeu d'échec comportant des objets roi, reine, fou, cavalier, tour et pion, héritant chacun de l'objet piece.
La méthode mouvement() pourra, grâce au polymorphisme d'héritage, effectuer le mouvement approprié en fonction de la classe de l'objet référencé au moment de l'appel. Cela permettra notamment au programme de dire piece.mouvement sans avoir à se préoccuper de la classe de la pièce.</br></br></p>

<h4>Passons à l'exercice</h4>
<p>Créez une classe Animal contenant une méthode déplacer() et definissez la de facon à ce qu'elle affiche "Je me déplace"</br>
Créez ensuite une classe Dauphin héritant de Animal contenant elle aussi une méthode déplacer() et définnissez la de facon a ce qu'elle affiche "Je nage" et fait de même en construisant une classe Aigle</p>

***N'oubliez pas de bien faire de l'héritage***

<h2>Exercice 7</h2>

<h3>Classe ListeInt</h3>
<p>Créez une classe Liste avec les méthodes suivantes: </br>
sort(liste de ints) : permettant de renvoyer la liste prise en parametre triée dans l'ordre croissant</br>
max(liste de ints) : permettant de renvoyer l'élément le plus grand de la liste</br>
min(liste de ints) : permettant de renvoyer l'élément le plus petit de la liste</p>

<h2>Exercice 8</h2>

<h3>Mastermind</h3>
<p>Ecrivez un programme permettant de reproduire le concept du Mastermind avec des chiffres.</br>
Vous remplacerez donc les six couleurs par 1, 2, 3, 4, 5, 6.</br>
Le joueur qui doit devinner à seulement dix coups pour trouver la combinaison.
</p>

***Ca serait bien de le faire avec des classes***

# ***Fin***
