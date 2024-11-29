---
layout: presentation
chapitre: true
package: pkg_autoformation
order: 1
---
## QCM sur Kotlin - Niveau Débutant 

**1. Quel est le type de données qui représente un caractère en Kotlin ?**

(a) Char
(b) Character
(c) String
(d) Byte


**2. Quelle est la syntaxe correcte pour déclarer une variable nommée `age` de type `Int` et lui attribuer la valeur 30 ?**

(a) `var age = 30`
(b) `int age = 30`
(c) `age = 30`
(d) `Int age = 30`


**3. Quelle instruction permet de lire une valeur entière saisie par l'utilisateur et de la stocker dans la variable `nombre` ?**

(a) `nombre = readLine().toInt()`
(b) `nombre = Scanner(System.in).nextInt()`
(c) `nombre = JOptionPane.showInputDialog(null, "Entrez un nombre :")`
(d) `nombre = System.in.read()`


**4. Quelle est la différence entre un opérateur `==` et un opérateur `equals()` en Kotlin ?**

(a) L'opérateur `==` compare les références des objets, tandis que l'opérateur `equals()` compare leur contenu.
(b) L'opérateur `==` ne peut être utilisé que pour les types primitifs, tandis que l'opérateur `equals()` peut être utilisé pour tous les types.
(c) L'opérateur `==` est plus rapide que l'opérateur `equals()`.
(d) Il n'y a pas de différence entre les opérateurs `==` et `equals()` en Kotlin.


**5. Qu'est-ce qu'un bloc `when` en Kotlin ?**

(a) Une structure de contrôle qui permet d'exécuter du code en fonction de la valeur d'une expression.
(b) Une variable spéciale qui peut stocker plusieurs valeurs.
(c) Une instruction qui permet de répéter un bloc de code un certain nombre de fois.
(d) Une fonction qui ne retourne aucune valeur.


**6. Quelle est la syntaxe correcte pour un bloc `when` qui vérifie la valeur de la variable `fruit` et affiche un message différent en fonction de sa valeur ?**

```kotlin
when (fruit) {
    "pomme" -> println("Vous avez choisi une pomme")
    "orange" -> println("Vous avez choisi une orange")
    else -> println("Fruit inconnu")
}
```

**7. Quels sont les éléments clés d'une classe en Kotlin ?**

(a) Propriétés, méthodes, constructeurs
(b) Fonctions, variables, boucles
(c) Conditions, instructions, opérateurs
(d) Packages, imports, classes


**8. Qu'est-ce qu'une liste en Kotlin ?**

(a) Un type de données mutable qui permet de stocker une collection d'éléments ordonnés.
(b) Une variable spéciale qui peut stocker plusieurs valeurs.
(c) Une instruction qui permet de répéter un bloc de code un certain nombre de fois.
(d) Une fonction qui ne retourne aucune valeur.


**9. Quelle est la syntaxe correcte pour créer une liste mutable de type `String` nommée `fruits` et y ajouter des éléments ?**

```kotlin
val fruits = mutableListOf<String>()
fruits.add("pomme")
fruits.add("orange")
fruits.add("banane")
```


**10. Qu'est-ce qu'une boucle `for` en Kotlin ?**

(a) Une structure de contrôle qui permet d'exécuter un bloc de code un certain nombre de fois.
(b) Une variable spéciale qui peut stocker plusieurs valeurs.
(c) Une instruction qui permet de tester une condition et d'exécuter un bloc de code si la condition est vraie.
(d) Une fonction qui ne retourne aucune valeur.


**11. Quelle est la syntaxe correcte pour une boucle `for` traditionnelle qui affiche les nombres de 1 à 10 ?**

```kotlin
for (i in 1..10) {
    println(i)
}
```

**12. Qu'est-ce qu'une boucle `while` en Kotlin ?**

(a) Une structure de contrôle qui permet d'exécuter un bloc de code un certain nombre de fois.
(b) Une variable spéciale qui peut stocker plusieurs valeurs.
(c) Une instruction qui permet de tester une condition et d'exécuter un bloc de code si la condition est vraie.
(d) Une fonction qui ne retourne aucune valeur.


**13. Quelle est la syntaxe correcte pour une boucle `while` qui lit des nombres saisis par l'utilisateur jusqu'à ce qu'un nombre négatif soit entré ?**

```kotlin
var nombre: Int
do {
    nombre = readLine().toInt()
} while (nombre >= 0)
```


**14. Qu'est-ce qu'une fonction en Kotlin ?**

(a) Un bloc de code réutilisable qui peut prendre des paramètres et retourner une valeur.
(b) Une variable spéciale qui peut stocker plusieurs valeurs.
(c) Une instruction qui permet de contrôler le flux d'exécution d'un programme.
(d) Un type de données qui