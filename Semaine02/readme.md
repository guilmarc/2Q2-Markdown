<h1 align="Center">Exercices 02</h1>
<h3 align="Center">2Q2 - Développement Assembleur</h3>

### Lien vers les [notes de cours](https://slides.com/hkoncept/2q2-02?token=f6QnjBgl) !

## Contexte

Dans votre dossier `sources` et un sous-dossier au nom de l'exercice (exemple `\sources\exercices02`) créer une copie du template assembleur en le ré-enregistrant selon cette nomentlature `E`[Numéro de l'exercice]`Q`[Numéro de la question]`.ASM` (exemple: `E02Q01.ASM` pour la première question des l'exercices 02).

## Consignes

1. Vous devez **impérativement** utiliser et respecter le [template ASM8086](cshawi.info/bin/2q2/_TEMPLATE.ASM).
2. Toutes les données numériques entières doivent être en hexadécimales minuscules (exemple: `21h`).
3. Les étiquettes doivent être en minuscule et tout le reste en majuscule.
4. Vous devez **obligatoirement** commencer par coder votre solution en C++ dans Visual Studio et le transférer dans votre `.ASM` par la suite. Enfin vous transcoder en ASM8086 tout en conservant une corrélation avec le code `C++`.

## Question 01 - ASCII

Créer deux variables x=5 et y=9. Calculer la différence entre y et x et affichez la réponse à l'écran.

```plaintext
4
```

## Question 02 - Jump! Jump!

Reproduire ce code C++ en assembleur et le faire rouler avec 85 comme note tout comme 50.

```cpp
int seuil = 60;
int note = 85;
string message ="Vous avez avez obtenu un";
string succes = "succes"
string echec = "echec";
cout << message << " ";
if(note >= seuil) {
   cout << reussite;
} else {
   cout << echec;
}
cout << "!";
```

```plaintext
Vous avez avez obtenu un succes!
```

```plaintext
Vous avez avez obtenu un echec!
```

## Question 03 - Mr. Alpha Baitte

Écrivez l'alphabet à l'écran comme suit en affichant les caractères un à la fois :

> Interdit d'utiliser l'interruption DOS 09h.

```plaintext
AaBbCcDdEeFfGgHhIiJjKkLlMmNnOoPpQqRrSsTtUuVvWwXxYyZz
```

> Utilisez le moins de ligne de code que possible !

## Question 04 - Pablo Picasso del Shawinigan

Recréez simplement ce dessin à l'écran :

```plaintext
**********
*********
********
*******
******
*****
****
***
**
*
```

## DÉFI Question 05 - Citations célèbres

Élaborer un algorithme qui demandera une citation à l'utilisateur ainsi qu'un caractère précis et qui comptera le nombre d'occurence de ce caractère dans la citation.

> Considérer les caractères accentués comme des caractères différents.

```plaintext
Entrez votre citation célèbre : Vis chaque jour comme si c’était le dernier
Entrez une lettre à évaluer : e
Il y a 5 e dans la citation "Vis chaque jour comme si c’était le dernier"
```

<p align="Center"><img src="./images/end.png" alt="drawing" width="150"/></p>
