
<p align="Center"><img src="../includes/logo.png" alt="drawing" width="150"/></p>
<h3 align="Center">2Q2 - Développement Assembleur</h3>

# Exercices 04 - Les fichiers

<!--#
#### 📝 Lien vers les [notes de cours](https://slides.com/hkoncept/2q2-04/fullscreen?token=LZDfz3yW) !
-->

#### 🗄️ [Structures de projets & consignes à suivre](../includes/rules.md)

## 📁 Question 01 - HelloWorld Files !

Créez un fichier nommé `hellofile.txt` et placez-y le texte `Bienvenue dans le monde des fichiers !` en travaillant dans un seul algorithme, le main.

## 🫡 Question 02 - SayHello !

Écrivez un algorithme qui permet d'afficher à la console le contenu du fichier `hellofile.txt` créé à la question 01.

```plaintext
Bienvenue dans le monde des fichiers !
```

## ⚙️ Question 03 - HelloProc

Transformez votre solution de la question 01 en respectant cette structure :
| # | Procédure | Rôle | Entrées | Sortie |
|---|-----------|------------------------------------------------------------|----------------------------------------------------------|-------------------|
| 1 | openfile | Ouvrir un fichier pour écriture et fournir le handle | - Adresse du nom du fichier - Espace mémoire pour le handle | handle du fichier |
| 2 | writemsg | Écrire, un à un, une chaîne de caractères dans un fichier jusqu'au caractère `$` | - handle du fichier - Adresse du message à écrire | aucune |

> ATTENTION : Seules les instructions `PUSH`, `POP` et `CALL` sont permises dans le main.

### Information complémentaire

Les instructions `LEA` et `OFFSET` effectuent sensiblement le même travail. Elles chargent dans un registre ou sur la pile l'**adresse** mémoire de la cible.

#### Pousser sur la pile l'adresse d'une variable `msg`

```plaintext
LEA DX, msg
PUSH DX
```

équivaut à

```
PUSH OFFSET msg
```

> Il ne faut pas refaire un `LEA` si ce que vous lisez est déjà une adresse mémoire, mais utiliser `MOV`.

<hr><p align="Center"><img src="./images/end.png" alt="drawing" width="150"/></p>
