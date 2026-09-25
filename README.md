# Design System — dépôt de départ

Ce dépôt est la base de votre design system et de votre projet front-end de fin d'année.

## Démarrer
1. Sur GitHub, cliquez sur **Use this template** → créez votre propre dépôt.
2. Clonez-le : `git clone <url-de-votre-depot>`
3. Ouvrez `index.html` avec Live Server (ou `npx serve .`).

## Contenu
| Fichier | Séance 1 |
| --- | --- |
| `docs/FICHE-PROJET.md` | Partie 1 — fiche projet express |
| `docs/wireframes/` | Partie 3 — exports PNG de vos wireframes |
| `docs/atelier/design-system-seance1.excalidraw` | Tableau des ateliers (à importer sur excalidraw.com) |
| `docs/INVENTAIRE.md` | Partie 5 — inventaire des composants |
| `tokens/primitives.css` | Tokens niveau 1 : valeurs brutes |
| `tokens/semantic.css` | Tokens niveau 2 : intentions (+ thème sombre) |
| `tokens/foundations.css` | Typo, espacements, rayons, focus, ombres, animations |
| `components/button.css` | Le test de vérité : un bouton 100 % tokens |
| `DECISIONS.md` | Vos décisions, justifiées par la fiche projet |

## Règle d'or
Un composant ne consomme **jamais** une primitive. Toujours un token sémantique ou de composant.
