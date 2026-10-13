---
name: Architectural Precision
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
  on-surface-variant: '#3e494a'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#6e797b'
  outline-variant: '#bdc9ca'
  surface-tint: '#006972'
  primary: '#006872'
  on-primary: '#ffffff'
  primary-container: '#00838f'
  on-primary-container: '#ffffff'
  inverse-primary: '#75d5e2'
  secondary: '#545f73'
  on-secondary: '#ffffff'
  secondary-container: '#d5e0f8'
  on-secondary-container: '#586377'
  tertiary: '#006873'
  on-tertiary: '#ffffff'
  tertiary-container: '#008391'
  on-tertiary-container: '#ffffff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#92f1fe'
  primary-fixed-dim: '#75d5e2'
  on-primary-fixed: '#001f23'
  on-primary-fixed-variant: '#004f56'
  secondary-fixed: '#d8e3fb'
  secondary-fixed-dim: '#bcc7de'
  on-secondary-fixed: '#111c2d'
  on-secondary-fixed-variant: '#3c475a'
  tertiary-fixed: '#97f0ff'
  tertiary-fixed-dim: '#66d6e7'
  on-tertiary-fixed: '#001f24'
  on-tertiary-fixed-variant: '#004f58'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
  slate-900: '#0f172a'
  slate-800: '#1e293b'
  slate-700: '#334155'
  slate-100: '#f1f5f9'
  surface-bg: '#f8fafc'
  border-subtle: '#e2e8f0'
  bronze-accent: '#8b5a2b'
  teal-deep: '#006978'
typography:
  headline-xl:
    fontFamily: Outfit
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
  headline-xl-mobile:
    fontFamily: Outfit
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg:
    fontFamily: Outfit
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
  headline-lg-mobile:
    fontFamily: Outfit
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 34px
  headline-md:
    fontFamily: Outfit
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: Outfit
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  title-md:
    fontFamily: Outfit
    fontSize: 18px
    fontWeight: '500'
    lineHeight: 24px
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
    fontWeight: '600'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
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

This design system embodies the disciplined precision of modern architectural engineering and high-end contracting. Built for premier commercial, residential, and high-rise renovation clientele in Calgary, the visual posture communicates structural permanence, absolute transparency, and meticulous craftsmanship.

The aesthetic philosophy draws on **Modern Corporate Minimalism with Architectural Precision**. Rather than relying on generic trade imagery or rough-hewn work-site tropes, it utilizes clean surfaces, surgical structural lines, structured grids, and high-legibility typography. Interfaces evoke the calm confidence of an architect's drafting studio: expansive breathing room, rich slate anchoring, and sharp, technical teal-cyan highlights drawn directly from the corporate identity mark.

## Colors

The palette transforms the brand mark into a rigorous, balanced architectural color space.

- **Primary (`#00838f`)**: A deep, saturated mineral teal derived directly from the primary glyphs in the corporate emblem. Used for high-priority interactive components, active nav states, and critical actions.
- **Secondary (`#1e293b`)**: An authoritative dark architectural slate. Serves as the structural skeleton across headers, high-impact cards, structural dividers, and prominent editorial sections.
- **Tertiary (`#0097a7`)**: A luminous cyan-teal used for focus states, hover transitions, and technical badges.
- **Neutral (`#64748b`)**: Calibrated slate grey ensuring legible secondary typography, non-distracting icons, and measured containment boundaries.
- **Named Accents**: `bronze-accent` (`#8b5a2b`) preserves the legacy raw timber/earth undertone from earlier branding for certifications and custom tags, while `surface-bg` (`#f8fafc`) and `border-subtle` (`#e2e8f0`) keep screens airy, crisp, and uncluttered.

## Typography

Typography establishes an intentional contrast between structural authority and functional technical clarity:

- **Display & Headlines (Outfit)**: Pure geometric proportions, crisp terminal cuts, and open apertures project architectural precision without feeling cold or austere. Heavy weights (`600`, `700`) command presence on project portfolio displays and structural service titles.
- **Body & Labels (Inter)**: The standard of digital utility and industrial legibility. High x-height and clear character distinctions deliver effortless scanning across technical specifications, contract details, schedules, and estimation forms.
- Tracking on all uppercase labels and category tags is slightly expanded (`+0.05em`) to evoke formal architectural schematics.

