---
name: Wepor Digital Nexus
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#3a3939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#bbc9cf'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#859399'
  outline-variant: '#3c494e'
  surface-tint: '#4cd6ff'
  primary: '#a4e6ff'
  on-primary: '#003543'
  primary-container: '#00d1ff'
  on-primary-container: '#00566a'
  inverse-primary: '#00677f'
  secondary: '#c6c6c7'
  on-secondary: '#2f3131'
  secondary-container: '#454747'
  on-secondary-container: '#b4b5b5'
  tertiary: '#ffd59c'
  on-tertiary: '#442b00'
  tertiary-container: '#feb127'
  on-tertiary-container: '#6b4700'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#b7eaff'
  primary-fixed-dim: '#4cd6ff'
  on-primary-fixed: '#001f28'
  on-primary-fixed-variant: '#004e60'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#ffddb1'
  tertiary-fixed-dim: '#ffba49'
  on-tertiary-fixed: '#291800'
  on-tertiary-fixed-variant: '#624000'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-lg:
    fontFamily: Sora
    fontSize: 72px
    fontWeight: '700'
    lineHeight: 80px
    letterSpacing: -0.04em
  headline-xl:
    fontFamily: Sora
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Sora
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Sora
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  body-lg:
    fontFamily: Geist
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Geist
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-mono:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1440px
  gutter: 24px
  section-padding-desktop: 120px
  section-padding-mobile: 64px
---

## Brand & Style

The brand identity is engineered to evoke a sense of precision, innovation, and premium exclusivity. It targets tech-forward early adopters and audiophiles who value both high-performance hardware and minimalist aesthetics. The UI functions as a sophisticated "digital gallery," where the interface recedes to prioritize high-fidelity product photography and immersive 3D renders.

The design style is a hybrid of **Technological Minimalism** and **Refined Glassmorphism**. It utilizes vast expanses of "void" (deep black space) to create a boutique atmosphere, punctuated by sharp, high-contrast typography and luminous accent points. The emotional response is one of calm authority—a silent, powerful engine of innovation. 

**Key Principles:**
- **The Void:** Use `#0A0A0A` as a canvas to make product colors and hardware materials pop.
- **Luminosity:** Reserve the accent color for active states, data points, and critical calls to action, simulating the glow of a high-end hardware LED.
- **Precision Motion:** Transitions should be frictionless. Use staggered fades (200ms-400ms) and subtle scale-ups (1.02x) on product cards to imply physical presence.

## Colors

The palette is strictly controlled to maintain a "dark-room" aesthetic. 

- **Primary (Electric Cyan):** Used sparingly for interactive signals, progress bars, and focal points. It represents the "energy" within the devices.
- **Background (Deep Charcoal):** A near-black base that prevents the harshness of pure `#000000` while providing infinite depth.
- **Surface (Glass Base):** A slightly elevated grey (`#161616`) used for card containers and navigation bars, often applied with transparency and backdrop blur.
- **Text:** Pure white is used for primary headlines to ensure maximum contrast, while a 70% opacity white is used for secondary body text to reduce eye strain in dark environments.

## Typography

The typographic system balances futuristic geometry with technical legibility.

- **Headlines:** Sora is utilized for its wide, geometric stance. It conveys a modern tech vibe that feels engineered rather than drawn. Use tight tracking on large display sizes to create a locked-in, architectural look.
- **Body:** Geist provides a clean, neutral, and highly readable experience for technical specifications and product descriptions. It maintains a contemporary feel without distracting from the headlines.
- **Technical Labels:** JetBrains Mono is used for small metadata, "In Stock" indicators, and hardware specs. The monospaced nature reinforces the smart/coded nature of the products.

## Layout & Spacing

This design system employs a **Fluid Grid** with aggressive vertical rhythm to create the "boutique" feel. 

- **Grid:** Use a 12-column grid for desktop with 24px gutters. Product displays should often span 6 or 8 columns, leaving ample "empty" columns to frame the content.
- **Vertical Rhythm:** Sections should be separated by massive padding (`120px+`) to allow the user's eyes to reset between products. 
- **Mobile Reflow:** On mobile, the 12-column grid collapses to 4 columns. Section padding reduces to `64px`. All glassmorphic cards become full-width to maximize touch targets.

## Elevation & Depth

Depth is not communicated through shadows, but through **Tonal Layering** and **Glassmorphism**.

- **Level 0 (Background):** `#0A0A0A` - The infinite base.
- **Level 1 (Cards/Overlays):** A semi-transparent surface (`rgba(22, 22, 22, 0.7)`) with a `20px` backdrop-blur. 
- **The Glow Effect:** Instead of traditional shadows, elevated elements use a very subtle `1px` inner border of `rgba(255, 255, 255, 0.1)` on the top and left edges to simulate light hitting the edge of a glass pane. 
- **Active State:** When an element is focused or active, a soft `#00D1FF` outer glow (blur: 15px, opacity: 0.2) may be applied to suggest energy emission.

## Shapes

The shape language is **Soft-Tech**. Elements are not sharp (which feels aggressive) nor fully rounded (which feels too "consumer/friendly"). 

- **Standard Elements:** Use a `4px` (0.25rem) radius for a precise, machined look.
- **Large Containers:** Use `12px` (0.75rem) for product cards and main glass overlays.
- **Interactive Triggers:** Buttons and input fields follow the `4px` rule to maintain a serious, professional hardware aesthetic.

## Components

### Buttons
- **Primary:** Solid `#00D1FF` with black text. No border. On hover, the button should increase in brightness.
- **Secondary:** Transparent background with a `1px` white border. Text is white. On hover, background becomes `rgba(255, 255, 255, 0.1)`.

### Glass Cards
Used for product features and spec sheets. Must include a `1px` border of `rgba(255, 255, 255, 0.08)` and a `20px` backdrop-blur. Content inside should have ample padding (minimum `32px`).

### Input Fields
Darker than the background (`#000000`) with a bottom-only border of `rgba(255, 255, 255, 0.2)`. On focus, the bottom border transitions to `#00D1FF`.

### Status Chips
Used for "Live," "In Stock," or "VR Ready." Use the `label-mono` type style. Background is a faint tint of the status color (e.g., 10% Cyan) with a solid 1px border of the same color.

### Interactive Progress / Loaders
Always use `#00D1FF`. Use thin lines (`2px`) for a technical, high-precision feel.