---
name: "Estudio Arquitectura Norte"
description: "Servicios profesionales — Diseñamos espacios para vivir mejor"
version: alpha
colors:
  primary: "#18181b"
  secondary: "#71717a"
  accent: "#d4d4d8"
  background: "#ffffff"
  surface: "#f8f9fa"
  text: "#1a1a1a"
  textMuted: "#6b7280"
typography:
  display:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: "72px"
    fontWeight: 700
    lineHeight: 1.05
    letterSpacing: "-0.03em"
  headline:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: "28px"
    fontWeight: 400
    lineHeight: 1.3
  body:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.7
  caption:
    fontFamily: "JetBrains Mono, monospace"
    fontSize: "12px"
    fontWeight: 500
    lineHeight: 1.4
    letterSpacing: "0.05em"
rounded:
  sm: "0px"
  md: "2px"
  lg: "4px"
spacing:
  xs: "4px"
  sm: "8px"
  md: "16px"
  lg: "24px"
  xl: "32px"
  "2xl": "48px"
  "3xl": "64px"
components:
  nav:
    backgroundColor: "{colors.background}"
    textColor: "{colors.text}"
    padding: "{spacing.md}"
    height: "72px"
  hero:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.background}"
    typography: "{typography.display}"
    padding: "{spacing.3xl}"
  heading:
    textColor: "{colors.text}"
    typography: "{typography.headline}"
  button:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.background}"
    rounded: "{rounded.md}"
    padding: "{spacing.md}"
    typography: "{typography.body}"
  buttonSecondary:
    backgroundColor: "{colors.secondary}"
    textColor: "{colors.text}"
    rounded: "{rounded.md}"
    padding: "{spacing.md}"
    typography: "{typography.body}"
  link:
    textColor: "{colors.accent}"
    typography: "{typography.body}"
  chip:
    backgroundColor: "{colors.accent}"
    textColor: "{colors.text}"
    rounded: "{rounded.sm}"
    padding: "{spacing.sm}"
    typography: "{typography.caption}"
  card:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.text}"
    rounded: "{rounded.lg}"
    padding: "{spacing.lg}"
  caption:
    textColor: "{colors.textMuted}"
    typography: "{typography.caption}"
  section:
    backgroundColor: "{colors.background}"
    textColor: "{colors.text}"
    padding: "{spacing.3xl}"
---
# Estudio Arquitectura Norte

## Overview
A single-page servicios profesionales website in the minimalista style. Tagline: "Diseñamos espacios para vivir mejor". Ultra-clean with extreme whitespace. Relies on typography and spacing rather than decoration. Monochromatic with a single accent color. No unnecessary elements.

## Colors
`primary` anchors the hero, primary CTA, and brand highlights. `secondary` drives alternate CTAs and hover affordances. `accent` carries links and chips. Neutrals `background`, `surface`, `text`, and `textMuted` carry the long tail of content so the brand accents stay scannable.

## Typography
All four typography tokens use the scale defined in the frontmatter. `display` is reserved for the hero. `headline` is for section headings. `body` is the reading default. `caption` is for metadata, timestamps, and chips.

## Layout
Mobile-first. Max content width 1200px, centered. Breakpoints at 768px and 1024px. Sticky top nav using the `nav` component. Section vertical rhythm uses `{spacing.3xl}` for primary sections and `{spacing.xl}` for inner groups.

## Elevation & Depth
Reserved shadow use. `card` components get a single soft shadow; `nav` stays flat with a 1px bottom border in `{colors.textMuted}` at 20% alpha. No layered overlays.

## Shapes
Three-level rounded scale: `{rounded.sm}` for chips, `{rounded.md}` for buttons and inputs, `{rounded.lg}` for cards.

## Components
`nav` sticky with business name and a primary CTA using the `button` component. `hero` full-width with `{typography.display}` on the primary background. Use `heading` for every H2 inside sections. `button` is the primary CTA; `buttonSecondary` is the alternate. `link` for inline text links. `chip` for small tags or badges. `card` wraps service and menu highlights. `caption` is for muted metadata. `section` sets the outer padding for every top-level block.

## Do's and Don'ts
- Do use `https://placehold.co/` for any placeholder image.
- Do keep all visible text in Spanish (es-AR).
- Do resolve every component property through the token refs; don't inline hex values in the HTML where a token exists.
- Don't import external CSS or JS libraries — a single self-contained HTML file.
- Don't generate pornographic, violent, hateful, discriminatory, illegal, weapons, drugs, or gambling content.
