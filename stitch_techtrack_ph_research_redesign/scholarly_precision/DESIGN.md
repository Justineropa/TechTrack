---
name: Scholarly Precision
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#434655'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#737686'
  outline-variant: '#c3c6d7'
  surface-tint: '#0053db'
  primary: '#004ac6'
  on-primary: '#ffffff'
  primary-container: '#2563eb'
  on-primary-container: '#eeefff'
  inverse-primary: '#b4c5ff'
  secondary: '#4059aa'
  on-secondary: '#ffffff'
  secondary-container: '#8fa7fe'
  on-secondary-container: '#1d3989'
  tertiary: '#0051b1'
  on-tertiary: '#ffffff'
  tertiary-container: '#0f69dc'
  on-tertiary-container: '#edf0ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#b4c5ff'
  on-primary-fixed: '#00174b'
  on-primary-fixed-variant: '#003ea8'
  secondary-fixed: '#dce1ff'
  secondary-fixed-dim: '#b6c4ff'
  on-secondary-fixed: '#00164e'
  on-secondary-fixed-variant: '#264191'
  tertiary-fixed: '#d8e2ff'
  tertiary-fixed-dim: '#adc6ff'
  on-tertiary-fixed: '#001a42'
  on-tertiary-fixed-variant: '#004395'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  title-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
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
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  margin: 1.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system supports a modern academic technology research platform built for researchers, faculty, and technical scholars. The brand personality is authoritative, intellectually rigorous, and approachable—balancing institutional credibility with contemporary digital clarity.

The UI evokes a sense of focused calm, structured inquiry, and effortless navigation through dense technical and scholarly material. It combines **Corporate / Modern** structure with **Minimalism**, utilizing generous whitespace, crisp hairline borders, subtle tonal gradients, and restrained interactive states. High-contrast deep navy navigation and footer anchors frame a bright, distraction-free reading and data-exploration canvas.

## Colors

The palette pairs a bright, high-legibility light canvas with deep navy structural anchors and muted blue interactive accents.

- **Canvas & Surfaces:** Primary content backgrounds use pure white (`#ffffff`) for reading surfaces and cards, layered over light slate grays (`#f8fafc` and `#f1f5f9`) for page backgrounds, sidebars, and secondary content panels.
- **Structural Anchors:** The top navigation bar and global footer use deep navy (`#0f172a` and `#1e293b`) and dark blue (`#1e3a8a`) to ground the interface and establish clear visual boundaries.
- **Accents & Interactive States:** Muted royal blue (`#2563eb`) and vibrant blue (`#3b82f6`) drive primary actions, active links, and focus indicators. Slate gray (`#64748b`) handles secondary metadata, captions, and muted icons.
- **Borders & Dividers:** Subtle cool-gray hairline borders (`#e2e8f0`) separate structured content panels without visual heaviness.

## Typography

The typographic hierarchy pairs **Plus Jakarta Sans** for headings and titles with **Inter** for body copy, data tables, and UI labels.

- **Headlines:** Plus Jakarta Sans provides geometric clarity and a welcoming, contemporary academic tone. Tight negative letter spacing (`-0.01em` to `-0.02em`) keeps large display titles cohesive.
- **Body & Long-Form Reading:** Inter is optimized for sustained screen reading of research abstracts, technical documentation, and multi-column layouts. Maintain a comfortable line length of 65–75 characters for `body-md` and `body-lg`.
- **Labels & Metadata:** Use `label-md` and `label-sm` in uppercase or semi-bold weights for publication dates, citation counts, and taxonomy tags.
- **Responsive Scaling:** Display and large headline roles step down on mobile viewports (`display-lg-mobile`, `headline-lg-mobile`) to preserve vertical rhythm and prevent awkward wrapping.

## Layout & Spacing

The layout uses a **12-column fluid grid** constrained to a maximum container width of `1280px` on desktop viewports, ensuring structured alignment for research catalogs, dashboards, and editorial articles.

