
<h1 align="Center">Exercices 01</h1>
<h3 align="Center">2Q2 - Développement Assembleur</h3>

### Lien vers les [notes de cours](https://slides.com/hkoncept/2q2-01/fullscreen?token=njXZpxb5) !

## Contexte

Dans votre dossier `sources` et un sous-dossier au nom de l'exercice (exemple `\sources\exercices01`) créer une copie du template assembleur en le ré-enregistrant selon cette nomentlature `E`[Numéro de l'exercice]`Q`[Numéro de la question]`.ASM` (exemple: `E01Q01.ASM` pour la première question des l'exercices 01).

## Consignes

1. Vous devez **impérativement** utiliser et respecter le [template ASM8086](cshawi.info/bin/2q2/_TEMPLATE.ASM).
2. Toutes les données numériques entières doivent être en hexadécimales minuscules (exemple: `21h`).
3. Les étiquettes doivent être en minuscule et tout le reste en majuscule.
4. Vous devez **obligatoirement** commencer par coder votre solution en C++ dans Visual Studio et le transférer dans votre `.ASM` par la suite. Enfin vous transcoder en ASM8086 tout en conservant une corrélation avec le code `C++`.

## Question 01 - Salutations

Affichez votre prénom et votre nom à l'écran provenant de deux variables différentes nommées `firstname` et `lastname`. Ne placez que votre nom et prénom dans les deux champs, pas d'espaces ni de point d'exclamation !

```plaintext
Cédrik Dubois!
```

## Question 02 - Je père Mute !

1. Déclarer 2 variables entière: x = 8 et y = 5
2. Trouver une façon pour interchanger (permuter) le contenu des 2 variables de façon dynamique (c'est-à-dire qui s'adaptera et fonctionnera peu importe les valeurs initiales de x et y).
3. Afficher les résultats AVANT et APRÈS la permutation. Par exemple, en console, on devrait voir:

```
Avant permutation x = 5 et y = 8
Après permutation x = 8 et y = 5
```

ATTENTION: Cela doit fonctionner quand même avec d'autres valeurs sans rien changer d'autre que les valeurs elles-mêmes.

<p align="Center"><img src="./images/end.png" alt="drawing" width="150"/></p>
