# BioBalance Funnel

One-Page Funnel-Website für **BioBalance** — testbasierte Praxislösungen im Gesundheitswesen.

## Über

Lead-Funnel zur Gewinnung von Partnern aus dem Gesundheitsbereich (Fitnessstudios, Gesundheits-Coaches, Therapeuten, Heilpraktiker, Ernährungsberater).

Kernbotschaft: **"Wir raten nicht — wir testen."** Vom Berater zum Longevity-Experten mit dem exklusiven Trockenbluttest.

## Inhalt

- `index.html` — komplette One-Page-Site (single file, alle Styles inline)
- `assets/` — Logo & Bildmaterial (Thilo Wagner)

## Lokal öffnen

Einfach `index.html` im Browser doppelklicken.

## Deployment

Die Seite ist statisch. Sie kann z.B. auf folgenden Plattformen kostenlos veröffentlicht werden:

- **GitHub Pages** — in Repo-Settings → Pages → Source: `main` → `/` (root)
- **Netlify** — Repo verbinden, Drag & Drop, oder `netlify deploy`
- **Vercel** — Repo verbinden, fertig
- **Cloudflare Pages** — Repo verbinden

## Anpassungen vor Live-Gang

In `index.html` zwei Stellen anpassen:

1. **Calendly-Link einfügen** (zwei Stellen, suche nach `Calendly-Link`):
   ```html
   <a href="DEIN_CALENDLY_LINK" class="btn btn-outline">📅 Direkt Termin buchen</a>
   ```

2. **Lead-Formular**: Aktuell zeigt das Formular nur eine lokale Bestätigung. Für echte Lead-Erfassung empfohlen:
   - [Formspree](https://formspree.io) (einfachster Weg, Form-`action` setzen)
   - [Netlify Forms](https://docs.netlify.com/forms/setup/) (wenn Netlify-Hosting)
   - Eigenes Backend / Mailto-Fallback

## Lizenz / Hinweis

Inhalt: © 2026 Thilo Wagner / BioBalance · Privates Projekt
