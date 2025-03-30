<p align="Center"><img src="../includes/logo.png" alt="drawing" width="150"/></p>
<h3 align="Center">2Q2 - Développement Assembleur</h3>

# Exercices 05 - Les procédures

#### 📝 Lien vers les [notes de cours](https://slides.com/hkoncept/2q2-05/fullscreen?token=3QPss-cZ) !

#### 📁 [Structures de projets & consignes à suivre](../includes/rules.md)

## 🔁 Question 01 - Le père Mute va mieux !

<p align="Center"><img src="./images/monk.jpg" alt="drawing" width="250"/></p>
Reprendre la question 01 des exercices 01, (Le père Mute) et créez un algorithme très court qui permet de permuter les valeurs réelles de deux variables en mémoire. Codez l'affichage des valeurs de x et de y dans une procdure réutilisable.

```
Avant permutation x = 3 et y = 9
Après permutation x = 9 et y = 3
```

## 🚀 Question 02 - La NASA

<p align="Center"><img src="./images/nasa.webp" alt="drawing" width="150"/></p>
La NASA vous a octroyé un contrat de programmation d'une procédure d'affichage du décompte pré-lancement d'une fusée. Cette procédure doit afficher `Attention: X`, où X est le chiffre passé en paramètre (en 'int'). La procédure affichera `Décollage !!!` lorsque le chiffre passé en paramètre sera de zéro (0).

```
Attention: 9
Attention: 8
Attention: 7
Attention: 6
Attention: 5
Attention: 4
Attention: 3
Attention: 2
Attention: 1
Décollage !!!
```

## Question 03 - La NASA (dont vous êtes le héros) !

<p align="Center"><img src="./images/heros.webp" alt="drawing" width="100"/></p>

> Si vous avez créé trois procédures au total à la question 02, allez directement à la question 04 !

Le directeur de la NASA est très satisfait de votre travail avec eux mais il vous demande de faire une copie de votre précédent projet et maintenant de le faire fonctionner avec 3 procédures :

1. `print_warning` : "Afficher l'avertissement".
2. `char2db` : "Convertir un char en byte".
3. `db2char` : "Convertir un byte en char".

## 🔄 Question 05 - FibonaLoop

<p align="Center"><img src="./images/fibonacci.jpg" alt="drawing" width="150"/></p>
Utilisant des procédures de la question précédente, demandez un nombre à l'utilisateur et affichez ce nombre d'éléments de la suite de Fibonacci en utilisant une procédure `fibonacci`.

```plaintext
Entrez un nombre : 20
Fibonacci #20 = 6765
```

## 🦺 Question 06 - FibonaSafe

<p align="Center"><img src="./images/safe.png" alt="drawing" width="150"/></p>
Reprennez votre solution de la question précédente et assurez-vous que l'utilisateur entre un nombre dont la réponse est gérable par ASM8086 (16 bits)...

## <img src="../includes/logo.png" alt="drawing" width="20"/> DÉFI - Question 07 - FibonaCursive

<p align="Center"><img src="./images/fibonacci-sequence.jpg" alt="drawing" width="150"/></p>
Utilisant du matériel des questions précédentes, demandez un nombre à l'utilisateur et affichez ce nombre d'éléments de la suite de Fibonacci en utilisant la **méthode récursive**.

```plaintext
Entrez un nombre : 20
Fibonacci #20 = 6765
```

> Un **point bonus** sera octroyé pour tous les étudiants en mesure de venir m'**expliquer** leur solution à ce défi pendant les heures de classe et ce, avant la date de remise.

<hr><p align="Center"><img src="./images/end.png" alt="drawing" width="150"/></p>
