---
name: EcoWire Minimal
colors:
  surface: '#fbf9f7'
  surface-dim: '#dbdad8'
  surface-bright: '#fbf9f7'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f1'
  surface-container: '#efeeeb'
  surface-container-high: '#e9e8e6'
  surface-container-highest: '#e4e2e0'
  on-surface: '#1b1c1b'
  on-surface-variant: '#414940'
  inverse-surface: '#30312f'
  inverse-on-surface: '#f2f0ee'
  outline: '#71796f'
  outline-variant: '#c1c9bd'
  surface-tint: '#36693d'
  primary: '#013a13'
  on-primary: '#ffffff'
  primary-container: '#1e5128'
  on-primary-container: '#8cc38f'
  inverse-primary: '#9cd49e'
  secondary: '#526253'
  on-secondary: '#ffffff'
  secondary-container: '#d3e5d0'
  on-secondary-container: '#576757'
  tertiary: '#243427'
  on-tertiary: '#ffffff'
  tertiary-container: '#3a4b3d'
  on-tertiary-container: '#a7baa8'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#b8f1b9'
  primary-fixed-dim: '#9cd49e'
  on-primary-fixed: '#002108'
  on-primary-fixed-variant: '#1e5128'
  secondary-fixed: '#d6e7d3'
  secondary-fixed-dim: '#bacbb8'
  on-secondary-fixed: '#101f12'
  on-secondary-fixed-variant: '#3b4b3c'
  tertiary-fixed: '#d4e8d5'
  tertiary-fixed-dim: '#b8ccb9'
  on-tertiary-fixed: '#0f1f13'
  on-tertiary-fixed-variant: '#394b3d'
  background: '#fbf9f7'
  on-background: '#1b1c1b'
  surface-variant: '#e4e2e0'
typography:
  headline-xl:
    fontFamily: Atkinson Hyperlegible Next
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Atkinson Hyperlegible Next
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Atkinson Hyperlegible Next
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Atkinson Hyperlegible Next
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 30px
    letterSpacing: -0.005em
  headline-sm:
    fontFamily: Atkinson Hyperlegible Next
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
  body-lg:
    fontFamily: Atkinson Hyperlegible Next
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Atkinson Hyperlegible Next
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Atkinson Hyperlegible Next
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Atkinson Hyperlegible Next
    fontSize: 15px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Atkinson Hyperlegible Next
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Atkinson Hyperlegible Next
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.04em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system embodies low-carbon digital design (Green IT) fused with radical accessibility (WCAG 2.2 Level AAA). It presents an unembellished, low-fidelity wireframe vernacular: structured, precise, honest, and lightweight. Visual clutter is completely discarded to minimize client-side rendering costs and visual fatigue. 

The aesthetic is functional, architectural, and deliberate. It evokes clarity, absolute legibility, environmental sobriety, and methodical structural discipline. Interfaces built with this system clearly distinguish content scaffolding from decorative excess, creating trust through utilitarian transparency and rapid comprehension.

## Colors

The color palette operates strictly under WCAG AAA contrast guidelines (minimum 7:1 for normal body text, 4.5:1 for large text and interface components) across an off-white, light-canvas environment. 

- **Canvas & Surface:** Built on clean, unbleached off-white tones (`#FBFBF9` base canvas, `#F2F2ED` secondary surface container) that reduce white pixel emission strain while avoiding heavy visual processing overhead.
- **Primary Accent (`#1E5128`):** A sober, low-saturation botanical evergreen used sparingly for structural emphasis, primary actions, and confirmed states.
- **Structural Lines & Neutral Ink (`#121312` and `#3E433E`):** Neutral dark values provide crisp wireframe strokes, high-legibility text hierarchy, and prominent outlines.
- **Accessible Indicators:** Focus rings leverage an unmistakable dual-layer high-contrast border scheme (`#121312` solid outline with a `#FFFFFF` separation ring) exceeding accessibility mandates.

## Typography

Typography prioritizes hyper-legibility, visual distinction between ambiguous character forms (such as `1`, `l`, and `I`), and effortless reading comfort across all ambient lighting conditions.

- **Typeface Selection:** Atkinson Hyperlegible Next is utilized systematically across headlines, body copy, and labels. Its carefully shaped glyphs ensure immediate comprehension for neurodivergent individuals and users with low visual acuity.
- **Hierarchy & Scale:** Hierarchy is articulated through discrete font weights (`400`, `600`, and `700`) and size differentiation rather than chromatic shifts. Body text never drops below 14px, keeping baseline line heights generous (at least 1.5x font size for longform prose) to satisfy WCAG AAA standards.

