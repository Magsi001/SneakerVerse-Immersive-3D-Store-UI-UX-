---
name: Luminous Velocity
colors:
  surface: '#121414'
  surface-dim: '#121414'
  surface-bright: '#37393a'
  surface-container-lowest: '#0c0f0f'
  surface-container-low: '#1a1c1c'
  surface-container: '#1e2020'
  surface-container-high: '#282a2b'
  surface-container-highest: '#333535'
  on-surface: '#e2e2e2'
  on-surface-variant: '#c4c7c7'
  inverse-surface: '#e2e2e2'
  inverse-on-surface: '#2f3131'
  outline: '#8e9192'
  outline-variant: '#444748'
  surface-tint: '#c9c6c5'
  primary: '#c9c6c5'
  on-primary: '#313030'
  primary-container: '#050505'
  on-primary-container: '#797777'
  inverse-primary: '#5f5e5e'
  secondary: '#b0c6ff'
  on-secondary: '#002d6f'
  secondary-container: '#568dff'
  on-secondary-container: '#002661'
  tertiary: '#c6c6c6'
  on-tertiary: '#2f3131'
  tertiary-container: '#040505'
  on-tertiary-container: '#767777'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c9c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474646'
  secondary-fixed: '#d9e2ff'
  secondary-fixed-dim: '#b0c6ff'
  on-secondary-fixed: '#001945'
  on-secondary-fixed-variant: '#00429c'
  tertiary-fixed: '#e3e2e2'
  tertiary-fixed-dim: '#c6c6c6'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#464747'
  background: '#121414'
  on-background: '#e2e2e2'
  surface-variant: '#333535'
typography:
  display-2xl:
    fontFamily: Sora
    fontSize: 72px
    fontWeight: '800'
    lineHeight: 80px
    letterSpacing: -0.04em
  display-lg:
    fontFamily: Sora
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Sora
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Sora
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.1em
  display-lg-mobile:
    fontFamily: Sora
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base-unit: 8px
  container-max-width: 1440px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  stack-xs: 4px
  stack-sm: 12px
  stack-md: 24px
  stack-lg: 48px
  stack-xl: 80px
---

## Brand & Style

This design system is engineered for a high-end "SneakerVerse" ecosystem, blending the exclusivity of luxury streetwear with the cutting-edge aesthetics of digital futurism. The personality is confident, high-octane, and meticulously crafted, aiming to evoke a sense of "digital physicalness" where high-performance footwear feels like an artifact from the near future.

The visual direction utilizes a **Neo-Glassmorphic** approach. It combines deep, obsidian surfaces with multi-layered translucency, high-frequency background blurs, and spectral glows. The aesthetic draws from high-performance automotive interfaces and premium editorial layouts, characterized by:
- **Futuristic Depth:** Utilizing Z-axis layering to create a sense of floating objects in a vast, dark space.
- **Ultra-Modern Polish:** Micro-interactions and visual cues that feel responsive and liquid.
- **Luxury Minimalism:** Heavy use of negative space to allow the product photography (the "Grails") to dominate the visual hierarchy.

## Colors

The palette is rooted in a "Deep Space" dark mode that prioritizes high-contrast legibility and atmospheric depth.

- **Base (Deep Black):** The foundation of the UI, providing a limitless canvas that makes glass effects and metallic accents pop.
- **Accents (Electric Blue):** Used sparingly for critical calls to action, active states, and "kinetic" energy indicators.
- **Metals (Metallic Silver):** Employed for secondary information and iconography to provide a sophisticated, hardware-like feel.
- **Light (Pure White):** Reserved for primary typography and essential highlights to ensure maximum readability against the dark backdrop.

Layering is achieved through varying opacities of white and blue over the deep black base, creating a "smoke and glass" effect rather than flat grey shades.

## Typography

The typography strategy uses a trio of typefaces to define the "SneakerVerse" hierarchy:

1.  **Sora (Headlines):** Its geometric but tech-forward construction provides the "award-winning" display feel. Large headlines should use tight letter spacing to feel impactful and structural.
2.  **Inter (Body):** Selected for its unparalleled clarity in dark environments. It handles long-form product descriptions and interface labels with Swiss precision.
3.  **JetBrains Mono (Technical Labels):** Used for SKU numbers, price tags, and technical specs (e.g., "Air Max Unit 270"). This adds a "coded" or "manufactured" feel to the sneaker details.

**Styling Note:** For hero sections, use `display-2xl` with a subtle silver-to-white gradient to mimic metallic reflection.

## Layout & Spacing

The design system utilizes a **Dynamic Fluid Grid** that prioritizes breathability. 

- **Desktop Layout:** A 12-column grid with wide 64px outer margins to create an "editorial" look. Components often span "offset" columns to create asymmetrical, high-end compositions.
- **Mobile Layout:** A 4-column grid with 16px margins. Elements move to a vertical stack, but maintain high horizontal padding within cards to preserve the floating effect.
- **Rhythm:** An 8px linear scale is used for all internal spacing. For product galleries, use "unconventional" spacing (staggered heights) to mimic a high-fashion lookbook.

## Elevation & Depth

Depth is the defining characteristic of this system. It is achieved through three primary methods:

1.  **Backdrop Blurs:** Floating panels (cards/modals) must use a `backdrop-filter: blur(20px)` with a semi-transparent `rgba(255, 255, 255, 0.05)` fill. This creates the "Glassmorphism" effect.
2.  **Layered Shadows:** Use multi-layered shadows instead of a single drop shadow. A soft, large-spread dark shadow provides the lift, while a tight, primary-colored glow (`#0070FF` at 10-15% opacity) suggests the object is emitting light or reflecting the digital environment.
3.  **Inner Strokes:** To define edges on dark backgrounds, use a 1px top-aligned inner border (linear-gradient of white to transparent) to simulate a "specular highlight" on the edge of the glass.

## Shapes

The shape language is **"Refined Geometric."** 

- **Standard Elements:** Use a 0.5rem (8px) radius for buttons and input fields to maintain a professional, sharp look.
- **Featured Cards:** Use `rounded-xl` (1.5rem/24px) for product cards and main containers to emphasize the "floating glass" aesthetic.
- **Interactive States:** On hover, shapes may slightly expand (scale 1.02) to reinforce the tactile, responsive nature of the UI.

## Components

### Buttons
- **Primary:** Solid Electric Blue with a localized glow effect on hover. Typography is bold and high-contrast white.
- **Secondary (Glass):** Transparent background with 1px Silver border and backdrop blur.
- **Ghost:** No border, text-only with a subtle blue underline or glow on hover.

### Floating Product Cards
- These are the centerpiece. Features a high-resolution sneaker cutout that "breaks" the container boundary (overlapping the top or side).
- Background: 5% white glass with a subtle 1px border highlight.
- Content: Name in Sora Bold, Price in JetBrains Mono.

### Glassmorphic Inputs
- Deep black fill (10% opacity) with a focus state that triggers an Electric Blue outer glow and a 1px border.
- Placeholder text in Metallic Silver.

### Chips & Tags
- Pill-shaped with low-opacity blue backgrounds for "New Drop" or "Limited Edition" status.

### Dynamic Lists
- Minimalist rows separated by 1px low-opacity silver lines. Interactive rows should highlight with a subtle glass overlay on hover.