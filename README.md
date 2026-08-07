# Totální zatmění Slunce 12. 8. 2026 — rodinný plán

- `index.html` — kompletní plán (varianty, mapa pásu totality, den D, itinerář, odkazy)
- `mapa-body.html` — interaktivní mapa dětských bodů (Leaflet + mapy.cz / OpenStreetMap)

## Klíč mapy.cz
V `mapa-body.html` na začátku `<script>` je řádek `const MAPY_KEY = "";`.
1) Vytvoř klíč (REST API) na https://developer.mapy.com
2) V konzoli mapy.cz povol doménu tohoto webu (viz níže)
3) Vlož klíč mezi uvozovky a commitni.
Bez klíče se použije OpenStreetMap.

## GitHub Pages
Settings → Pages → Source: *Deploy from a branch* → `main` / `/ (root)`.
Web: `https://<user>.github.io/<repo>/` · mapa: `.../mapa-body.html`
