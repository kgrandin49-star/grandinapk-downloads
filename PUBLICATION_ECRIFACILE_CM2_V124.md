# ÉcriFacile · Suite CM2 — V1.2.4 (code 18)

> **Statut : publication de la préversion en préparation.** La notice est publique, mais le fichier APK V1.2.4 signé n'a pas encore été déposé dans une Release. Ne téléchargez pas l'APK non signée du dépôt de développement.

## ÉcriFacile : un cartable numérique accessible sur Android

Application d'aide au travail scolaire de niveau CM2, destinée à simplifier la rédaction, les calculs, l'organisation des documents et le remplissage des fiches distribuées en classe.

### Nouveautés V1.2.4

- **Mon cartable :** grands dossiers visuels par matière, possibilité de créer « Devoirs CM2 » ou d'autres dossiers personnalisés, classement et déplacement des documents sans ouvrir le gestionnaire de fichiers Android.
- **Remplir une fiche :** photographier une feuille ou importer un PDF, placer et déplacer des réponses au clavier dans les espaces vides, puis enregistrer le travail.
- **PDF sur plusieurs pages :** remplir et exporter les pages du document sous forme d'un PDF complet.
- **Cahier numérique :** rétablissement des fenêtres de confirmation des actions destructrices dans Android WebView.
- Conservation des fonctions de rédaction, lecture vocale, numérisation OCR et calcul existantes.

### Validation et limites

- **Tests réels sur Samsung :** saisie dans une fiche, sauvegarde et réouverture, création/déplacement de dossiers, export d'un PDF complété et vérification d'un PDF de deux pages : résultats positifs rapportés lors des essais.
- **Lenovo Tab P11 :** validation sur l'appareil scolaire encore à effectuer.
- Import PDF dans « Remplir une fiche » : **12 pages au maximum** et images cumulées limitées à **10 Mo** pour cette première version.
- Les zones de réponse se positionnent **manuellement**. Détection automatique des trous, annotation au stylet dans l'éditeur de fiches et aide phonétique directement dans ces zones ne sont pas encore intégrées.
- Les PDF exportés sont des documents **aplatis** (réponses visibles), pas des formulaires PDF interactifs.

### Installation et conservation des documents

1. Quand elle sera disponible, télécharger **uniquement l'APK signée** depuis les [Releases officielles GrandinAPK](https://github.com/kgrandin49-star/grandinapk-downloads/releases).
2. Sur l'appareil concerné, effectuer de préférence une **sauvegarde du cartable** avant la mise à jour.
3. Installer par-dessus une précédente version ÉcriFacile **uniquement si le certificat de signature correspond** ; ne pas désinstaller l'ancienne application en cas de conflit.
4. Sur un profil Android supervisé (Family Link), respecter les autorisations du parent et les restrictions d'installation ; l'installation peut nécessiter un contrôle supplémentaire.

Application Android : `fr.ecrifacile.cm2.suitealpha`, version `1.2.4`, `versionCode 18`, Android 11 ou plus récent.

### Activation et confidentialité

ÉcriFacile peut nécessiter une **demande d'activation par e-mail et une validation de l'administrateur GrandinAPK**. Le téléchargement ou l'installation ne vaut pas acceptation de cette demande. Le cartable et les documents scolaires sont conservés dans l'espace privé de l'application sur l'appareil ; ils ne sont pas publiés sur GitHub.

Ne transmettez pas de fiches d'élèves remplies, de captures contenant des données personnelles, de mots de passe ou de clés privées dans les issues publiques.

La publication d'une APK sur GitHub ne signifie pas que le code source privé de l'application est ouvert ou sous licence libre.

### Informations de la future Release

- **Tag prévu :** `ecrifacile-cm2-v1.2.4-test`
- **Nom :** `ÉcriFacile Suite CM2 V1.2.4 — Préversion Android`
- **APK attendue :** `EcriFacile_CM2_v18_SIGNEE.apk` (signée localement avec le certificat d'ÉcriFacile, puis contrôlée avant publication)
- **Fichier de contrôle :** `EcriFacile_CM2_v18_SIGNEE.apk.sha256`
- **Statut GitHub :** cocher « Set as a pre-release » tant que le test Lenovo n'est pas terminé.

**Attention :** cette page ne constitue pas une preuve qu'une APK signée V1.2.4 est publiée. Vérifiez toujours que la Release et ses fichiers sont réellement présents avant de partager un lien de téléchargement.
