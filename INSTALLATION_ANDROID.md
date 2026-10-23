# Installer les applications GrandinAPK sur Android

Ce guide est destiné aux utilisateurs de **Révise ton collège**, **Suivi de chantier** et **ÉcriFacile Suite CM2**. Aucun ordinateur n'est nécessaire.

> **Important :** installer une application ne donne pas automatiquement accès à son contenu. **Une validation par e-mail et l'autorisation de l'administrateur GrandinAPK sont nécessaires.**

## 1. Télécharger l'application

1. Depuis le téléphone ou la tablette Android sur lequel vous voulez installer l'application, ouvrez la page officielle : [GrandinAPK — Releases](https://github.com/kgrandin49-star/grandinapk-downloads/releases).
2. Choisissez la version publiée la plus récente.
3. Ouvrez la section **Assets / Ressources**.
4. Téléchargez **uniquement le fichier `.apk` signé** correspondant à votre application.
5. Attendez la fin du téléchargement.

Les applications prévues sont :

| Application | Version disponible | Nom du fichier de publication |
|---|---|---|
| **Révise ton collège** | **V12 (code 12)** | **`ReviseTonCollege-v12-SIGNED.apk`** |
| Suivi de chantier | 2.2.0 (code 22) | `SuiviDeChantier.apk` |
| ÉcriFacile Suite CM2 | **1.2.4 (code 18), préversion** | `EcriFacile_CM2_v18_SIGNEE.apk` |

**Téléchargements directs :** [Révise ton collège V12](https://github.com/kgrandin49-star/grandinapk-downloads/releases/download/revise-ton-college-v12/ReviseTonCollege-v12-SIGNED.apk) · [ÉcriFacile V1.2.4 — préversion](https://github.com/kgrandin49-star/grandinapk-downloads/releases/download/ecrifacile-cm2-v1.2.4-test/EcriFacile_CM2_v18_SIGNEE.apk) · [Toutes les Releases](https://github.com/kgrandin49-star/grandinapk-downloads/releases).

## 2. Installer le fichier APK

1. Ouvrez **Mes fichiers > Téléchargements**, ou ouvrez la notification de téléchargement.
2. Appuyez sur le fichier `.apk` téléchargé.
3. Si Android affiche « Installation d'applications inconnues » ou « Autoriser depuis cette source », ouvrez les réglages proposés et autorisez **le navigateur ou Mes fichiers** à installer ce fichier.
4. Revenez à l'installation, puis touchez **Installer**.
5. Quand Android confirme l'installation, touchez **Ouvrir**.
6. Après l'installation, vous pouvez **désactiver l'autorisation d'installation depuis cette source** dans les paramètres Android.

Selon le fabricant et la version d'Android, les intitulés peuvent varier. Sur certains appareils, une protection supplémentaire peut demander une confirmation explicite.

## 3. Demander la validation par e-mail

1. Lancez l'application.
2. Suivez les indications de l'écran d'activation, notamment la saisie de votre **adresse e-mail valide**.
3. Envoyez la demande d'activation si l'application le propose.
4. **Attendez l'acceptation par l'administrateur GrandinAPK.** Une demande envoyée n'est pas une demande acceptée.
5. Une fois l'accès autorisé, revenez dans l'application. Utilisez son bouton de vérification d'activation, s'il est affiché, ou relancez l'application.

La procédure exacte et les libellés dépendent de l'application. **Il n'y a pas de validation automatique garantie.**

## 4. Installer une mise à jour

1. Ouvrez les [Releases officielles](https://github.com/kgrandin49-star/grandinapk-downloads/releases).
2. Téléchargez la nouvelle version signée de **la même application**.
3. Ouvrez le fichier et installez-la **par-dessus la version existante**.

**Ne désinstallez pas l'ancienne version avant une mise à jour normale : cela pourrait effacer les données locales.** Les mises à jour exigent notamment que la signature de l'application soit compatible avec celle déjà installée et que la nouvelle version ne soit pas plus ancienne.

Si Android affiche « application non installée », un conflit de signature ou une incompatibilité, **arrêtez-vous** avant toute désinstallation et contactez l'administrateur.

## 5. Problèmes fréquents

**Le fichier téléchargé n'apparaît pas :** vérifiez les téléchargements du navigateur et l'application Mes fichiers.

**Android refuse d'installer :** vérifiez l'autorisation d'installation pour la source utilisée, l'espace disponible et le message exact affiché par Android.

**L'installation signale un conflit avec une version existante :** n'effacez pas l'ancienne application sans avoir vérifié la sauvegarde des données locales.

**L'application reste en attente d'activation :** l'administrateur n'a peut-être pas encore validé la demande. Vérifiez de nouveau après son accord.

**Une erreur apparaît :** transmettez seulement le nom de l'application, sa version, le modèle Android et une capture du message d'erreur. **Ne partagez jamais de mots de passe, codes d'activation ou informations personnelles en public.**

## 6. Sécurité

- Téléchargez uniquement depuis les [Releases du dépôt public officiel](https://github.com/kgrandin49-star/grandinapk-downloads/releases).
- Les fichiers destinés à être installés sont des **APK signées**. Les APK marquées `unsigned` ne sont pas destinées aux utilisateurs.
- Le certificat de signature des premières APK préparées est **GrandinAPK**, avec l'empreinte de certificat SHA-256 suivante :

  `c866aa7ce79b82adaf68727858d32ec16d6cfc3e0b953ae2f911fd4dd49fc50b`

- La **clé privée de signature**, ses **mots de passe**, les identifiants d'administration, les bases d'activation et le code source privé **ne doivent jamais être publiés ici**.
- Le dépôt public sert aux téléchargements et à leur documentation, pas à gérer les demandes d'activation.

---

*Documentation GrandinAPK — mise à jour le 23 octobre 2026. ÉcriFacile V1.2.4 est disponible en préversion signée.*
