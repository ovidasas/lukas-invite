# Luko interaktyvus pakvietimas

Šiame aplanke yra paruoštas **vieno HTML failo** puslapis su interaktyviais veikėjais ir automatiškai generuojamu **QR kodu**.

## Kaip įkelti į internetą (GitHub Pages)
1. Susikurk naują GitHub repozitoriją, pvz. `lukas-invite`.
2. Įkelk šiuos failus (`index.html`, `invite.png`).
3. GitHub'e eik į **Settings → Pages** ir pasirink `Deploy from a branch`, Branch: `main`, Folder: `/ (root)`.
4. Išsaugok – po kelių akimirkų gausi adresą: `https://<tavo-vardas>.github.io/lukas-invite/`.
5. Atnaujink puslapį – **QR kodas automatiškai rodys šio puslapio nuorodą**.

## Alternatyva: Netlify
1. Nueik į https://app.netlify.com/ ir `New site from Git` (arba `Deploy manually` nuvilkdamas aplanką).
2. Paskelbus, gausi `https://kažkas.netlify.app/` nuorodą – QR atsinaujins automatiškai.

## Hotspot koregavimas
Jei veikėjų taškai nepataiko, atsidaryk `index.html` ir pakoreguok kiekvieno `.spot` `left/top` procentus.

## QR atsisiuntimas
Mygtukas „Atsisiųsti QR“ puslapyje leis parsisiųsti PNG QR paveiksliuką.
