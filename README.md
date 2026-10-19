# The Printing Yassin — site statique

## Mettre en ligne gratuitement avec GitHub Pages
1. Créez un compte sur https://github.com puis cliquez sur **New repository** (nom ex. `site-printing`, visibilité **Public**).
2. Cliquez sur **uploading an existing file**, puis glissez-déposez **tout le contenu de ce dossier** (index.html, les .html, assets/, et tous les dossiers d'images — pas le .zip lui-même). Cliquez sur **Commit changes**.
3. Allez dans **Settings → Pages**. Source : **Deploy from a branch**, branche **main**, dossier **/(root)**, puis **Save**.
4. Après 1 à 2 minutes, le site est disponible sur `https://VOTRE-PSEUDO.github.io/site-printing/`.

Astuce : GitHub est sensible aux majuscules et aux espaces dans les noms de fichiers. Tous les noms ont déjà été normalisés (minuscules, sans accents ni espaces).


Note : le CSS et le JavaScript (panier, devis, thème, numéro WhatsApp) sont intégrés directement dans chaque page .html — il n'y a plus de dossier `assets/`. Pour changer le numéro WhatsApp, cherchez `whatsapp:` dans les fichiers .html.
