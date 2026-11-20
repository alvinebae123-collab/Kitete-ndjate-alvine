CV Flutter — KITETE NDJATE CHRISTIAN.

Application mobile réalisée avec Flutter et Dart dans le cadre d’un TP universitaire à l’ISIG Goma.

Elle présente quatre espaces : connexion, CV, famille et coordonnées.

Fonctionnalités

* Connexion avec identifiant et mot de passe masqué.
* Présentation du profil, de la formation, des expériences et compétences.
* Présentation des membres de la famille.
* Coordonnées cliquables : téléphone, e-mail et GitHub.
* Navigation avec une barre inférieure (BottomNavigationBar).

Identifiants de démonstration

* Identifiant : alvine
* Mot de passe : 1234

Ces identifiants sont prévus uniquement pour la démonstration du TP. Ils sont codés dans l’application et ne constituent pas une authentification sécurisée.

Prérequis

* Flutter SDK installé et accessible dans le PATH.
* Visual Studio Code avec les extensions Flutter et Dart.
* Git installé.

Installation et lancement

flutter pub get
flutter run

Captures d’écran

Après avoir lancé l’application, réalise une capture de chacune des quatre pages et place les fichiers dans le dossier screenshots/ avec exactement ces noms :

1. Connexion

2. Accueil — CV

3. Famille

4. Contact

Structure du projet

cv_flutter_alvine/
├── assets/
│   └── images/
│       ├── moi.jpg
│       ├── pere.jpg
│       └── mere.jpg
├── lib/
│   └── main.dart
├── screenshots/
│   ├── 01_connexion.png
│   ├── 02_accueil_cv.png
│   ├── 03_famille.png
│   └── 04_contact.png
├── pubspec.yaml
└── README.md

Ajoute les photos personnelles dans assets/images/ :

* moi.jpg : photo de KITETE NDJATE CHRISTIAN.
* pere.jpg : photo de son père.
* mere.jpg : photo de sa mère.

Si les photos ne sont pas encore disponibles, l’application affiche des icônes ou des initiales de remplacement.

Auteur

KITETE NDJATE CHRISTIAN

* Institution : ISIG Goma
* Formation : À compléter
* Année académique : 2026–2027
* Adresse : À compléter
* Téléphone : +243 995033695
* E-mail : alvinebae123@gmail.com
* GitHub : https://github.com/alvinebae123-collab

Dépôt GitHub

Consulter le dépôt du projet CV Flutter
