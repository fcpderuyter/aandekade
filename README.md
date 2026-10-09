# ...aan de kade — GitHub Pages

Deze map is voorbereid voor gratis hosting via GitHub Pages.

## Formulieren koppelen
GitHub Pages verwerkt zelf geen formulieren. Daarom zijn de formulieren voorbereid voor Formspree.

Zoek in `index.html` naar:
- `REPLACE_ME_CONTACT`
- `REPLACE_ME_BOOKING`

Vervang die door de echte Formspree formulier-ID's.

## Publiceren op GitHub Pages
1. Maak op GitHub een publieke repository, bijvoorbeeld `aan-de-kade`.
2. Upload alle bestanden uit deze map naar de hoofdmap van de repository.
3. Ga naar `Settings` → `Pages`.
4. Kies bij **Build and deployment**:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
5. Klik op **Save**.
6. Wacht tot GitHub Pages de site publiceert.

Je site komt dan op een URL zoals:
`https://jouw-gebruikersnaam.github.io/aan-de-kade/`

## Formspree instellen
1. Maak een gratis Formspree-account.
2. Maak één formulier voor Contact.
3. Kopieer de formulier-ID uit de endpoint-URL.
4. Vervang `REPLACE_ME_CONTACT`.
5. Maak een tweede formulier voor Boeking.
6. Vervang `REPLACE_ME_BOOKING`.
7. Test beide formulieren op de gepubliceerde site.
8. Stel in Formspree eventueel de bedanktpagina/redirect in naar `bedankt.html`.

## Agenda
Pas activiteiten aan in `agenda.js`. Na opslaan en committen publiceert GitHub Pages automatisch opnieuw.

## Privacy
Controleer `privacy.html` vóór livegang en vul echte organisatiegegevens, bewaartermijnen en gebruikte diensten in.

## Netlify
`netlify.toml` is niet nodig op GitHub Pages en is daarom niet meegenomen.
