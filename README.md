# keet-updates

Flux de **mise à jour automatique** de [Keet](https://flowwi.fr) — l'app macOS qui transforme une réunion
en compte-rendu + actions, en un raccourci.

- **`appcast.xml`** — le flux Sparkle lu par l'updater intégré de l'app (servi via GitHub Pages :
  `https://tflowwi.github.io/keet-updates/appcast.xml`).
- **Releases** — chaque version de Keet est publiée ici en tant que *GitHub Release* (le `.dmg` notarisé).

Les mises à jour sont **signées EdDSA** et téléchargées en **HTTPS** ; Keet vérifie la signature avant d'installer.
L'audio des réunions ne transite jamais par ici — ce dépôt ne contient que des binaires d'app et des métadonnées.

> Le téléchargement initial de l'app se fait depuis la page produit. Ce dépôt ne sert qu'aux **mises à jour**.
