# Leerfeed

Een persoonlijke leerapp in TikTok-stijl (PWA): korte kaartjes, visuele deep dives en elke dag nieuwe, nagekeken inhoud.

- `index.html`: de app (alles in één bestand)
- `content/feed.json`: dagelijkse inhoud (`cards` en `dives`), aangevuld door een geplande taak
- Wensen voor deep dives: maak een issue met titel `Wens: <onderwerp>`

## Formaat `content/feed.json`
```json
{
  "updated": "2026-11-17T06:40:00Z",
  "cards": [{"cat": "wetenschap", "title": "", "body": "", "take": "", "deep": "", "quiz": {"q": "", "o": ["", "", ""], "a": 0}, "src": [{"t": "", "u": "https://..."}], "date": "ISO"}],
  "dives": [{"id": "2026-11-17", "title": "", "emoji": "", "cat": "tech", "date": "ISO", "chapters": [{"h": "", "text": "", "svg": "<svg ...>"}], "quiz": [], "src": []}]
}
```
Categorieën: wetenschap, psychologie, geld, marketing, geschiedenis, gezondheid, taal, tech, productiviteit.
