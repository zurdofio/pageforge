# DESIGN.md — Obra social mascotas

## 1. Overview & Creative Direction

**Business:** Obra social mascotas
**Industry:** Salud y bienestar
**Tagline:** La Obra Social para Mascotas
**Description:** es una obra social para mascotas, debe tener un diseño alegre y divertido

**Design Style:** creativo
Expressive and original. Asymmetric layouts, bold typography choices, unexpected color combinations. Visual storytelling through images and illustrations.

## 2. Color Palette

| Role | Color | Usage |
|------|-------|-------|
| Primary | #78350f | Headers, primary buttons, key UI elements |
| Secondary | #f59e0b | Supporting elements, hover states, secondary buttons |
| Accent | #fde68a | Highlights, links, call-to-action accents |
| Background | #ffffff | Main page background |
| Surface | #f8f9fa | Card and section backgrounds |
| Text | #1a1a1a | Primary body text |
| Text Muted | #6b7280 | Secondary text, captions |

## 3. Typography

- **Headings:** Use a modern Google Font (e.g., Inter, Poppins, or Montserrat). Bold weight, tight letter-spacing.
- **Body:** Same font family, regular weight, 16px base size, 1.6 line-height.
- **Accents:** For code, URLs, or monospace elements use JetBrains Mono or similar.
- All fonts must be free Google Fonts loaded via `<link>`.

## 4. Layout Principles

- Single-page design with clear section separation
- Mobile-first responsive layout
- Fixed/sticky navigation header
- Generous padding (section padding: 80px+ vertical)
- Max content width: 1200px, centered
- Consistent spacing scale (8px base unit)

## 5. Components & Sections

### Navigation
- Sticky top bar with logo/business name, nav links, and a CTA button
- Use the business name as a styled text logo
- Hamburger menu on mobile

### Hero Section
- Full-width with business name, tagline, and primary CTA button
- Background: either a gradient using primary/secondary colors, a hero image from placehold.co, or a clean solid background

### About / Services
- Generate plausible content based on the industry and description
- Use cards or columns for services/features
- Include placeholder images from https://placehold.co/

### Contact
- No contact section needed

### Footer
- Simple footer with business name and copyright

## 6. Interactions & Animations

- Subtle scroll-reveal animations (fade-in + slight translate) on sections
- Smooth scroll for anchor navigation
- Hover effects on buttons (brightness/scale) and cards (shadow/border)
- No heavy animations. Keep it professional and sober.

## 7. Technical Constraints

- Single self-contained HTML file
- All CSS in `<style>` tags (no external CSS files)
- Minimal vanilla JS in `<script>` (only for animations and mobile nav toggle)
- No external JS libraries or frameworks
- Responsive mobile-first with breakpoints at 768px and 1024px
- All text content in Spanish
- Use https://placehold.co/ for any placeholder images

## 8. Content Policy

Do NOT generate content related to: pornography, explicit sexual content, graphic violence, hate speech, discrimination, illegal activities, weapons, drugs, or gambling.