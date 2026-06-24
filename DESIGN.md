---
name: Velvet Brew
colors:
  surface: '#fff8f3'
  surface-dim: '#e2d9ce'
  surface-bright: '#fff8f3'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fcf2e7'
  surface-container: '#f6ece1'
  surface-container-high: '#f1e7dc'
  surface-container-highest: '#ebe1d6'
  on-surface: '#1f1b14'
  on-surface-variant: '#4f4540'
  inverse-surface: '#353028'
  inverse-on-surface: '#f9efe4'
  outline: '#81756f'
  outline-variant: '#d3c3bd'
  surface-tint: '#705a4f'
  primary: '#25160e'
  on-primary: '#ffffff'
  primary-container: '#3c2a21'
  on-primary-container: '#aa9084'
  inverse-primary: '#dec1b3'
  secondary: '#6d5b4f'
  on-secondary: '#ffffff'
  secondary-container: '#f4dbcc'
  on-secondary-container: '#725f53'
  tertiary: '#1f1812'
  on-tertiary: '#ffffff'
  tertiary-container: '#352d26'
  on-tertiary-container: '#a0948a'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#fbdcce'
  primary-fixed-dim: '#dec1b3'
  on-primary-fixed: '#281810'
  on-primary-fixed-variant: '#574238'
  secondary-fixed: '#f7decf'
  secondary-fixed-dim: '#dac2b4'
  on-secondary-fixed: '#261910'
  on-secondary-fixed-variant: '#544339'
  tertiary-fixed: '#eee0d5'
  tertiary-fixed-dim: '#d2c4b9'
  on-tertiary-fixed: '#211a14'
  on-tertiary-fixed-variant: '#4e453d'
  background: '#fff8f3'
  on-background: '#1f1b14'
  surface-variant: '#ebe1d6'
typography:
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.2'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 40px
---

## Brand & Style

The design system is centered on a "Sophisticated Organic" narrative. It balances the warmth of a local coffee shop with the precision of a high-end espresso bar. The aesthetic direction leverages **Glassmorphism** and **Tactile Minimalism** to create a digital environment that feels as layered and textured as a hand-poured latte.

The interface should evoke a sense of calm and artisanal quality. By using translucent surfaces and soft background blurs, the UI suggests depth and physical presence without clutter. Transitions must be fluid and eased, mimicking the slow pour of cream into espresso. The target audience values craftsmanship, premium ingredients, and a frictionless, serene ordering experience.

## Colors

The palette is derived from the lifecycle of a coffee bean and the ritual of brewing.

- **Primary (Espresso):** A deep, rich brown used for core branding, primary actions, and high-level headings. It provides the grounding weight for the system.
- **Secondary (Latte):** A muted, sophisticated beige used for supportive elements, secondary buttons, and active states.
- **Tertiary (Cream):** A soft, warm off-white used for cards, glass containers, and subtle backgrounds.
- **Neutral (Parchment):** The foundation color for the overall canvas, ensuring the interface feels warm and inviting rather than sterile.

The system utilizes a light mode default to maintain a "morning cafe" freshness, though the depth of the Espresso primary ensures high legibility and contrast.

## Typography

This design system employs a sophisticated serif/sans-serif pairing to communicate both heritage and modern efficiency.

**Playfair Display** is reserved for headlines and editorial moments. Its high-contrast strokes and elegant terminals reflect the premium nature of the "Crush Coffee" brand. 

**Plus Jakarta Sans** handles all functional and body text. Its modern, rounded terminals complement the glassmorphic UI elements and ensure high readability during the fast-paced task of mobile ordering. 

For mobile screens, large display headings scale down aggressively to prevent awkward line breaks, while body text remains slightly larger than standard (16px+) to ensure accessibility in bright, morning light environments.

## Layout & Spacing

The layout philosophy follows a **fluid, breathable grid** that prioritizes white space to reduce cognitive load. 

- **Desktop:** A 12-column grid with 24px gutters. Content is typically centered in a 1200px container to maintain an editorial feel.
- **Mobile:** A 4-column fluid grid. Side margins are set to 20px to allow for comfortable one-handed navigation.
- **Spacing Rhythm:** All margins and paddings are multiples of 8px. Use generous vertical spacing (64px+) between major sections to emphasize the "Cozy & Sophisticated" brand pillars.

Elements should feel like they are floating on the parchment background, with structural alignment provided by the grid rather than heavy visible lines.

## Elevation & Depth

Depth is achieved through a combination of **Glassmorphism** and **Ambient Shadows**. 

1.  **Glass Layers:** Primary containers use a semi-transparent white (Tertiary) fill with a 20px-40px background blur (Backdrop Filter). This creates a "frosted glass" effect that allows background colors and imagery to peak through softly.
2.  **Inner Glow:** To enhance the tactile feel, glass elements feature a 1px white inner stroke (top and left only) to simulate a light source hitting the edge of a physical material.
3.  **Shadows:** Shadows are rarely pitch black. They use a 15% opacity of the Espresso primary color, with a large blur radius (30px-50px) and a subtle downward offset (10px) to make cards feel like they are hovering gently above the surface.

## Shapes

The shape language is organic and approachable. Standard UI elements (cards, input fields) utilize a **0.5rem (8px)** corner radius to feel soft but professional. 

Interactive elements like buttons and category tags utilize a **Pill-shaped (rounded-xl)** style to mimic the shape of a coffee bean and provide a clear visual affordance for "tap-ability." Icon containers should follow a circular or highly rounded profile to maintain the softness of the brand.

## Components

### Buttons
- **Primary:** Espresso background, Cream text, pill-shaped. Subtle 4px lift shadow on hover.
- **Secondary:** Glassmorphic background (low opacity Cream), Espresso text, 1px Espresso border.

### Cards (Product/Menu)
Cards are the primary expression of the glassmorphic style. They feature a soft 16px corner radius, background blur, and a very light Espresso-tinted shadow. Images within cards should have a subtle zoom-in effect on hover.

### Inputs
Search bars and customizer inputs should use a Tertiary (Cream) background with a 1px Latte border. On focus, the border transitions to Espresso and a soft glow appears.

### Chips & Selection
Used for milk types, roast levels, or sizes. These are pill-shaped with a Latte background. When selected, they transition to Espresso with white text.

### Navigation Bar
The mobile bottom-nav or desktop header should be a persistent glassmorphic bar that sits at the top/bottom of the viewport, blurring the content as it scrolls beneath it. This maintains the "premium" feel across all views.