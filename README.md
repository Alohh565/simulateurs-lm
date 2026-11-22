# Simulateurs de vente bricolage

Simulateurs de vente gratuits et open source pour les rayons d'un magasin de bricolage. Ils permettent de chiffrer un projet avec le client en quelques minutes, directement dans le navigateur, sans installation ni compte.

## Les simulateurs

| Rayon | Simulateur | Ce qu'il fait |
|---|---|---|
| Confort | [Chauffage](sims/chauffage.html) | Compare le coût annuel, l'investissement, le retour sur investissement et le CO₂ de 8 solutions de chauffage |
| Menuiseries | [Menuiseries](sims/menuiseries.html) | Fenêtres et portes : prix, pose, TVA, MaPrimeRénov', reste à charge et économies |
| Cuisine | [Atelier Cuisine](sims/cuisine.html) | Plan 2D, vue 3D, aménagement des meubles, contrôles d'ergonomie et devis |
| Sols | [Sols](sims/sols.html) | Pièces, revêtement, type de pose, plan 3D et finitions |
| Quincaillerie | [Fixation](sims/fixation.html) | Choix de la cheville, du foret et de la vis selon le support et le poids |

La page [`index.html`](index.html) regroupe tous les simulateurs dans un seul outil. On peut passer d'un rayon à l'autre sans perdre sa saisie.

## Utilisation

- **En ligne** : activez GitHub Pages (Settings → Pages → Deploy from branch → `main`), puis ouvrez le lien fourni.
- **En local** : téléchargez le repo et ouvrez `index.html` dans un navigateur.

Chaque simulateur est un seul fichier HTML autonome (HTML, CSS et JavaScript). Seules les polices et la bibliothèque 3D (three.js) sont chargées depuis un CDN.

## Avertissement

Les montants sont des estimations indicatives et non contractuelles. Les prix et les aides (TVA, MaPrimeRénov'…) évoluent : vérifiez-les avant de remettre un chiffrage à un client.

## Contribuer

Les suggestions, signalements de bugs et nouveaux simulateurs sont les bienvenus : ouvrez une *issue* ou une *pull request*.

## Licence

[MIT](LICENSE) © 2026 Alan Pincedé
