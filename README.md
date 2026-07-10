# Calculator Oferta - GitHub Pages

Folder pregatit pentru publicare pe GitHub Pages.

## Publicare rapida

1. Creeaza un repository nou pe GitHub, de exemplu `calculator-oferta`.
2. Incarca toate fisierele din acest folder in repository:
   - `index.html`
   - `manifest.webmanifest`
   - `icon.svg`
   - `icon-180.png`
3. In repository, mergi la `Settings -> Pages`.
4. La `Build and deployment`, alege:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
5. Apasa `Save`.

Linkul va fi de forma:
`https://username.github.io/calculator-oferta/`

Pe iPhone: deschide linkul in Safari -> Share -> Add to Home Screen.

## Firebase

Pentru salvare online:
1. Creeaza proiect in Firebase Console.
2. Adauga Web App si copiaza `firebaseConfig`.
3. Activeaza Firestore Database.
4. Completeaza `firebase-config.js` cu datele tale.
5. Incarca pe GitHub: `index.html`, `firebase-config.js`, `manifest.webmanifest`, `icon.svg`, `icon-180.png`, `icon-512.png`.
