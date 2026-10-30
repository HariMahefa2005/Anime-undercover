# Anime Undercover – Multiverse Edition

Projet Android natif minimal (Kotlin + WebView locale), conçu pour être ouvert et compilé avec Android Studio.

## Fonctionnalités incluses
- Jeu local sur un seul téléphone, de 3 à 20 joueurs.
- Distribution secrète des rôles Civil, Undercover et Mr White.
- Personnages associés entre plusieurs univers d'anime.
- Passage du téléphone pour chaque révélation de rôle.
- Manches successives, vote individuel secret, élimination et égalité sans élimination.
- Dernière chance de Mr White pour deviner le personnage civil.
- Détection des conditions de victoire.

## Compiler l'APK avec Android Studio
1. Installe Android Studio sur un ordinateur.
2. Décompresse `AnimeUndercoverAndroid.zip`.
3. Dans Android Studio, choisis **Open** puis sélectionne le dossier `AnimeUndercoverAndroid`.
4. Laisse Gradle synchroniser le projet. Si Android Studio propose d'installer Android SDK 35, accepte.
5. Choisis **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
6. À la fin, clique sur **locate**. L'APK debug se trouve normalement dans `app/build/outputs/apk/debug/app-debug.apk`.
7. Transfère `app-debug.apk` sur ton téléphone et ouvre-le pour l'installer. Android peut demander d'autoriser l'installation depuis cette source.

## Configuration technique
- Android Gradle Plugin : 8.7.3
- Compile SDK : 35
- Minimum Android : 6.0 (API 23)
- JDK : 17 recommandé

## Notes
- Le jeu fonctionne hors ligne : les personnages et le moteur de jeu sont intégrés dans l'application.
- Le verrouillage de capture d'écran est activé pendant le jeu pour protéger les rôles secrets.
- Le contenu de la base de personnages est une première sélection extensible ; elle ne contient pas encore les 300–500 personnages envisagés.
- Cette livraison est le projet source prêt à compiler, pas un APK déjà compilé.
