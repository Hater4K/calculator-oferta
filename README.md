## Flux partide si oferte

- Partida este sursa datelor: produse, cantitati, preturi, transport, client si adresa.
- In oferta se pot modifica doar datele comerciale: numar, data, client, CUI, adresa, valabilitate, plata si observatii.
- Produsele, preturile si transportul nu se modifica in oferta. Din oferta, apasa **Modifica partida**; orice modificare facuta acolo se transfera automat in oferta.
- La generarea ofertei, partida se muta din lista activa, dar ramane legata de oferta si poate fi redeschisa din butonul de mai sus.

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


## Oferte salvate

Aplicatia include acum oferte salvate permanent in aceeasi stocare Firebase folosita de partide.

- Dintr-o partida deschisa, foloseste butonul `Genereaza oferta`.
- Ofertele apar in sectiunea `Oferte salvate`.
- Poti vizualiza, edita, duplica, exporta PDF sau sterge o oferta.
- Pentru update pe GitHub, incarca si fisierele noi: `offers.js`, `offers.css` si folderul `assets/`.