## Layout & Spacing

The spatial engine mirrors blueprint layout discipline, adhering to an 8px modular baseline across fluid grid tiers.

- **Desktop (>= 1200px)**: 12-column responsive grid with a 1280px max-width content container, `2rem` outer margins, and `1.5rem` gutters. Sections leverage generous vertical rhythm (`space-xl` and multipliers) to create an editorial, high-end firm presence.
- **Tablet (768px - 1199px)**: 8-column layout with `1.5rem` margins and `1.25rem` gutters. Media blocks compress gracefully into 2-up configurations.
- **Mobile (< 768px)**: 4-column layout with `1rem` margins and `1rem` gutters. Interactive actions become edge-to-edge full width touch targets with guaranteed minimum tap sizes of 48px.

## Elevation & Depth

Visual hierarchy rejects exaggerated, heavy shadows in favor of architectural surface stratification and tactile planes:

- **Surface Layering**: The primary foundation is built with `surface-bg` (`#f8fafc`). Elevated content cards rest on pure `#ffffff`. Secondary framing panels use low-tint slate fills (`slate-100`).
- **Low-Contrast Technical Borders**: Surfaces are bordered by a crisp `1px solid #e2e8f0` stroke, reinforcing deliberate craftsmanship and structural boundaries.
- **Ambient Diffusion**: Where elevation is required (such as project modal sheets or floating quote requests), shadows remain ultra-soft and slate-tinted: `0 10px 25px -5px rgba(30, 41, 59, 0.06), 0 8px 10px -6px rgba(30, 41, 59, 0.04)`.
- **Card Hover Elevation**: Hover interactions trigger a micro-lift: shifting Y-axis by `-2px`, intensifying border tone to `primary_color_hex` at 40% opacity, and deepening the slate ambient shadow.

## Shapes

The design system employs a **Soft (`1`)** shape language:
- Base elements (buttons, text inputs, chips) feature a crisp `0.25rem` (4px) corner radius.
- Structural containers and cards use `rounded-lg` (`0.5rem` / 8px).
- Modals, prominent hero showcases, and project galleries use `rounded-xl` (`0.75rem` / 12px).

This restrained corner radius avoids playful circularity and reinforces structural solidity, echoing stone, steel framing, glass curtain walls, and precise carpentry cuts.

## Components

### Buttons
- **Primary**: Solid teal fill (`#00838f`), white text (`#ffffff`), `0.25rem` radius, `0.75rem 1.5rem` padding. Hover transition shifts background to `#006978` with a subtle 2px upward translation.
- **Secondary / Slate**: Background `#1e293b`, text `#ffffff`. Used for formal contracts, specification downloads, and administrative actions.
- **Outline / Architectural**: Transparent background, `1px solid #00838f`, text `#00838f`. Hover fills with `rgba(0, 131, 143, 0.08)`.

### Cards & Project Showcases
- White surface base, `1px solid #e2e8f0` border, `0.5rem` radius, `1.5rem` internal padding.
- High-rise and commercial portfolio cards feature an integrated 16:9 photography header, accompanied by an architectural badge anchored at the top-left corner.

### Chips & Badges
- Compact `0.25rem 0.625rem` dimensions with `0.25rem` radius.
- **Service Tags** (Drywall, Commercial Framing, Caulking): Subdued teal background (`rgba(0, 131, 143, 0.1)`) with `#00838f` text.
- **Status Tags** (In Progress, Completed): Slate background (`#f1f5f9`) with `#1e293b` text.

### Inputs & Estimation Forms
- Background `#ffffff`, border `1px solid #cbd5e1`, radius `0.25rem`, padding `0.75rem 1rem`.
- Focus state applies a crisp `0 0 0 2px rgba(0, 131, 143, 0.25)` ring and switches the border to `#00838f`.
- Labels are rendered in `Inter` 13px weight 600 in `#334155`.

### Checkboxes & Radio Controls
- Base size 18px with `0.25rem` radius (checkbox) or circular ring (radio).
- Active state fills with `#00838f` and a clean white interior checkmark or dot.

### Lists & Technical Specs
- Unordered lists utilize custom square or technical glyph bullets tinted in `#00838f` rather than standard browser dots.
- Metric spec lists (e.g., Square Footage, Turnaround Time, Glazing Class) use horizontal key-value rows bordered by hairline slate dividers.