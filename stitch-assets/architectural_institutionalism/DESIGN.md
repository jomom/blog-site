---
name: Architectural Institutionalism
colors:
  surface: '#f9f9fa'
  surface-dim: '#dadadb'
  surface-bright: '#f9f9fa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f4'
  surface-container: '#eeeeef'
  surface-container-high: '#e8e8e9'
  surface-container-highest: '#e2e2e3'
  on-surface: '#1a1c1d'
  on-surface-variant: '#444748'
  inverse-surface: '#2f3132'
  inverse-on-surface: '#f0f1f2'
  outline: '#747878'
  outline-variant: '#c4c7c7'
  surface-tint: '#5f5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1c1b1b'
  on-primary-container: '#858383'
  inverse-primary: '#c9c6c5'
  secondary: '#006c49'
  on-secondary: '#ffffff'
  secondary-container: '#6cf8bb'
  on-secondary-container: '#00714d'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#1d1b1a'
  on-tertiary-container: '#868381'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c9c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474646'
  secondary-fixed: '#6ffbbe'
  secondary-fixed-dim: '#4edea3'
  on-secondary-fixed: '#002113'
  on-secondary-fixed-variant: '#005236'
  tertiary-fixed: '#e6e1df'
  tertiary-fixed-dim: '#cac6c3'
  on-tertiary-fixed: '#1d1b1a'
  on-tertiary-fixed-variant: '#484645'
  background: '#f9f9fa'
  on-background: '#1a1c1d'
  surface-variant: '#e2e2e3'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 64px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: '1.3'
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: '0'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: '0'
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.1em
spacing:
  unit: 8px
  container-max: 1440px
  gutter: 32px
  margin-desktop: 64px
  margin-mobile: 24px
  section-padding: 128px
---

## Brand & Style
The brand personality is authoritative, structural, and intellectually rigorous. This design system rejects the ephemeral trends of consumer technology in favor of a permanent, institutional aesthetic inspired by high-stakes consultancy and systems engineering.

The visual style is **High-Contrast Institutional Minimalism**. It utilizes a "White Room" philosophy—expansive negative space that forces focus onto high-density information and structural precision. The emotional response is one of total reliability and elite technical expertise. The interface should feel like a high-end physical portfolio or a confidential technical whitepaper: structured, unyielding, and premium.

## Colors
The palette is hyper-restricted to maintain a serious, high-end tone. 
- **Deep Obsidian Charcoal (#0A0A0A)**: Used for all primary typography, structural borders, and heavy-weight iconography. It represents the "lead" or "ink" of the system.
- **Pure White (#FFFFFF)**: The singular background color. No subtle off-white tints are permitted for the main canvas to ensure maximum contrast.
- **Strategic Emerald (#10B981)**: Used with extreme restraint. This is a functional color reserved solely for active indicators, successful states, or critical micro-anchors. It should never be used for large surfaces.
- **Light Cool Gray (#F4F4F5)**: Used for subtle dividers and secondary containers where pure black borders would be too aggressive.

## Typography
Typography is the primary vehicle for the brand’s authority. 
- **Headings**: Set in Plus Jakarta Sans with heavy weights. Tight tracking (-0.02em to -0.04em) is mandatory for headlines to create a "locked-in" architectural feel. 
- **Body**: Set in Inter for its systematic neutrality. A relaxed line height (1.6) is used to ensure legibility during long-form technical reading.
- **Labels**: Small-scale labels should use uppercase with increased letter spacing to provide a structural, "blueprint" aesthetic.

## Layout & Spacing
The layout follows a strict 12-column fixed grid for desktop and a single-column fluid grid for mobile. 

The "Massive Structural Padding" principle requires significant vertical breathing room between sections (minimum 128px). Elements should align to the grid with zero deviation. Negative space is not "empty" here; it is a structural component that signifies premium quality and clarity of thought. Gutters are generous (32px) to prevent information density from feeling cluttered.

## Elevation & Depth
This design system avoids all shadows and blurs. Depth is conveyed exclusively through **Tonal Layering** and **1px Outlines**. 

- **Surface Levels**: All elements sit on the base #FFFFFF surface. 
- **Hierarchy**: Distinction is created by #0A0A0A borders (1px width). 
- **Interaction**: Depth is signaled by fill changes (e.g., a white button filling with black on hover) rather than rising off the page. The interface remains "flat" to mirror the precision of a technical drawing.

## Shapes
The shape language is strictly **Sharp**. A 0px radius is applied to all components, including buttons, input fields, cards, and avatars. This reinforces the institutional, uncompromising nature of the architectural profession. Circles are only permitted for specific functional icons or status dots (e.g., the Strategic Emerald micro-anchor).

## Components
- **Buttons**: Primary buttons are solid #0A0A0A with white text. Secondary buttons are 1px #0A0A0A outlines with no fill. All corners are sharp. Hover states involve a 100% color inversion.
- **Input Fields**: Simple bottom-border only or 1px charcoal bounding boxes. Labels are always positioned above the field in `label-caps` style.
- **Cards**: Cards do not have shadows. They are defined by 1px #F4F4F5 borders. For high-priority content, use 1px #0A0A0A borders.
- **Micro-Anchors**: Small indicators (active nav links, step indicators) use the Strategic Emerald Green (#10B981). This is the only place where this color appears.
- **Dividers**: Use 1px #F4F4F5 lines for secondary separation and 1px #0A0A0A lines for major content breaks.
- **Data Grids**: High-density tables should use horizontal lines only, emphasizing the horizontal flow of data over vertical containers.