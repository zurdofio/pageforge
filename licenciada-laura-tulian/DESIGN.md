# DESIGN.md — licenciada laura tulian

## 1. Overview & Creative Direction

**Business:** licenciada laura tulian
**Industry:** Salud y bienestar
**Tagline:** Fonoaudiologia Lic. Laura Tulian
**Description:** soy licenciada en fonoaudiologia, realizo estudios audiologicos particulares y obra social. Trabajo con bebes, niños, jovenes y adultos. El contacto debe ser solo por whatsapp, con un icono flotante

**Design Style:** profesional
Clean, balanced, and trustworthy. Uses structured layouts with generous whitespace. Typography is clear and authoritative. Subtle shadows and borders define hierarchy.

## 2. Color Palette

| Role | Color | Usage |
|------|-------|-------|
| Primary | #166534 | Headers, primary buttons, key UI elements |
| Secondary | #22c55e | Supporting elements, hover states, secondary buttons |
| Accent | #86efac | Highlights, links, call-to-action accents |
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
Include a contact section with:
- Phone: +5493515640023
- Email: laura.tulian@gmail.com
- Address: Montemayor 1531, cordoba

### Footer
Include social media icon links:
- instagram: https://instagram.com/sileymartin
- facebook: https://facebook.com/sileymartin
- twitter: https://x.com/sileymartin
- whatsapp: https://wa.me/543515640023

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