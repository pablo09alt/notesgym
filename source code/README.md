# NotesGym - Code Source Reconstruit

Ce dossier contient le code source reconstruit à partir de l'APK **NotesGym v2.0 (latest)**. Le projet est organisé pour être importé dans Android Studio et recompilé.

---

## Structure du projet
```
source code/
├── app/
│   ├── src/               # Code source (Java/Kotlin)
│   ├── res/               # Ressources (layouts, images, chaînes)
│   └── AndroidManifest.xml # Manifest Android
├── libs/                  # Bibliothèques externes
├── build.gradle           # Configuration Gradle
└── README.md              # Documentation
```

---

## Prérequis
- [Android Studio](https://developer.android.com/studio) (version 2022.3+)
- [Java JDK 17+](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html)

---

## Fonctionnalités clés
- Calcul des moyennes et "dream grade" (note rêvée).
- Menu hamburger activable/désactivable.
- Export des notes en CSV.
- Recherche de notes par nom.

---

## Comment recompiler
1. Ouvrir le projet dans Android Studio.
2. Synchroniser Gradle (`File > Sync Project with Gradle Files`).
3. Construire l'APK (`Build > Build Bundle(s) / APK(s) > Build APK`).

---

## Dépendances
Le projet utilise les bibliothèques suivantes (à ajouter dans `build.gradle`) :
- Room (pour la base de données locale)
- Retrofit (pour les appels réseau, si applicable)
- Material Components (pour le design)

---

## Personnalisation
- **Design** : Modifie les fichiers dans `res/` pour adapter les couleurs (ex: tons beiges, style sobre).
- **Fonctionnalités** : Ajoute des modules dans `src/` (ex: synchronisation avec Meilisearch, intégration domotique).

---

## Notes
- Le code est commenté pour faciliter la compréhension.
- Pour toute question ou amélioration, contacte [Pablo S.](https://github.com/pablo09alt).