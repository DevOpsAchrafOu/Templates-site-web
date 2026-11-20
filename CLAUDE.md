# Templates-site-web (FOCAL) — context for Claude Code

Owner: Ouakka Achraf (OA), freelance web/mobile team (Morocco). Conversation language: French / Moroccan Darija.

## What lives where
- Root (`index.html`, `css/`, `imgs/`, `js/`) — original FOCAL Bootstrap 4 template. Kept as the **"before"** version.
- `redesign/` — conversion redesign of FOCAL as a phone/laptop repair shop landing page (static HTML, edit directly).
  Live: https://devopsachrafou.github.io/Templates-site-web/redesign/

## Decisions already made (keep them)
- The business is **fictional** (FOCAL Repair, Denver, (720) 555-0142 — a reserved 555-01xx number). Keep the footer line "Demo concept — fictional business. Redesign by OA". Never use a real shop's name, number or reviews without its permission.
- No invented reviews or ratings; the reviews area links to Google instead.
- Conversion structure: one primary CTA (Call now), 3-field quote form, price table, trust strip, sticky mobile call bar.

## Deploying
- Push to `main` → GitHub Pages ("pages build and deployment") republishes. Work on a branch, PR, merge.

## Related repo
- `DevOpsAchrafOu/nexProMa-frontend` — nexProMa store and its redesign (see its CLAUDE.md).
- The team website (Arabic, "OA — مواقع وتطبيقات للأعمال المحلية") is a Claude Design canvas, not in a repo yet.