## Layout & Spacing

The layout is built on a responsive 12-column structural grid system on desktop (`1200px` max container) that scales down cleanly:
- **Desktop (1024px+):** 12 columns, 24px gutters, 32px outer canvas margin.
- **Tablet (768px - 1023px):** 8 columns, 20px gutters, 24px outer canvas margin.
- **Mobile (below 768px):** 4 columns, 16px gutters, 16px outer canvas margin.

Spacing follows an unambiguous 8pt spatial baseline rhythm (`0.5rem`, `1rem`, `1.5rem`, `2.5rem`). Touch targets strictly maintain a minimum boundary of 44x44 CSS pixels with mandatory 8px margins between interactive targets to prevent accidental activations. Content stretches predictably without unpredictable fluid shifts, minimizing unnecessary layout recalculations.

## Elevation & Depth

To remain faithful to green IT principles and low-fidelity wireframing, this design system does not use drop shadows, multi-layered blurs, or skeuomorphic gradients. Eliminating GPU-intensive blur calculations reduces CPU cycle consumption and battery draw.

- **Flat Wireframe Stratification:** Spatial depth is conveyed exclusively using crisp, 1px or 2px solid boundary lines (`#121312` and `#70756F`).
- **Surface Nesting:** Modals and elevated sheets sit atop an unblurred, solid flat backdrop overlay (`rgba(18, 19, 18, 0.45)`) and feature a distinct 2px solid `#121312` outline accompanied by a flat interior background of `#FBFBF9`.
- **Hover & Active States:** Depth transformations occur via sharp inverse fills (e.g., transition from transparent wireframe to solid `#121312` fill with white text) or offset outline shifts rather than diffuse elevation.

## Shapes

The geometric framework favors structural precision with subtle 0.25rem (`4px`) rounded corners for interactive components like buttons, input fields, and chips. 

Structural containers, cards, dialog banners, and layout viewports employ sharp 0px corners, maintaining an authentic blueprint wireframe texture. Badges and status pills leverage modest containment without drifting into purely decorative circular geometry.

## Components

### Buttons
- **Primary:** Solid `#1E5128` background, `#FFFFFF` text, 2px border in `#1E5128`. Padding: 12px 24px. Height: 48px minimum. Focus ring: 3px outer border in `#121312` with 2px clear offset.
- **Secondary / Wireframe:** Background `#FBFBF9`, 2px solid `#121312` border, text `#121312`. On hover: solid fill `#121312` with text `#FFFFFF`.
- **Tertiary / Ghost:** Text `#1E5128` with underline decoration, transparent background, maintaining 48px interactive target size.

### Inputs & Text Areas
- **Container:** Background `#FFFFFF`, 2px solid `#3E433E` border, 4px border-radius.
- **Labels:** Persistent high-contrast labels placed strictly above inputs in `label-md`, never relying on disappearing placeholders.
- **Focus State:** 3px outline in `#1E5128` with 2px whitespace offset. Error states use a high-contrast thick double outline in `#121312` alongside an explicit error icon and accompanying text.

### Checkboxes & Radio Buttons
- **Geometry:** 24x24px dimensions to ensure touch accessibility.
- **State:** Checkboxes have 2px border `#121312`. When checked: solid `#1E5128` background with an unstylized, high-visibility white check glyph. Radio buttons utilize a solid centered concentric `#1E5128` disc when selected.

### Chips & Badges
- **Structure:** 1px solid border `#506253`, background `#F2F2ED`, text `#121312`.
- **Active State:** Solid `#2B3A2C` background with inverted `#FFFFFF` text.

### Cards & Grouping Containers
- **Wireframe Box:** 1px or 2px solid `#121312` border, zero box-shadow, background `#FBFBF9`.
- **Header Separator:** 1px solid horizontal rule `#70756F` separating container titles from body content.

### Focus Indicators & Low-Carbon Assets
- **Universal Focus:** Any keyboard-focused element receives a visible, deterministic 3px outline (`#121312`) positioned with a 2px offset.
- **Media Placeholders:** Placeholder media boxes render a subtle structural `X` corner-to-corner wireframe graphic with monochrome vector glyphs instead of bloated placeholder bitmaps.