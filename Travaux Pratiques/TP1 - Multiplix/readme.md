<h1 align="Center">TP1 - Multiplix</h1>
<h3 align="Center">2Q2 - Développement Assembleur</h3>

## Contexte

Dans votre dossier `sources` et un sous-dossier au nom de l'exercice (exemple `\sources\tp1`) créer une copie du template assembleur en le ré-enregistrant selon au nom de `tp1.asm`.

Pour la remise vous compressez le dossier `tp1` et placez le `.zip` sur Omnivox.

## Consignes

1. Vous devez **impérativement** utiliser et respecter le [template ASM8086](cshawi.info/bin/2q2/_TEMPLATE.ASM).
2. Toutes les données numériques entières doivent être en hexadécimales minuscules (exemple: `21h`).
3. Les étiquettes doivent être en minuscule et tout le reste en majuscule.
4. Vous devez **obligatoirement** commencer par coder votre solution en C++. Vous devez diviser votre algorithme pour n'obtenir qu'une seule instruction par ligne. Enfin vous transcodez en `ASM8086` tout en conservant une **corrélation** avec le code `C++` que vous placerez **obligatoirement** en commentaire dans le fichier assembleur.

## Multiplix
Vous devez concevoir un algorithme ASM8086 permettant de multiplier deux nombres entre 1 et 100 que vous devrez valider pour enfin afficher le résultat à l'écran.

```plaintext
Entrer un premier nombre entre 1 et 100 : 150
Entrer un premier nombre entre 1 et 100 : 98
Entrer un deuxième nombre entre 1 et 100 : 65
98 x 65 = 6370
```

<p align="Center"><img src="./images/end.png" alt="drawing" width="150"/></p>
