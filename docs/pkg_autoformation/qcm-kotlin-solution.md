---
layout: presentation
chapitre: true
package: pkg_autoformation
order: 1
---
## QCM sur Kotlin - Niveau Débutant (20 questions avec solutions)

**1. Quel est le type de données qui représente un caractère en Kotlin ?**

(a) Char
(b) Character
(c) String
(d) Byte

**Réponse:** (a) Char

**Explication:** Le type de données `Char` est utilisé pour représenter un seul caractère en Kotlin. Les autres options ne sont pas des types de données appropriés pour représenter un caractère.

**2. Quelle est la syntaxe correcte pour déclarer une variable nommée `age` de type `Int` et lui attribuer la valeur 30 ?**

(a) `var age = 30`
(b) `int age = 30`
(c) `age = 30`
(d) `Int age = 30`

**Réponse:** (a) `var age = 30`

**Explication:** La syntaxe correcte pour déclarer une variable en Kotlin utilise le mot-clé `var` suivi du nom de la variable, du signe égal et de la valeur à attribuer. Le type de la variable peut être spécifié après le nom de la variable, mais ce n'est pas obligatoire si le type peut être déduit de la valeur.

**3. Quelle instruction permet de lire une valeur entière saisie par l'utilisateur et de la stocker dans la variable `nombre` ?**

(a) `nombre = readLine().toInt()`
(b) `nombre = Scanner(System.in).nextInt()`
(c) `nombre = JOptionPane.showInputDialog(null, "Entrez un nombre :")`
(d) `nombre = System.in.read()`

**Réponse:** (a) `nombre = readLine().toInt()`

**Explication:** La fonction `readLine()` permet de lire une ligne de texte saisie par l'utilisateur. La méthode `toInt()` convertit ensuite la chaîne de caractères en un nombre entier et l'affecte à la variable `nombre`.

**4. Quelle est la différence entre un opérateur `==` et un opérateur `equals()` en Kotlin ?**

(a) L'opérateur `==` compare les références des objets, tandis que l'opérateur `equals()` compare leur contenu.
(b) L'opérateur `==` ne peut être utilisé que pour les types primitifs, tandis que l'opérateur `equals()` peut être utilisé pour tous les types.
(c) L'opérateur `==` est plus rapide que l'opérateur `equals()`.
(d) Il n'y a pas de différence entre les opérateurs `==` et `equals()` en Kotlin.

**Réponse:** (a) L'opérateur `==` compare les références des objets, tandis que l'opérateur `equals()` compare leur contenu.

**Explication:** L'opérateur `==` vérifie si deux références pointent vers le même objet en mémoire. L'opérateur `equals()`, en revanche, compare les valeurs des objets, en utilisant la méthode `equals()` implémentée par la classe de l'objet.

**5. Qu'est-ce qu'un bloc `when` en Kotlin ?**

(a) Une structure de contrôle qui permet d'exécuter du code en fonction de la valeur d'une expression.
(b) Une variable spéciale qui peut stocker plusieurs valeurs.
(c) Une instruction qui permet de répéter un bloc de code un certain nombre de fois.
(d) Une fonction qui ne retourne aucune valeur.

**Réponse:** (a) Une structure de contrôle qui permet d'exécuter du code en fonction de la valeur d'une expression.

**Explication:** Un bloc `when` est similaire à une instruction `switch` dans d'autres langages de programmation. Il permet d'évaluer une expression et d'exécuter un bloc de code différent en fonction de la valeur de l'expression.

**6. Quelle est la syntaxe correcte pour un bloc `when` qui vérifie la valeur de la variable `fruit` et affiche un message différent en fonction de sa valeur ?**

```kotlin
when (fruit) {
    "pomme" -> println("Vous avez choisi une pomme")
    "orange" -> println("Vous avez choisi une orange")
    else -> println("Fruit inconnu")
}
```

**Explication:** Ce bloc `when` évalue la valeur de la variable `fruit`. Si la valeur est "pomme", le code `println("Vous avez choisi une pomme")` est exécuté. Si la valeur est "orange", le code `println("Vous avez choisi une orange")` est exécuté. Sinon, le code `println("Fruit inconnu")` est exécuté.


## QCM sur Kotlin - Niveau Débutant (14 questions avec solutions)

**7. Quels sont les éléments clés d'une classe en Kotlin ?**

(a) Propriétés, méthodes, constructeurs
(b) Fonctions, variables, boucles
(c) Conditions, instructions, opérateurs
(d) Packages, imports, classes

