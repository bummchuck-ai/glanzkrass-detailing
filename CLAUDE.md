# Glanzkrass Detailing — CLAUDE.md

## Projekt
Landingpage für Glanzkrass, professionelle Fahrzeugaufbereitung im Papenteich / Meine.
**Typ:** StarSite-Prototyp-Kunde (Branche: Detailing/Auto)
**Status:** Prototyp — noch kein aktiver Kundenauftrag bestätigt

## Stack
- Reines HTML/CSS/JS — kein Framework, kein Build-Step
- Google Fonts: Chakra Petch + DM Sans
- Design: Dark Cyber-Ästhetik (deep navy `#030509`, Cyan-Accent `#00d4ff`)
- Features: Custom Cursor, Canvas Rain-Effekt, Glassmorphism
- Seiten: `index.html`, `impressum.html`, `datenschutz.html`
- Assets: `assets/` Ordner

## Key Commands
```bash
# Lokal testen
open index.html
# oder
npx serve .

# Deploy
vercel --prod
```

## Deployment-Workflow
1. Änderungen lokal testen (`open index.html`)
2. Commit + Push: `git add -A && git commit -m "..." && git push`
3. Vercel deployed automatisch via GitHub-Integration (Static, kein Build)
4. Kein `vercel.json` vorhanden — Vercel erkennt static automatisch

## Regeln (KRITISCH)
- **StarSite-Prototyp** — Design repräsentiert StarSite-Portfolio
- Keine inhaltlichen Änderungen ohne Rücksprache mit Felix
- Design-Sprache beibehalten: dunkel, futuristisch, cyan/blau
- Wenn Kunde aktiv wird: CLAUDE.md mit echten Kontaktdaten updaten
- Repo: `bummchuck-ai/glanzkrass-detailing` (PRIVATE)
