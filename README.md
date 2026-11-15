# Brassband Oefenmaatje

Oefencoach voor koperblazers in de brassband: routines, inblazen, toonladders, akkoorden, stemapparaat, stemtoon, metronoom, loop-speler en logboek.

## Online zetten via GitHub Pages (± 15 minuten)

1. **Account maken:** ga naar github.com en maak een gratis account.
2. **Repository maken:** klik rechtsboven op **+** → **New repository**.
   - Naam: `oefenmaatje`
   - Zet hem op **Public**
   - Klik op **Create repository**
3. **Bestanden uploaden:** klik op **uploading an existing file**.
   Sleep alle bestanden uit deze map erin. Sleep de losse bestanden, niet de map zelf:
   `index.html`, `manifest.json`, `sw.js`, `icon-180.png`, `icon-192.png`, `icon-512.png`, `icon-512-maskable.png` (deze README mag er ook bij).
   Klik op **Commit changes**.
4. **Pages aanzetten:** ga naar **Settings** → **Pages**.
   - Bij *Source*: **Deploy from a branch**
   - Bij *Branch*: **main** en **/ (root)** → **Save**
5. Wacht 1–2 minuten. Je app staat dan op:
   `https://JOUWNAAM.github.io/oefenmaatje/`

## Op je beginscherm zetten

- **iPhone/iPad:** open de link in **Safari** → deelknop → **Zet op beginscherm**.
- **Android:** open de link in **Chrome** → menu (⋮) → **App installeren**.

Daarna opent de app schermvullend, en hij werkt ook zonder internet.

## Een update doorvoeren

1. Vervang het bestand op GitHub: open het en klik op het potloodje, of upload het opnieuw.
2. Verhoog in `sw.js` het versienummer, bijvoorbeeld `oefenmaatje-v1` → `oefenmaatje-v2`.
3. Iedereen krijgt de nieuwe versie zodra de app opnieuw geopend wordt (soms is twee keer openen nodig).

## Goed om te weten

- **Privacy:** logboek, routines en instellingen blijven op het eigen apparaat. Er gaat niets naar een server.
- **Stemapparaat:** de eerste keer vraagt de browser om toestemming voor de microfoon. Het geluid wordt alleen op het apparaat zelf geanalyseerd.
- **Nieuw logboek:** gegevens uit de Claude-versie gaan niet mee. Op GitHub begin je met een schoon logboek.
