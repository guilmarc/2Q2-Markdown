## Structures de projets & consignes à suivre

1. Lire la question et, sur 'papier', réinterpréter la demande en vos mots. Exemple: _Je dois générer des mots de passe aléatoirement_.
2. Décortiquer votre idée générale en 3 à 5 sections afin de simplifier l'écriture du _pseudo-code_ en C++.
   1. LECTURE: Demander la taille du mot de passe à l'utilisateur.
   2. GÉNÉRATION: Créer le mot de passe aléatoire en utilisant l'horloge.
   3. AFFICHAGE: Afficher le mot de passe à l'écran.
3. Dans votre solution C++ nommée `2Q2-Solutions`, un projet `ExercicesXX` et un fichier `main.cpp`, écrire votre algorithme dans une fonction `void questionXX()`. Afin d'être en mesure de faire la corrélation avec ASM8086, n'écrire qu'une seule instruction C++ par ligne.
   - Exemple, ce code :
   ```cpp
   cout << "Impossible d'ouvrir le fichier " << FILENAME << "!";
   ```
   - Deviendra :
   ```cpp
   const string message = "Impossible d'ouvrir le fichier ";
   //...
   cout << message;
   cout << FILENAME;
   cout << "!";
   ```
4. Dans votre dossier `sources` et un sous-dossier au nom de l'exercice (exemple `\sources\exercices01`) créer une copie de la dernière version du [template ASM8086](https://www.cshawi.info/2q2.html#t4) en le réenregistrant selon cette nomenclature `E`[Numéro de l'exercice]`Q`[Numéro de la question]`.ASM` (exemple: `E01Q02.ASM` pour la deuxième question de l'exercices 01).
5. Transcrire votre _pseudo-code_ C++ en ASM8086 et y ajouter le C++ en prenant bien soin de conserver une corrélation ligne par ligne (autant que possible).
   - Les variables ainsi que les procédures doivent être codées dans la section appropriée.
   - Toutes les données numériques entières doivent être en hexadécimales minuscules (exemple: `30` devriendra `21h`).
   - Les étiquettes doivent être en minuscules et tout le reste en majuscule.
   - Les instructions, commentaires et le code C++ doivent débuter **exactement** sur la colonne telle qu'indiquée en haut du _template_.
6. Une fois toutes les solutions élaborées, copiez votre _pseudo-code_ C++ `main.cpp` dans le dossier de l'exercice et compressez ce dossier en format `.zip` pour finalement le déposer sur Omnivox.
