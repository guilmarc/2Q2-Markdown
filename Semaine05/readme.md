<p align="Center"><img src="../includes/logo.png" alt="drawing" width="150"/></p>
<h3 align="Center">2Q2 - Développement Assembleur</h3>

# Exercices 05 - Les procédures

#### 📝 Lien vers les [notes de cours](https://slides.com/hkoncept/2q2-04/fullscreen?token=3QPss-cZ) !

#### 📁 [Structures de projets & consignes à suivre](../includes/rules.md)

## 🔁 Question 01 - Le père Mute va mieux !

Reprendre la question 01 des exercices 01, (Le père Mute) et créer une procédure nommée `pere_mute` qui permet de permuter les valeurs réelle de deux variables en mémoire.

```
Avant permutation x = 3 et y = 9
Après permutation x = 9 et y = 3
```

> ATTENTION: Cela doit fonctionner quand même avec d'autres chiffres.

## 🙃 Question 02 - Le monde à l'envers PART II

Le vieux sage aimerait maintenant avoir une procédure réutilisable lui permettant de lire les messages du bon côté. Votre algorithme principal devra lancer la lecture des 3 messages un après l'autre conformément à la section **Sortie à l'écran**.

1. Premier message

```
msg1 DB "! elip al resilitu'd elitu siofrap tse lI$"
```

2. Deuxième message

```
msg3 DB "$" ; Je n'ai plus rien à dire alors la fenêtre console ne devrait même pas s'ouvrir avec ce message vide !
```

3. Troisième message

```
msg2 DB "! tnemetiafrap egassem ec eril zeirved suov ,erup tnemiarv tse erudécorp ertov iS$"
```

#### Sortie à l'écran

```plaintext
Il est parfois utile d'utiliser la pile !
Si votre procédure est vraiment pure, vous devriez lire ce message parfaitement !
```

## 🧮 Question 03 - Multiplix Light

Votre mission ici est de permettre à l'utilisateur de multiplier deux chiffres entrés du clavier et de donner la valeur à l'écran en utilisant deux procédures imbriquées (multiplication et affichage du résultat).

```plaintext
Entrer le premier chiffre : 8
Entrer le deuxième chiffre : 9
Votre résultat est : 72
```

#### Consignes

1. Créer une procédure `multiplix` qui s'occupe de multiplier deux caractères numériques transformés en nombre entier grâce à la fonction `ascii2int`.
2. Dans la fonction `multiplix` appelez également la procédure `int2ascii` pour afficher la valeur à l'écran.
   
## 🔁 Question 04 - FibonaLoop
Utilisant des procédures de la question précédente, demander un nombre à l'utilisateur et afficher ce nombre d'éléments de la suite de Fibonacci en utilisant une fonction `fibonacci`.

```plaintext
Entrer un nombre : 30
Fibonacci #30 = 832040
```

## <img src="../includes/logo.png" alt="drawing" width="20"/> DÉFI - Question 05 - FibonaCursive
Utilisant des procédures des questions précédentes, demander un nombre à l'utilisateur et afficher ce nombre d'éléments de la suite de Fibonacci en utilisant la méthode récursive.  Il faudra donc appeler la fonction `fibonacci` dans la fonction `fibonacci`.

```plaintext
Entrer un nombre : 30
Fibonacci #30 = 832040
```
<hr><p align="Center"><img src="./images/end.png" alt="drawing" width="150"/></p>
