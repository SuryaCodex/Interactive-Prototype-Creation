---
name: DesignFlow
colors:
  surface: '#0b1326'
  surface-dim: '#0b1326'
  surface-bright: '#31394d'
  surface-container-lowest: '#060e20'
  surface-container-low: '#131b2e'
  surface-container: '#171f33'
  surface-container-high: '#222a3d'
  surface-container-highest: '#2d3449'
  on-surface: '#dae2fd'
  on-surface-variant: '#c2c6d8'
  inverse-surface: '#dae2fd'
  inverse-on-surface: '#283044'
  outline: '#8c90a1'
  outline-variant: '#424656'
  surface-tint: '#b3c5ff'
  primary: '#b3c5ff'
  on-primary: '#002b75'
  primary-container: '#0066ff'
  on-primary-container: '#f8f7ff'
  inverse-primary: '#0054d6'
  secondary: '#7bd1fa'
  on-secondary: '#003547'
  secondary-container: '#00799e'
  on-secondary-container: '#e9f6ff'
  tertiary: '#c0c1ff'
  on-tertiary: '#1000a9'
  tertiary-container: '#5d60eb'
  on-tertiary-container: '#faf6ff'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#dae1ff'
  primary-fixed-dim: '#b3c5ff'
  on-primary-fixed: '#001849'
  on-primary-fixed-variant: '#003fa4'
  secondary-fixed: '#c0e8ff'
  secondary-fixed-dim: '#7bd1fa'
  on-secondary-fixed: '#001e2b'
  on-secondary-fixed-variant: '#004d66'
  tertiary-fixed: '#e1e0ff'
  tertiary-fixed-dim: '#c0c1ff'
  on-tertiary-fixed: '#07006c'
  on-tertiary-fixed-variant: '#2f2ebe'
  background: '#0b1326'
  on-background: '#dae2fd'
  surface-variant: '#2d3449'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 30px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0.01em
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.03em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 40px
  2xl: 64px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
---

## Brand & Style
The design system is built for a high-performance UX/UI project management environment. The brand personality is rooted in **Professionalism** and **Efficiency**, serving as a quiet, powerful canvas for creative work. It utilizes a **Modern Minimalist** aesthetic blended with **Glassmorphism** to create a sense of depth without clutter.

The emotional response should be one of "focused inspiration"—the UI feels like a premium studio space where the tools are sharp, the surfaces are clean, and the workflow is unobstructed. Visual interest is achieved through the contrast between deep, structural slate tones and high-energy electric accents.

## Colors
The palette is optimized for a dark-mode-first professional environment to reduce eye strain during long design sessions.

- **Primary (Electric Blue):** Used exclusively for high-priority actions, focus states, and progress indicators. It represents energy and movement.
- **Neutral (Slate & Ink):** The foundation of the UI. Backgrounds use the deepest shades, while surfaces use lighter slate to establish hierarchy.
- **Supportive Accents:** Soft grays are used for secondary text and borders to maintain a low-friction visual density.
- **Status Colors:** Success (Emerald), Warning (Amber), and Error (Rose) are used sparingly, maintaining the same vibrancy as the primary blue.

## Typography
This design system utilizes **Inter** for its neutral, systematic utility. The typographic scale is designed for high legibility in data-dense project views.

- **Tracking:** Generous tracking is applied to body text and labels to increase "air" within the UI.
- **Hierarchy:** Display styles use tight tracking and bold weights to create impact, while body text remains regular weight for maximum readability.
- **Labels:** Small labels and captions use increased letter-spacing (0.05em) and medium weights to ensure they don't disappear against dark backgrounds.

## Layout & Spacing
The layout follows a **Fluid Grid** model with a 12-column structure for desktop. 

- **Spacing Rhythm:** Based on a 4px baseline, with most components using 16px (md) or 24px (lg) increments to create a spacious, airy feel.
- **Breakpoints:**
    - Mobile: < 768px (4 columns, 16px margins)
    - Tablet: 768px - 1280px (8 columns, 24px margins)
    - Desktop: > 1280px (12 columns, 48px margins, 1440px max-width)
- **Reflow:** Cards and grid items should wrap fluidly. In project views, sidebars are collapsible to give maximum real estate to the canvas or task board.

## Elevation & Depth
Depth is created through **Glassmorphism** and **Tonal Layering** rather than heavy shadows.

- **Surface 0 (Background):** Pure slate-dark (#020617).
- **Surface 1 (Base Cards):** Semi-transparent slate with a 12px backdrop blur and a 1px subtle border (#FFFFFF10).
- **Surface 2 (Popovers/Modals):** Higher transparency with a more pronounced 20px blur and a subtle "inner glow" border.
- **Shadows:** Use ultra-soft, large-radius ambient shadows (0px 20px 40px rgba(0,0,0,0.4)) only on floating elements like modals or dropdowns to separate them from the grid.

## Shapes
The shape language is consistently soft but professional. 

- **Base Radius:** 0.5rem (8px) for small components like inputs and tags.
- **Component Radius:** 0.75rem (12px) for cards, buttons, and main UI containers.
- **Pill Shapes:** Used exclusively for status indicators (tags) and search bars to differentiate them from actionable buttons.

## Components
- **Buttons:** 
    - *Primary:* Electric Blue background, white text, no border. High contrast.
    - *Secondary:* Ghost style with 1px slate-300 border and subtle hover fill.
- **Cards:** Glassmorphic appearance. 12px border radius, 1px stroke (white at 10% opacity), and a background blur of 12px.
- **Inputs:** Darker than the card surface. Subtle 1px border that glows Electric Blue on focus. Labels sit 4px above the field.
- **Chips/Tags:** Small, pill-shaped with low-opacity versions of status colors (e.g., Success is a dark emerald background with bright emerald text).
- **Lists:** Clean rows separated by 1px slate borders. Hover states use a subtle lightening of the background color (Slate-800).
- **Icons:** Minimalist 2px stroke line icons. Use primary blue for active icon states and slate-400 for inactive.
- **Navigation:** Vertical sidebar with active states indicated by a thick 4px left-border "indicator" in Electric Blue.