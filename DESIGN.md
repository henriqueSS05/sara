---
name: High-Velocity Fiber
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#20201f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353535'
  on-surface: '#e5e2e1'
  on-surface-variant: '#e3bfb1'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#aa8a7d'
  outline-variant: '#5a4136'
  surface-tint: '#ffb596'
  primary: '#ffb596'
  on-primary: '#581e00'
  primary-container: '#ff6600'
  on-primary-container: '#561d00'
  inverse-primary: '#a33e00'
  secondary: '#c6c6c6'
  on-secondary: '#303030'
  secondary-container: '#474747'
  on-secondary-container: '#b5b5b5'
  tertiary: '#c6c6c7'
  on-tertiary: '#2f3131'
  tertiary-container: '#969797'
  on-tertiary-container: '#2e3030'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdbcd'
  primary-fixed-dim: '#ffb596'
  on-primary-fixed: '#360f00'
  on-primary-fixed-variant: '#7c2e00'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c6'
  on-secondary-fixed: '#1b1b1b'
  on-secondary-fixed-variant: '#474747'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353535'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 64px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '800'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.3'
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '700'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-bold:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 40px
  section-gap: 120px
---

## Brand & Style
The design system is engineered to evoke a sense of unmatched speed, technical precision, and regional reliability. Targeting tech-savvy households and modern businesses, the aesthetic balances the "dark mode" sophistication of high-end hardware with the approachable warmth of community-focused service.

The design style is a hybrid of **Corporate Modern** and **Glassmorphism**. It utilizes deep black surfaces to represent the "void" of fiber optic cables, where light (data) travels at immense speeds. High-contrast white typography ensures absolute legibility, while vibrant orange accents serve as the "spark" of connectivity. Visuals should lean into technical "glow" effects and crisp, high-resolution imagery of glass fibers and glowing data streams.

## Colors
The palette is rooted in a high-contrast, dark-first philosophy. 

- **Primary (Action):** Vibrant Orange (#FF6600) is reserved for primary calls to action, active states, and critical path indicators. It represents energy and the "live" connection.
- **Background:** Pure Deep Black (#000000) provides the canvas, eliminating visual noise and emphasizing the content.
- **Surface/Neutral:** Dark Gray (#1A1A1A) is used for container backgrounds and secondary surfaces to create subtle depth against the pure black base.
- **Text:** Crisp White (#FFFFFF) is used for all primary body text and headlines to maintain maximum WCAG AA/AAA contrast ratios against the dark background.

## Typography
Inter is used across the entire system to ensure a systematic, utilitarian, and highly readable experience. 

Headlines utilize a heavy weight (700-800) with tight letter spacing to suggest stability and power. Display sizes should be used sparingly for hero sections to emphasize speed claims (e.g., "1 GIG"). Body text remains at a generous line height for maximum comfort on dark backgrounds. Small labels and "overlines" should use the bold, uppercase treatment to denote technical categories or plan types.

## Layout & Spacing
The layout follows a strict 12-column fluid grid for desktop and a single-column stack for mobile. 

Spacing is based on an 8px rhythmic scale. Large "Section Gaps" (120px) are used to separate major product offerings, allowing the dark background to create a sense of premium "breathing room." Content containers should be centered with a maximum width of 1280px. On mobile, horizontal margins are reduced to 16px to maximize the impact of full-width call-to-action buttons.

## Elevation & Depth
This design system utilizes **Glassmorphism** to create depth without relying on traditional drop shadows, which can look muddy on pure black backgrounds.

- **Level 1 (Base):** Pure Black #000000.
- **Level 2 (Cards):** Semi-transparent Dark Gray (10% white overlay) with a 20px backdrop blur and a 1px "inner-glow" border (White at 10% opacity).
- **Level 3 (Interactive):** Active cards or modals increase the border opacity and may include a subtle outer glow using a desaturated version of the Primary Orange to suggest "active power."

## Shapes
A "Rounded" profile (0.5rem base) is applied to all interactive elements to balance the technical "coldness" of the dark theme with a user-friendly, approachable feel. 

Buttons and input fields should feel substantial and tactile. Glassmorphism cards use the `rounded-xl` (1.5rem) setting to create a distinct separation from the structural grid and to look like sleek, modern hardware.

## Components

### Buttons
- **Primary:** Solid Vibrant Orange (#FF6600) with Black text. Bold weight. On mobile, these must be full-width (block level) for thumb-friendly interaction.
- **Secondary:** Ghost style with a 1px White border and White text.

### Glassmorphism Cards
Used for "Plan Benefits" and "Technical Specs." Features a 1px subtle border, 20px blur, and high-contrast white text. When hovered, the border should transition to Primary Orange.

### Step-by-Step Indicators
For the "Process" or "Installation" sections, use a vertical or horizontal line connected by "nodes." Completed steps are filled with Primary Orange; pending steps are outlined in White.

### Input Fields
Dark backgrounds (#1A1A1A) with 1px White borders (20% opacity). On focus, the border becomes solid Orange with a subtle outer glow.

### Chips/Tags
Small, rounded-pill containers with Orange text and a 10% Orange background tint, used to highlight "New" features or "Fiber" availability.