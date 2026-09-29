# PowerLibrary Documentation

Documentation utilisateur publique de PowerLibrary.

## Publication

Ce dépôt est conçu pour être publié directement avec GitHub Pages :

1. `Settings` → `Pages`
2. `Source` → `Deploy from a branch`
3. Branche `main`
4. Dossier `/(root)`
5. `Save`

Le site est ensuite disponible à l'adresse :

`https://wyldkaarde2023.github.io/PowerLibrary-Docs/`

## Modifier la documentation

Les fichiers du site sont volontairement statiques et sans dépendances :

- `index.html` : contenu de la documentation
- `assets/style.css` : présentation
- `assets/docs.js` : navigation et recherche
- `.nojekyll` : publication statique sans traitement Jekyll

Après un `git push` sur `main`, GitHub Pages republie automatiquement le site.