**Réponse:** (a) Propriétés, méthodes, constructeurs

**Explication:** Les éléments clés d'une classe en Kotlin sont :


**8. Qu'est-ce qu'une liste en Kotlin ?**

(a) Un type de données mutable qui permet de stocker une collection d'éléments ordonnés.
(b) Une variable spéciale qui peut stocker plusieurs valeurs.
(c) Une instruction qui permet de répéter un bloc de code un certain nombre de fois.
(d) Une fonction qui ne retourne aucune valeur.

**Réponse:** (a) Un type de données mutable qui permet de stocker une collection d'éléments ordonnés.

**Explication:** Une liste en Kotlin est un type de données mutable qui permet de stocker une collection d'éléments ordonnés. Les listes peuvent être créées à l'aide de la fonction `mutableListOf()` ou `listOf()`.

**9. Quelle est la syntaxe correcte pour créer une liste mutable de type `String` nommée `fruits` et y ajouter des éléments ?**

```kotlin
val fruits = mutableListOf<String>()
fruits.add("pomme")
fruits.add("orange")
fruits.add("banane")
```

**Explication:** Cette syntaxe utilise la fonction `mutableListOf()` pour créer une liste mutable de type `String` nommée `fruits`. Ensuite, la méthode `add()` est utilisée pour ajouter des éléments à la liste.

**10. Qu'est-ce qu'une boucle `for` en Kotlin ?**

(a) Une structure de contrôle qui permet d'exécuter un bloc de code un certain nombre de fois.
(b) Une variable spéciale qui peut stocker plusieurs valeurs.
(c) Une instruction qui permet de tester une condition et d'exécuter un bloc de code si la condition est vraie.
(d) Une fonction qui ne retourne aucune valeur.

**Réponse:** (a) Une structure de contrôle qui permet d'exécuter un bloc de code un certain nombre de fois.

**Explication:** Une boucle `for` en Kotlin permet d'exécuter un bloc de code un certain nombre de fois. Il existe deux types de boucles `for` en Kotlin : la boucle `for` traditionnelle et la boucle `for` sur une plage.

**11. Quelle est la syntaxe correcte pour une boucle `for` traditionnelle qui affiche les nombres de 1 à 10 ?**

```kotlin
for (i in 1..10) {
    println(i)
}
```

**Explication:** Cette boucle `for` utilise la plage `1..10` pour définir les valeurs de la variable `i`. La variable `i` prend chaque valeur de la plage de 1 à 10, et le code dans le bloc de la boucle est exécuté pour chaque valeur.

**12. Qu'est-ce qu'une boucle `while` en Kotlin ?**

(a) Une structure de contrôle qui permet d'exécuter un bloc de code un certain nombre de fois.
(b) Une variable spéciale qui peut stocker plusieurs valeurs.
(c) Une instruction qui permet de tester une condition et d'exécuter un bloc de code si la condition est vraie.
(d) Une fonction qui ne retourne aucune valeur.

**Réponse:** (c) Une instruction qui permet de tester une condition et d'exécuter un bloc de code si la condition est vraie.

**Explication:** Une boucle `while` en Kotlin permet d'exécuter un bloc de code tant qu'une condition donnée est vraie. La condition est évaluée avant chaque exécution du bloc de la boucle. Si la condition est vraie, le bloc de la boucle est exécuté. Si la condition est fausse, la boucle se termine.

**13. Quelle est la syntaxe correcte pour une boucle `while` qui lit des nombres saisis par l'utilisateur jusqu'à ce qu'un nombre négatif soit entré ?**

```kotlin
var nombre: Int
do {
    nombre = readLine().toInt()
} while (nombre >= 0)
```

**Explication:** Cette boucle `while` lit un nombre entier saisi par l'utilisateur à chaque itération. La condition de la boucle est `nombre >= 0`. Si la condition est vraie, le code dans le bloc de la boucle est exécuté et un nouveau nombre est lu. Si la condition est fausse (c'est-à-dire si un nombre négatif est entré), la boucle se termine.

**14. Qu'est-ce qu'une fonction en Kotlin ?**

(a) Un bloc de code réutilisable qui peut prendre des paramètres et retourner une valeur.
(b) Une variable spéciale qui peut stocker plusieurs valeurs.
(c) Une instruction qui permet de contrôler le flux d'exécution d'un programme.
(d) Un type de données qui