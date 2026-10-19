# Révise ton collège — V12 (Android)

## Informations de version
- Application : Révise ton collège (anciennement « Révise ta 5e »).
- Version : 8.3-college, `versionCode 12`.
- Identifiant Android : `fr.reviseta.cinquieme`.
- Système cible : Android (SDK cible 35).
- Distribution : APK release **signée avec le certificat historique**, en téléchargement depuis la section « Releases ».
- État : V12 installée et déclarée fonctionnelle lors d'un test sur téléphone Android le 19 octobre 2026.

## Nouveautés
- Présentation plus scolaire et adaptée aux collégiens.
- Thèmes « Neutre », « Garçon » et « Fille » ; thème neutre au démarrage.
- Choix de classe dans le parcours de première utilisation.
- Amélioration de l'affichage plein écran Android.
- Conservation des fiches, quiz et autres fonctionnalités de révision existantes.

## Installation et mise à jour
1. Dans les **Releases** de ce dépôt public, télécharger exclusivement le fichier `ReviseTonCollege-v12-SIGNED.apk` de la publication V12.
2. L'ouvrir sur un téléphone Android.
3. Si une ancienne version est installée, choisir **Mettre à jour**, sans désinstaller. Cela exige la même signature d'application.
4. Lancer l'application et, si demandé, suivre le parcours de demande d'activation.

La mise à jour est destinée à préserver les données locales et les activations existantes, sous réserve du comportement Android et de la configuration du téléphone. Une sauvegarde préalable reste conseillée.

**Important :** l'accès aux contenus peut nécessiter une validation d'activation par l'administrateur GrandinAPK. Publier un fichier APK ne supprime pas ce contrôle.

## Sécurité de publication
- Joindre uniquement une APK **signée** et, idéalement, un fichier texte avec son empreinte SHA-256 calculée **sur le fichier signé**.
- Ne jamais publier les fichiers `.jks`, `.p12`, les mots de passe, les scripts de configuration privés, les identifiants Firebase ou les données d'activation.
- Ne pas publier `ReviseTonCollege-v12-UNSIGNED.apk` comme fichier destiné aux utilisateurs.
- Vérifier la signature APK avant diffusion : `apksigner verify --verbose --print-certs ReviseTonCollege-v12-SIGNED.apk`.
- Empreinte SHA-256 du **certificat public** historique de Révise : `c866aa7ce79b82adaf68727858d32ec16d6cfc3e0b953ae2f911fd4dd49fc50b`.
- L'empreinte SHA-256 du **fichier APK signé** est différente de celle du certificat et doit être calculée sur le binaire définitif.

Page des publications : https://github.com/kgrandin49-star/grandinapk-downloads/releases

---

Document public de préparation à la diffusion — 19 octobre 2026. Cette notice ne signifie pas à elle seule que le fichier APK signé est déjà attaché à une Release.
