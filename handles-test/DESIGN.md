---
name: "Handles Test"
description: "Servicios profesionales — Prueba de handles persistidos"
version: alpha
colors:
  primary: "#1e40af"
  secondary: "#3b82f6"
  accent: "#60a5fa"
  background: "#ffffff"
  surface: "#f8f9fa"
  text: "#1a1a1a"
  textMuted: "#6b7280"
  onSecondary: "#000000"
typography:
  display:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: "56px"
    fontWeight: 800
    lineHeight: 1.1
    letterSpacing: "-0.02em"
  headline:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: "32px"
    fontWeight: 700
    lineHeight: 1.2
  body:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.6
  caption:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: "13px"
    fontWeight: 500
    lineHeight: 1.4
    letterSpacing: "0.02em"
rounded:
  sm: "4px"
  md: "8px"
  lg: "16px"
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
    textColor: "{colors.onSecondary}"
    rounded: "{rounded.md}"
    padding: "{spacing.md}"
    typography: "{typography.body}"
  link:
    textColor: "{colors.primary}"
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
# Handles Test

## Overview
A single-page servicios profesionales website in the profesional style. Tagline: "Prueba de handles persistidos". Clean, balanced, and trustworthy. Structured layouts with generous whitespace. Typography is clear and authoritative. Subtle shadows and borders define hierarchy.

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
- Do give every `<img>` a descriptive `alt` in Spanish, explicit `width` and `height` so the page doesn't jump while it loads, and `loading="lazy"` on everything below the first screen.
- Do keep all visible text in Spanish (es-AR).
- Do use each component's resolved values exactly as given — same hex, same px, same font stack. Don't approximate them, and don't invent intermediate shades or sizes that aren't in the spec.
- Don't import external CSS or JS libraries — a single self-contained HTML file.
- Don't generate pornographic, violent, hateful, discriminatory, illegal, weapons, drugs, or gambling content.
