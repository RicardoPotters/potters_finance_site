# Potters Finance

Zakelijke one-page website voor `pottersfinance.nl`, geschikt voor deployment op Vercel als statische site.
De huidige versie gebruikt de kleurstelling en bedrijfsgegevens uit het briefpapier van Potters Finance B.V.

## Bestanden

- `index.html`: de volledige homepage
- `styles.css`: styling en responsive layout
- `vercel.json`: minimale Vercel-config

## Deploy op Vercel

1. Maak in Vercel een nieuw project aan.
2. Selecteer de map `pottersfinance-site`.
3. Framework preset: `Other`.
4. Build command leeg laten.
5. Output directory leeg laten.
6. Deploy.

## Domein koppelen

Voeg in Vercel toe:

- `pottersfinance.nl`
- `www.pottersfinance.nl`

Zet daarna bij Freedom de DNS-records die Vercel aangeeft. Meestal zijn dat:

- `A` record voor `@` naar `76.76.21.21`
- `CNAME` record voor `www` naar de door Vercel getoonde host

## Aanpassen

Waarschijnlijke eerste vervolgstappen:

- echte contactgegevens toevoegen
- teksten verder aanscherpen op basis van je echte LinkedIn-headline en ervaring
- logo of portret toevoegen
- diensten en sectorfocus specifieker maken
