# GrandinAPK Downloads (public) — instructions pour Codex

## Règle transverse GrandinAPK — coûts GitHub / Termux / Codex (25/10/2026)

**Méthode validée pour tous les projets APK.** Les consignes suivantes s'appliquent aux travaux de Codex et de tout assistant intervenant sur ce dépôt.

1. **Sources privées, distribution publique.** Conserver le code des applications dans les dépôts privés. Utiliser `kgrandin49-star/grandinapk-downloads` uniquement pour les APK de distribution validés et leurs notes de version. Ne pas rendre des sources privées publiques.
2. **Compilation par défaut en local.** Exécuter les tests, Gradle, Capacitor et la génération des APK dans **Termux + Debian/proot** avec le JDK, le SDK Android et les outils déjà configurés. Ne jamais dépendre d'une compilation GitHub Actions pour une mise à jour courante.
3. **Limiter GitHub Actions.** Ne pas ajouter ou réactiver de compilation Android automatique sur `push` ou `pull_request`. Les workflows coûteux doivent rester en `workflow_dispatch` et n'être lancés qu'à la demande expresse du propriétaire. Autoriser seulement des tests automatiques légers, ciblés et justifiés. Éviter matrices de runners, émulateurs systématiques, artefacts temporaires multiples et longues rétentions. Ne pas lancer d'exécution automatique pour contourner un quota atteint.
4. **Signature locale impérative.** Toujours réutiliser le **keystore original de l'application concernée** : `.jks` ou `.p12`, avec son alias et son certificat existants. Ne jamais générer une nouvelle clé pour une mise à jour, ni remplacer la signature par une clé debug. Garder les clés, alias sensibles et mots de passe exclusivement dans l'environnement privé local ; ne jamais les committer, exposer dans les logs ou les transmettre à GitHub.
5. **Contrôles avant diffusion.** Comparer l'`applicationId` / nom du package, un `versionCode` strictement supérieur et l'empreinte **SHA-256 du certificat de signature** avec une APK déjà installée / signée. Utiliser `aapt`, `zipalign` puis `apksigner` lorsque pertinent. Refuser la publication en cas d'écart. Ne jamais désinstaller l'ancienne application pour passer outre une incompatibilité ; préserver comptes, activations, données et sauvegardes.
6. **Publication contrôlée.** Signer sur Termux, vérifier, installer en **mise à jour** et tester sur appareil réel. Publier **manuellement**, après validation explicite, uniquement l'APK finale signée dans une GitHub Release publique. Éviter les artefacts GitHub Actions persistants comme moyen principal de distribution.
7. **Interventions prudentes.** Avant toute mutation, vérifier branche active, historique, workflow déclenché et impact potentiel sur la facturation. Conserver les tests de sécurité. Ne pas supprimer ni refondre des workflows, données, branches, releases ou historiques sans autorisation spécifique. Ne déployer ni Worker Cloudflare, Firebase, D1 ou Apps Script sans validation explicite.
8. **Rapport vérifiable.** Après modification, indiquer clairement les fichiers et branches changés, les tests réellement exécutés, les éléments non vérifiés, les risques résiduels et les prochaines commandes Termux. Ne jamais prétendre qu'une APK a été construite, signée, installée ou publiée si cela n'a pas eu lieu.

**Contexte de coût validé :** GitHub Free avait atteint 2 000 / 2 000 minutes Actions et 0,5 / 0,5 Go de stockage d'artefacts au 25/10/2026. La facturation affichée était 0 $ après remises. Objectif : conserver la formule gratuite sans compromettre la compatibilité des mises à jour.

## Règles spécifiques au dépôt public
- Ce dépôt sert exclusivement de vitrine et de distribution. **Aucune clé privée, fichier `.jks`/`.p12`, secret, mot de passe, token, configuration Firebase privée ni source sensible ne doit être ajouté.**
- Ne publier qu'après validation explicite une APK release déjà compilée, signée et vérifiée localement, avec numéro de version, empreinte SHA-256 de fichier et notes de version correctes.
- Ne pas compiler ou signer depuis ce dépôt public ; ne pas ajouter de workflow coûteux.
- Ne pas remplacer ou supprimer les APK/releases déjà publiés sans accord explicite.
