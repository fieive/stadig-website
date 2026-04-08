Search the web for the latest UI/UX design trends from 2026. Use WebSearch with queries like "UI design trends 2026", "UX trends 2026", and "web design trends 2026".

Look at multiple sources (design publications, agency roundups, designer blogs). Synthesize the findings, then:

1. Generate a self-contained HTML file at `/tmp/ui-trends.html` with:
   - Dark background (#0f0f0f), warm accent color (#f0b49a), Manrope font from Google Fonts
   - A hero section with large title "UI/UX Trends 2026" and today's date
   - A scannable card grid (bento-style) — one card per trend, each with:
     - Trend name as bold heading
     - 2–3 sentence description of what it looks like in practice
     - A small tag/badge like "Typography", "Motion", "Color", etc.
     - A **live visual demo** built from pure HTML/CSS inside the card — a small interactive or animated preview that demonstrates the trend visually. Examples:
       - Bento Grid → a miniature bento layout with colored tiles
       - Glassmorphism → a frosted semi-transparent card with a blurred gradient behind it
       - Digital Texture / Tactile UI → a clay/jelly button with a squish animation on hover
       - Expressive Typography → oversized display text with tight tracking
       - Organic / Anti-Grid → an SVG blob shape or diagonal overlapping elements
       - Warm Saturated Color → a gradient swatch strip showing the palette
       - Motion / Micro-interactions → a CSS animated element (spinner, pulse, sliding indicator)
       - Glassmorphism → backdrop-filter blur panel over a colorful background
       - Calm Interface → a minimal card with lots of breathing room and muted type
       - Nostalgia / Retro → pixel borders, early-software font feel, or scan-line overlay
       Each demo must be contained within the card's preview area (max ~180px tall), use only CSS/HTML (no canvas, no external images), and feel polished. Use CSS animations (@keyframes) where relevant.
   - A "Relevance to Stadig" section — which trends apply to the studio site (dark theme, warm accents, Norwegian aesthetic)
   - A sources section with clickable links
   - Smooth hover effects on cards, clean typography, generous spacing
   - The HTML must be fully self-contained (no external dependencies except Google Fonts)

2. Open the file in the default browser using: `open /tmp/ui-trends.html`

Keep the card layout responsive (CSS grid, min 280px columns). Make it look like a real design brief — something a designer would actually enjoy reading. The visual demos are the centrepiece — make them genuinely impressive.