- **Grid & Rhythm:** Columns are separated by a `1.5rem` (24px) gutter with `1.5rem` outer margins on mobile, expanding to `2rem`–`3rem` on tablet and desktop.
- **Breakpoints:**
  - **Mobile (`< 640px`):** 4-column grid; single-column stacked cards and full-width panels.
  - **Tablet (`640px – 1024px`):** 8-column grid; 2-column card grids and collapsible sidebars.
  - **Desktop (`> 1024px`):** 12-column grid; 3- or 4-column research grids, persistent left/right filter panels, and split-pane reading views.
- **Spacing Scale:** Internal component padding uses `space-md` (`1rem`) to `space-lg` (`1.5rem`), while section-level vertical separation uses `space-xl` (`2.5rem`) or multiples thereof.

## Elevation & Depth

Visual hierarchy relies on **tonal layers** and **low-contrast outlines** rather than heavy drop shadows, keeping the interface crisp and focused.

- **Surface Stacking:** Distinct background tiers—`#f8fafc` for the base canvas, `#f1f5f9` for recessed panels, and `#ffffff` for elevated cards—create natural separation.
- **Crisp Borders:** Cards, tables, and structured content panels use `1px solid` borders in cool light gray (`#e2e8f0`) to define boundaries cleanly.
- **Subtle Shadows & Gradients:** Interactive cards and dropdown menus may use extra-diffused ambient shadows (`0 4px 12px rgba(15, 23, 42, 0.05)`) paired with subtle top-to-bottom surface gradients on hero banners.
- **Restrained Hover States:** Hovering over interactive cards slightly darkens the border to `#cbd5e1` or `#93c5fd` and applies a gentle `1px`–`2px` upward translation without dramatic shadow blooms.

## Shapes

The shape language uses **Rounded** (`0.5rem` / 8px base radius) geometry to soften the dense, structured nature of academic and technical content.

- **Standard Elements (`0.5rem`):** Buttons, input fields, dropdowns, and compact chips use the base `0.5rem` radius.
- **Containers (`1rem`):** Research cards, structured content panels, and modal dialogs use `rounded-lg` (`1rem`) for a clean, modern frame.
- **Pills & Badges:** Status indicators and taxonomy tags may use full pill rounding (`9999px`) when paired with `label-sm` typography.

## Components

- **Buttons:** Primary buttons use `#2563eb` with `#ffffff` text, `0.5rem` radius, and `label-lg` typography, shifting to `#1d4ed8` on hover. Secondary buttons use `#ffffff` backgrounds with `1px solid #cbd5e1` borders and `#0f172a` text. Ghost buttons use `#2563eb` text on transparent backgrounds with a `#f1f5f9` hover fill.
- **Chips & Tags:** Research topic tags and filter chips use `#f1f5f9` backgrounds with `#334155` text and `1px solid #e2e8f0` borders. Active filter chips invert to `#eff6ff` backgrounds with `#2563eb` text and `#bfdbfe` borders.
- **Cards:** Research paper and project cards use `#ffffff` backgrounds, `1rem` radius, `1px solid #e2e8f0` borders, and `1.5rem` internal padding. Include clear typographic hierarchy: category label (`label-sm`), title (`title-lg`), abstract snippet (`body-sm`), and author/date metadata (`#64748b`).
- **Lists & Tables:** Data-heavy lists and publication tables use alternating `#ffffff` and `#f8fafc` row fills, `1px solid #e2e8f0` horizontal dividers, and generous `0.75rem`–`1rem` vertical cell padding.
- **Input Fields:** Search bars and form inputs use `#ffffff` backgrounds, `1px solid #cbd5e1` borders, `0.5rem` radius, and `#0f172a` text. Focus states apply a `2px` `#3b82f6` ring.
- **Checkboxes & Radio Buttons:** Unchecked controls use `1px solid #cbd5e1` borders on `#ffffff`. Checked states fill with `#2563eb` and crisp `#ffffff` indicators.
- **Navigation Bar & Footer:** The top navigation bar uses `#0f172a` or `#1e293b` with `#ffffff` links and `#3b82f6` active indicators. The global footer uses `#0f172a` with `#94a3b8` secondary text and `#1e3a8a` accent dividers.