<p align="Center"><img src="../../includes/logo.png" alt="drawing" width="150"/></p>
<h3 align="Center">2Q2 - Développement Assembleur - TP3 (5%)</h3>

## 🪵 The Fabulous Logger !

Vous avez été embauché par **Infologique Inc.** afin de vous occuper de l'assurance qualité de l'application web **RétroAction**. Vous êtes responsable de créer une mini-application qui servira à sauvegarder les erreurs survenues dans le système dans un fichier `log.dat`, comme dans l'exemple suivant :

#### Contenu du fichier `log.dat`

```plaintext
#1001 - 2025-05-02 à 11h35.20 : Redémarrage complet du système.
#1002 - 2025-05-05 à 11h30.00 : Mot de passe mal validé.
#1003 - 2025-05-05 à 11h30.01 : Ouverture de la page de profil ne fonctionne pas.
```

#### Visuel de l'application :

```plaintext
************************
*      RétroAction     *
************************
Incident #1001 : Redémarrage complet du système.

Incident enregistré, appuyez sur une touche pour continuer...
```

...fermeture de l'application

Ouverture de l'application 3 jours plus tard...

```plaintext
************************
*      RétroAction     *
************************
Incident #1002 : Mot de passe mal validé

Incident enregistré, appuyez sur une touche pour continuer...
```

```plaintext
************************
*      RétroAction     *
************************
Incident #1003 : Ouverture de la page de profil ne fonctionne pas

Incident enregistré, appuyez sur une touche pour continuer...
```

> ATTENTION: Il serait peut-être aidant de créer également un fichier `log.sys`, non ?

<p align="Center"><img src="./images/end.png" alt="drawing" width="150"/></p>
