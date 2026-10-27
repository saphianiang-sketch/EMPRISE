# RENAISSANCE — Application web mobile (PWA)

Prototype fonctionnel en français : histoire interactive en cinq chapitres, valorisation, journal privé local, ancrage, pause respiratoire, ressources d'aide.

## Tester sur ordinateur

Dans ce dossier, lancez `python -m http.server 8000` puis ouvrez `http://localhost:8000`.

## Publier gratuitement avec GitHub Pages

1. Créez un compte GitHub et un dépôt **public** (sans y ajouter de données personnelles).
2. Envoyez tous les fichiers du dossier `renaissance-app` à la racine du dépôt.
3. Dans **Settings > Pages**, choisissez **Deploy from a branch**, `main`, `/ (root)` et enregistrez.
4. Attendez la publication puis ouvrez l'URL HTTPS fournie par GitHub Pages.
5. Sur Android, utilisez le menu du navigateur > **Installer l'application** ou **Ajouter à l'écran d'accueil**. Sur iPhone avec Safari, utilisez **Partager > Sur l'écran d'accueil**.

GitHub Pages propose un hébergement statique gratuit pour les dépôts publics admissibles ; conditions susceptibles d'évoluer. Le site est public, mais les notes ne sont pas envoyées au dépôt.

## Confidentialité et limites

Le journal et la progression utilisent `localStorage` : aucune synchronisation, aucun chiffrement applicatif, aucune sauvegarde distante. Ne convient pas au stockage de dossiers médicaux. Effacement possible depuis Confidentialité. L'application n'effectue pas de suivi ni de publicité.

L'application ne constitue ni un dispositif médical validé, ni une thérapie, ni une garantie de guérison. Faire relire les contenus par des spécialistes de l'addictologie avant diffusion large. Vérifier l'exactitude des numéros d'aide et des obligations légales (RGPD, mentions légales, accessibilité, éventuelle réglementation des dispositifs médicaux).

## Mettre à jour

Modifier les fichiers, changer la version `CACHE` dans `sw.js`, puis republier.
