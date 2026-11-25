# Arène des Dragons

Jeu de combat au tour par tour dans le navigateur : campagne en cinq chapitres, expédition, épreuves légendaires, équipement, boutiques, duel local à deux sur le même écran.

Tout le jeu tient dans `index.html`. Il n'y a rien à installer ni à compiler.

## Mettre en ligne avec GitHub Pages

1. Dépose `index.html` (et `.nojekyll`) à la racine du dépôt, sur la branche `main`.
2. Dans le dépôt : **Settings → Pages → Build and deployment → Deploy from a branch**, branche `main`, dossier `/ (root)`.
3. Après une à deux minutes, le jeu est à l'adresse `https://<ton-identifiant>.github.io/<nom-du-dépôt>/`.

Le dépôt doit être public pour que Pages fonctionne avec un compte gratuit.

## Ce qui fonctionne hors de claude.ai

- Campagne, expédition, épreuves, boutiques, équipement, duel local.
- La sauvegarde, enregistrée dans le navigateur : elle est propre à chaque appareil et à chaque adresse.

## Ce qui ne fonctionne pas encore hors de claude.ai

- L'arène en ligne entre deux appareils.
- La sauvegarde partagée entre appareils.

## Dépendances chargées depuis Internet

- three.js r128, depuis cdnjs.
- Les polices Anton et Inter, depuis Google Fonts.
