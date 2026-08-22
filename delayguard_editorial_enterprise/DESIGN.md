---
name: DelayGuard Editorial Enterprise
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f3'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#564242'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f1f1f1'
  outline: '#897172'
  outline-variant: '#dcc0c0'
  surface-tint: '#a13c46'
  primary: '#5b0617'
  on-primary: '#ffffff'
  primary-container: '#7a1f2b'
  on-primary-container: '#ff8b92'
  inverse-primary: '#ffb3b5'
  secondary: '#5e5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e2e2e2'
  on-secondary-container: '#646464'
  tertiary: '#003227'
  on-tertiary: '#ffffff'
  tertiary-container: '#004b3b'
  on-tertiary-container: '#7cbaa5'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdada'
  primary-fixed-dim: '#ffb3b5'
  on-primary-fixed: '#40000c'
  on-primary-fixed-variant: '#822530'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c6'
  on-secondary-fixed: '#1b1b1b'
  on-secondary-fixed-variant: '#474747'
  tertiary-fixed: '#b0f0d9'
  tertiary-fixed-dim: '#94d3be'
  on-tertiary-fixed: '#002018'
  on-tertiary-fixed-variant: '#0a5040'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  display-lg:
    fontFamily: EB Garamond
    fontSize: 48px
    fontWeight: '400'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: EB Garamond
    fontSize: 32px
    fontWeight: '400'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: EB Garamond
    fontSize: 28px
    fontWeight: '400'
    lineHeight: '1.2'
  headline-md:
    fontFamily: EB Garamond
    fontSize: 24px
    fontWeight: '400'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-md:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
  note-italic:
    fontFamily: Literata
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.4'
spacing:
  unit: 4px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 40px
  container-max: 1440px
---

## Brand & Style

The design system is rooted in **Modern Minimalism** with an **Editorial** lens. It prioritizes clarity, authority, and professional restraint to serve an enterprise audience. The aesthetic avoids the typical "tech-startup" softness in favor of a structured, literary-inspired layout that treats data with the same respect as high-end journalism.

The emotional response should be one of calm confidence and objective truth. By stripping away decorative gradients, shadows, and vibrant "traffic light" colors, the UI forces focus onto the content and metrics. The style utilizes heavy whitespace, high-contrast monochrome pairings, and precise alignment to establish a sophisticated and trustworthy environment.

## Colors

This design system employs a strict 95/5 color rule. The palette is almost entirely monochromatic to ensure the interface feels grounded and institutional.

- **Primary (Burgundy #7A1F2B):** Used exclusively for meaningful accents, high-priority status indicators, and critical call-to-actions. It must be used sparingly to maintain its impact.
- **Surface & Backgrounds:** The primary workspace is pure white (#FFFFFF). The light neutral (#F5F5F5) is used for secondary regions like sidebars or table headers to provide subtle structural contrast without introducing depth.
- **Typography & Borders:** Pure black (#000000) is reserved for primary headings and structural borders. Secondary text (#454545) provides a softer hierarchy for body copy and metadata.

## Typography

The typographic strategy balances the intellectual heritage of **EB Garamond** with the functional precision of **Hanken Grotesk**. 

1. **Editorial Headers:** Use EB Garamond for all major page titles and section headings. It should be sized generously with tighter letter-spacing for a "masthead" feel.
2. **Functional UI:** Hanken Grotesk handles all interactive elements, navigation, and data density. Use its various weights to establish hierarchy rather than color.
3. **Contextual Nuance:** Literata Italic is used for footnotes, "as-of" dates, and subtle annotations. It provides a human, literary touch to a high-data environment.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy for desktop to maintain editorial integrity, transitioning to a fluid model for mobile.

- **Grid:** A 12-column grid with 24px gutters. Content should be grouped in clear vertical blocks, often separated by 1px solid horizontal rules.
- **Rhythm:** Spacing is strictly based on 4px increments. Large sections are separated by significant whitespace (64px+) to prevent the enterprise data from feeling cluttered.
- **Alignment:** Consistent left-alignment is mandatory for all text-heavy editorial layouts. Only use center-alignment for specific marketing-style hero moments.

## Elevation & Depth

This design system is strictly **Flat**. It rejects all use of shadows, blurs, or gradients.

- **Depth through Layering:** Depth is conveyed through tonal separation (White surfaces on Light Gray backgrounds) and the use of 1px solid borders (#000000).
- **Outlines:** Use 1px borders to define containers. Do not use rounded corners beyond the 2px maximum.
- **Z-Index:** For necessary overlays (modals or dropdowns), use a thick 2px solid black border to differentiate the element from the background, rather than a shadow.

## Shapes

The shape language is primarily **Sharp (0px)**. 

A maximum of 2px radius may be applied only to small interactive elements like checkboxes or input fields to provide a hint of approachability. Large layout containers and primary buttons must remain perfectly square to uphold the architectural, editorial aesthetic.

## Components

### Buttons & Interaction
- **Primary:** Solid black background, white Hanken Grotesk text, square corners. No hover movement; use a subtle opacity shift (90%) or a burgundy border on hover.
- **Secondary:** 1px black border, white background, black text.
- **Ghost:** Black text, no border. Used for low-priority actions.

### Data Tables
- **Structure:** 1px horizontal black rules only. No vertical rules. 
- **Header:** #F5F5F5 background, uppercase Hanken Grotesk (label-md).
- **Ranking:** Use font weight (Bold) and Burgundy text for top-tier or high-delay items instead of background colors.

### Status Indicators
- Status is communicated through typography. 
- **Critical:** Bold, Burgundy (#7A1F2B) text.
- **Standard:** Regular, Secondary Text (#454545).
- **Positive:** Regular, Black (#000000) text with a small unicode checkmark if necessary. Avoid "Green/Yellow/Red" systems.

### Form Elements
- **Inputs:** 1px solid gray or black border. Square. No focus glow; use a 2px black border on focus.
- **Labels:** Hanken Grotesk, Bold, 12px, uppercase.

### Navigation
- Top-level navigation uses Hanken Grotesk with ample letter spacing. 
- Active states are indicated by a 2px Burgundy underline or a simple weight change.