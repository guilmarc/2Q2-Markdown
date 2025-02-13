<p align="Center"><img src="../includes/logo.png" alt="drawing" width="150"/></p>
<h3 align="Center">2Q2 - Développement Assembleur</h3>

# Exercices 04 - Les fichiers

<!--#
#### 📝 Lien vers les [notes de cours](https://slides.com/hkoncept/2q2-04/fullscreen?token=LZDfz3yW) !
-->

#### 📁 [Structures de projets & consignes à suivre](../includes/rules.md)

## 🔂 Question 01 - Pet pis répète...

L'idée est de créer un fichier nommé `repete.dat` et d'y inscrire `Pet pis répète s'en vont en bateau...`. Le texte doit se répéter dans le fichier, autant de fois que vous lancerez l'algorithme fonctionnel.

Exemple, après 5 lancements de l'algorithme sans supprimer le fichier `repete.dat` ce dernier contiendra :

```plaintext
Pet pis répète s'en vont en bateau...
Pet pis répète s'en vont en bateau...
Pet pis répète s'en vont en bateau...
Pet pis répète s'en vont en bateau...
Pet pis répète s'en vont en bateau...
```

## 🔂 Question 02 🔂 - ...s'en vont en bateau !

Affichez le contenu du fichier `repete.dat` à l'écran en tenant compte du cas où le fichier serait absent (gestion des erreurs):

```plaintext
Pet pis répète s'en vont en bateau !
Pet pis répète s'en vont en bateau !
Pet pis répète s'en vont en bateau !
Pet pis répète s'en vont en bateau !
Pet pis répète s'en vont en bateau !
```

Dans le cas où le fichier n'existe pas:

```plaintext
Impossible d'ouvrir le fichier repete.dat
```

## ✅ Question 03 - TFC, The Fabulous Corrector !

Cédrik Dubogue a élaboré un [court rapport](./_bin/report.dat) de projet de développement. Cependant il éprouve certaines difficultés avec sa touche `Caps Lock` et les cases (majuscule et minuscules) sont passablement amochées.

Une chance que tu es apte à lui générer automatiquement une version corrigée `report.txt` grâce à ton super algorithme de correction.

## 💻 Question 04 - Atlas Informatique

La compagnie **Atlas Informatique** a besoin de vos talents pour créer un algorithme de recherche. Ils souhaitent être en mesure d'afficher les détails sur leurs [produits](./_bin/products.dat). Les clients entreront un code de produit et les détails de ce dernier s'afficheront à l'écran. L'algorithme n'aura pas de fin, dès que l'information d'un produit est à l'écran, l'utilisateur devra être en mesure d'entrer un nouveau code.

```
ATLAS INFORMATIQUE

Code de produit : 336635

Western Digital - WD Black SN850 1To
Un choix parfait pour les gamers recherchant fluidité et rapidité.
1799.36$

Code de produit : 488884

Produit non trouvé !

Code de produit : 584780

Apple - MacBook Air M2
Une combinaison parfaite entre puissance et efficacité énergétique.
220.68$

; ...

```

## 💻 _DÉFI_ Question 05 - Atlas Informatique <img src="../includes/logo.png" alt="drawing" width="20"/><img src="../includes/logo.png" alt="drawing" width="20"/><img src="../includes/logo.png" alt="drawing" width="20"/><img src="../includes/logo.png" alt="drawing" width="20" style="filter: grayscale(1);"><img src="../includes/logo.png" alt="drawing" width="20" style="filter: grayscale(1);"/>

**Atlas Informatique** a bien aimé votre logiciel de recherche de produits et souhaite maintenant que les produits ne défilent plus un par-dessus l'autre. Autrement dit, l'écran doit demeurer fixe.

```
ATLAS INFORMATIQUE

Code de produit : 336635

Western Digital - WD Black SN850 1To
Un choix parfait pour les gamers recherchant fluidité et rapidité.
1799.36$
```

...autre recherche :

```
ATLAS INFORMATIQUE

Code de produit : 584780

Apple - MacBook Air M2
Une combinaison parfaite entre puissance et efficacité énergétique.
220.68$
```

...autre recherche :

```
ATLAS INFORMATIQUE

Code de produit : 488884

Produit non trouvé !
```

💲 Un point bonus dans la session sera octroyé aux 5 premiers étudiants qui présenteront **en personne** une solution fonctionnelle à cette demande client.

<hr><p align="Center"><img src="./images/end.png" alt="drawing" width="150"/></p>
