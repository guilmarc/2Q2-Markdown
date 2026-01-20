<p align="Center"><img src="../includes/logo.png" alt="drawing" width="150"/></p>
<h3 align="Center">2Q2 - Développement Assembleur</h3>

# Exercices 01 - Introduction

#### 📁 [Structures de projets & consignes à suivre](../includes/rules.md)

## 7️⃣ Question 01 - Le 7 chanceux

Affichez le chiffre 7 à l'écran.

```plaintext
7
```

## ➕ Question 02 - Registre+

Entrez la valeur 4 dans le registre `AL`.  Additionnez-y la valeur 5 et affichez la somme à l'écran.
> ASTUCE: Pour passer de numérique à ASCII, il faut ajouter la valeur numérique du caractère `0` (30h) au registre à afficher.     
```plaintext
9
```

## ➕ Question 03 - Variables+

Déclarez une variable de type `DB` nommée `number`, initialisée à 2.  Affichez à l'écran la somme de la valeur de `number` et de la valeur 3.     
```plaintext
5
```

## ✖️ Question 04 - Multiplix

Déclarez une variable de type approprié nommée `x`, initialisée à 2 ainsi qu'une variable `y` initialisée à 3.  Affichez à l'écran le produit de `x` et `y`.   
```plaintext
6
```

## % Question 05 - Modulix

Déclarez une variable `x`, initialisée à 25.  Affichez à l'écran le résultat de `x` modulo 6.    
```plaintext
1
```

## 🫡 Question 06 - Salutations

Affichez votre prénom et votre nom à l'écran provenant de deux variables différentes nommées `firstname` et `lastname`. Ne placez que votre nom et prénom dans les deux champs, pas d'espaces ni de point d'exclamation !

```plaintext
Cédrik Dubois!
```

## 🔁 Question 07 - Le père Mute !

1. Déclarer 2 variables entière: x = 8 et y = 5
2. Trouver une façon pour interchanger (permuter) le contenu des 2 variables de façon dynamique (c'est-à-dire qui s'adaptera et fonctionnera peu importe les valeurs initiales de x et y).
3. Afficher les résultats AVANT et APRÈS la permutation. Par exemple, en console, on devrait voir:

```
Avant permutation x = 5 et y = 8
Après permutation x = 8 et y = 5
```

ATTENTION: Cela doit fonctionner quand même avec d'autres valeurs sans rien changer d'autre que les valeurs elles-mêmes.

## 🎫 DÉFI Question 08 - Lotterie

Trouvez une façon d'afficher un chiffre pseudo-aléatoire (entre 0 et 9) à chaque lancement de l'algorithme.

```
6
```

```
1
```

```
8
```

<hr><p align="Center"><img src="../includes/end.png" alt="drawing" width="150"/></p>
