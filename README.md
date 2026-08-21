# Site vitrine BonApp!

Le site public de [bon-app.info](https://bon-app.info) — pages statiques
autonomes, sans dépendance externe (styles inclus dans chaque fichier).

- **`index.html`** — page vitrine : contenu, styles, interactions.
- **`confidentialite.html`** — politique de confidentialité.
- **`conditions.html`** — conditions d'utilisation.
- **`suppression-compte.html`** — suppression du compte et des données.
  URL exigée par les magasins d'applications (Google Play, App Store) au
  titre de la suppression de compte : ne pas la renommer ni la retirer.
- **`CNAME`** — domaine personnalisé GitHub Pages.

## Déploiement

GitHub Pages sert la branche `main` à la racine. Chaque commit sur `main`
redéploie automatiquement (workflow « pages build and deployment »).

Mettre à jour : branche `<type>/<slug>` → PR → merge sur `main`.

## Liens

- App (APK Android) : https://github.com/BonApp-QC/bonapp-apk/releases/latest/download/BonApp-latest.apk
- API : https://api.bon-app.info
