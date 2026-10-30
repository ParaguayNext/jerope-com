# jerope.com – startsida (utkast)

Första grund för en ny webbplats på domänen **jerope.com**. Detta är ett startläge för teamet
(Project Manager, Website Ops, Critiquito, Site Audit) att bygga vidare på.

## Struktur

- `index.html` – startsidan (logotypplats, rubrik, kort beskrivning, kontaktsektion)
- `styles.css` – all styling, responsiv, inga beroenden
- `assets/` – plats för logotyp och bilder

Ren HTML + CSS. Inget byggsteg – öppna `index.html` direkt i en webbläsare, eller servera mappen
med valfri statisk webbserver (t.ex. `npx serve .` eller `python3 -m http.server`).

## Innehåll = platshållare

Allt textinnehåll är **platshållare** inom hakparenteser, t.ex. `[Rubrik]`, `[Kort beskrivning]`,
`[Logotyp här]` och `[kontakt@exempel – ange riktig e-post]`. Inga påståenden, mätetal, citat eller
omdömen är framtagna – riktigt innehåll ska komma från Roger.

Sidan har `noindex, nofollow` så att utkastet inte indexeras av sökmotorer. Ta bort det inför lansering.

## Publicering och DNS

- Förhandsvisningar får bara ske på tillfälliga adresser (t.ex. `*.pages.dev`), aldrig på jerope.com.
- **Produktionsdeploy, koppling av jerope.com och alla DNS-ändringar kräver Rogers uttryckliga ja.**
