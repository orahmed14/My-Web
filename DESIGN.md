---
name: Modern Desert Serenity
colors:
  surface: '#fff8f3'
  surface-dim: '#e3d8cb'
  surface-bright: '#fff8f3'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fdf2e4'
  surface-container: '#f7ecdf'
  surface-container-high: '#f2e7d9'
  surface-container-highest: '#ece1d3'
  on-surface: '#201b13'
  on-surface-variant: '#43474a'
  inverse-surface: '#353027'
  inverse-on-surface: '#faefe1'
  outline: '#74787b'
  outline-variant: '#c3c7ca'
  surface-tint: '#556067'
  primary: '#061116'
  on-primary: '#ffffff'
  primary-container: '#1b262c'
  on-primary-container: '#828d95'
  inverse-primary: '#bcc8d0'
  secondary: '#9c4323'
  on-secondary: '#ffffff'
  secondary-container: '#ff9069'
  on-secondary-container: '#762808'
  tertiary: '#111008'
  on-tertiary: '#ffffff'
  tertiary-container: '#26251b'
  on-tertiary-container: '#8f8c7f'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d8e4ec'
  primary-fixed-dim: '#bcc8d0'
  on-primary-fixed: '#121d23'
  on-primary-fixed-variant: '#3d484f'
  secondary-fixed: '#ffdbcf'
  secondary-fixed-dim: '#ffb59c'
  on-secondary-fixed: '#390c00'
  on-secondary-fixed-variant: '#7d2d0e'
  tertiary-fixed: '#e7e2d4'
  tertiary-fixed-dim: '#cbc6b8'
  on-tertiary-fixed: '#1d1c13'
  on-tertiary-fixed-variant: '#49473c'
  background: '#fff8f3'
  on-background: '#201b13'
  surface-variant: '#ece1d3'
typography:
  display-lg:
    fontFamily: Libre Caslon Text
    fontSize: 64px
    fontWeight: '400'
    lineHeight: 72px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Libre Caslon Text
    fontSize: 40px
    fontWeight: '400'
    lineHeight: 48px
  headline-lg-mobile:
    fontFamily: Libre Caslon Text
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
  headline-md:
    fontFamily: Libre Caslon Text
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
  title-lg:
    fontFamily: Hanken Grotesk
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  section-gap: 120px
  container-padding: 24px
  grid-gutter: 32px
  card-gap: 24px
---

## Brand & Style
The brand personality is **composed, reverent, and sophisticated**. This design system moves away from typical religious travel tropes to position the product as a **premium travel concierge**. It prioritizes the spiritual journey's peace of mind through a high-end, editorial aesthetic.

The visual style is **Minimalist & Premium**. It leverages expansive whitespace to provide visual "breathing room," reflecting the tranquility of the pilgrimage. By combining traditional serif elements with a clean, modern structural layout, the system establishes a bridge between ancient tradition and modern reliability.

- **Minimalism:** Focus on a single clear action per section.
- **Spaciousness:** Large internal padding within containers and generous margins between sections.
- **Editorial Influence:** Large-scale high-quality photography paired with asymmetrical text placements to evoke a high-end travel magazine feel.

## Colors
The palette is inspired by the natural landscape of the Hijaz region, utilizing earth tones to ground the user experience.

- **Refined Navy (#1B262C):** Used for primary text, navigation backgrounds, and high-priority call-to-actions to ensure maximum contrast and an air of authority.
- **Deep Terracotta (#A64B2A):** An accent color used sparingly for highlights, active states, and specific "premium" indicators. It provides warmth without the aggression of pure red.
- **Soft Sand (#F5F0E1):** The primary background color. It is softer on the eyes than pure white and reinforces the "Desert Serenity" theme.
- **Surface Neutrals:** Use a scale of warm greys derived from the primary navy to maintain harmony in secondary text and UI borders.

## Typography
The typography strategy relies on the contrast between **Libre Caslon Text** (Tradition/Trust) and **Hanken Grotesk** (Modernity/Precision).

- **Headlines:** Should always be set in the serif typeface. For large display sizes, use tighter letter spacing to create a more "designed" look.
- **Body Text:** Hanken Grotesk provides a technical, clean feel that balances the decorative nature of the serif. It ensures long-form content and data (like prices and dates) remain highly legible.
- **Labels:** Use Hanken Grotesk with slight tracking (letter spacing) and uppercase styling for small UI elements like "Economy" or "Direct Flight" badges to maintain a refined, concierge-style aesthetic.

## Layout & Spacing
This design system utilizes a **12-column fixed grid** (1280px max-width) for desktop to maintain a centered, high-end feel.

- **Generous Gaps:** Section vertical spacing is set at a significant `120px` to prevent the UI from feeling cluttered. 
- **The "Concierge" Margin:** Content should never feel cramped against the edges. Use a minimum of `24px` horizontal padding on mobile, scaling to `48px+` on tablet.
- **Alignment:** Use a mix of centered typography for hero sections and left-aligned (or right-aligned for Arabic) text for content blocks to create a dynamic, editorial rhythm.

## Elevation & Depth
Depth is created through **Tonal Layers** and **Ambient Shadows** rather than lines.

- **Surfaces:** Use the Soft Sand (#F5F0E1) as the base, with pure white (#FFFFFF) used for elevated "cards" or containers to create a subtle but clear distinction.
- **Shadows:** Avoid dark, heavy shadows. Use an "Ambient Glow" style: `0px 12px 32px rgba(27, 38, 44, 0.04)`. This creates a soft lift that feels natural and premium.
- **Interactions:** Upon hover, cards should subtly lift (shadow deepens slightly) rather than changing color, maintaining the calm atmosphere of the design.

## Shapes
To maintain a "Sophisticated & Premium" look, the design system uses **Soft (Level 1)** roundedness. 

- **Subtlety:** Curves are intentional but restrained (4px - 8px). This mimics high-end stationery or architectural lines rather than the "bubbly" look of consumer social apps.
- **Buttons:** Primary buttons should use the `rounded-lg` (8px) setting to feel approachable yet firm.
- **Imagery:** Large hero images should remain sharp (0px) or use very minimal rounding (4px) to emphasize the professional photography.

## Components
- **Buttons:**
    - *Primary:* Refined Navy background, White text. No border. High horizontal padding.
    - *Secondary:* Transparent background, Refined Navy border (1px), Serif text for a "boutique" feel.
- **Package Cards:** Use a white background on the Soft Sand page. Images should take up the top 50% of the card. Prices should be prominently displayed in the Serif font.
- **Inputs & Search:** Instead of heavy boxes, use a "Minimalist Field" style with only a bottom border or a very light, soft-filled background.
- **Chips/Badges:** Use the Terracotta (#A64B2A) at 10% opacity for the background and 100% opacity for the text. This highlights categories (e.g., "5-Star", "VIP") without overwhelming the visual hierarchy.
- **Navigation:** A "floating" transparent header that becomes Refined Navy on scroll, ensuring the photography of the hero section is the first thing the user sees.