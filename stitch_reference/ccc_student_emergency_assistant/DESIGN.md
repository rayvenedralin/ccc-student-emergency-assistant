---
name: CCC Student Emergency Assistant
colors:
  surface: '#f7f9fc'
  surface-dim: '#d8dadd'
  surface-bright: '#f7f9fc'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f7'
  surface-container: '#eceef1'
  surface-container-high: '#e6e8eb'
  surface-container-highest: '#e0e3e6'
  on-surface: '#191c1e'
  on-surface-variant: '#45464e'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f4'
  outline: '#76767f'
  outline-variant: '#c6c6cf'
  surface-tint: '#515d84'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#0c193d'
  on-primary-container: '#7782ac'
  inverse-primary: '#bac5f2'
  secondary: '#b42724'
  on-secondary: '#ffffff'
  secondary-container: '#fd5c52'
  on-secondary-container: '#600005'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#001e31'
  on-tertiary-container: '#3e8ac0'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#bac5f2'
  on-primary-fixed: '#0c193d'
  on-primary-fixed-variant: '#3a456b'
  secondary-fixed: '#ffdad6'
  secondary-fixed-dim: '#ffb4ab'
  on-secondary-fixed: '#410002'
  on-secondary-fixed-variant: '#910810'
  tertiary-fixed: '#cce5ff'
  tertiary-fixed-dim: '#91ccff'
  on-tertiary-fixed: '#001e31'
  on-tertiary-fixed-variant: '#004b72'
  background: '#f7f9fc'
  on-background: '#191c1e'
  surface-variant: '#e0e3e6'
typography:
  display-urgent:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '800'
    lineHeight: 38px
    letterSpacing: 0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 30px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: 0em
  headline-sm:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: 0em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  label-urgent:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '800'
    lineHeight: 16px
    letterSpacing: 0.06em
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  margin: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-lg: 1rem
  space-xl: 1.5rem
---

## Brand & Style

The design system establishes an authoritative, reliable, and instantaneous lifeline for higher-education campuses. Designed for students, faculty, and administrative safety personnel navigating acute, high-stress crises, the UI prioritizes clarity, non-distracting visual hierarchy, and split-second cognitive processing.

The aesthetic blends **Modern Institutional Utility** with high-contrast safety ergonomics:
- **Calm Authority & Urgency:** Deep institutional tones project stability and administrative oversight, while assertive alert colors signal life-safety operations without inducing panic.
- **Cognitive Ergonomics:** Stripped of unnecessary decorative trends, the interface delivers information in unambiguous, glanceable containers.
- **Stress-Resilient Affordances:** Immediate recognition over subtle discovery. Elements demand zero interpretation; primary danger vectors and SOS triggers use unmistakable tactile affordances.

## Colors

The palette establishes an immediate operational hierarchy anchored in emergency triage:

- **Primary Dark (`#000B30`):** Institutional navy blue used for top navigation bars, structural typography, primary non-emergency CTA controls, and deep tonal anchoring. It communicates organizational security.
- **Urgent Crimson Red (`#A61C1C`):** Reserved exclusively for life-safety triggers, the primary SOS broadcast module, active lock-down or evacuation notifications, and critical system states. It is never applied decoratively.
- **Accent Teal (`#1E73A8`):** Applied to auxiliary actions, ongoing safety status updates, non-critical contact options (e.g., campus escort requests, incident follow-ups), and focused form states.
- **Neutral Screen Background (`#F4F6F9`):** A cool, light gray canvas that prevents glare while creating sharp separation against active white containers.
- **Surface Pure White (`#FFFFFF`):** Applied across all elevated surface containers, input backgrounds, and information cards to maintain crisp content delineation.
- **Contrast & Legibility:** All text pairings against their respective backgrounds strictly satisfy WCAG 2.1 AAA contrast ratios (minimum 7:1 for body copy; 4.5:1 for bold critical callouts).

## Typography

The typography uses Inter across all levels to maintain maximum legibility, even in low-light scenarios, cracked displays, or high-stress visual impairment.

- **Urgent Callouts:** Critical emergency prompts, broadcast flags, and alert banners use `display-urgent` and `label-urgent` rendered in full uppercase with expanded tracking (`0.02em` to `0.06em`) to ensure legibility from an arm's-length distance.
- **Reading Rhythm:** Body text maintains an optimal line height ratio of 1.4 to 1.5, allowing dense procedural instructions (such as active shooter guidelines or severe weather shelter steps) to be scanned rapidly without line confusion.
- **Monospaced Data:** Incident reference codes, terminal dispatch timestamps, and geographic coordinates default to tabular numeric rendering.

## Layout & Spacing

The layout is built for mobile-first operational contexts:

- **Screen Margins:** Fixed at 16px (`1rem`) on portable handheld displays to maximize screen real estate while ensuring thumbs do not accidentally trigger edge actions.
- **Touch Target Integrity:** Every interactive module complies with an absolute minimum touch zone of 48x48px, surrounded by at least 8px (`space-sm`) of negative space to prevent mis-taps during physical movement or trembling.
- **Grid Structure:** A 4-column fluid mobile grid with 16px gutters, scaling to an 8-column layout with 24px margins on tablet devices.
- **Vertical Hierarchy:** Vertical stacked layouts prioritize high-order action sheets over deep menus. Critical actionable panels sit anchored within the thumb-accessible lower third of the mobile screen.

## Elevation & Depth

Visual hierarchy uses controlled surface separation and distinct ambient containment:

- **Ambient Shadow System:** Cards, floating trays, and actionable alerts leverage a calibrated, deep-tinted shadow: `box-shadow: 0 4px 12px rgba(0, 11, 48, 0.08)`. This anchors cards distinctly against the Light Gray canvas without creating muddy boundaries.
- **Structural Separation:** Elevation does not depend on heavy shadows alone; pure white cards feature an optional 1px subtle boundary (`rgba(0, 11, 48, 0.06)`) in flat or high-glare environments.
- **Urgent Modal Elevation:** Active emergency sheets, critical 911/SOS dispatch drawers, and broadcast push cards utilize an elevation offset of `box-shadow: 0 8px 24px rgba(0, 11, 48, 0.16)`, accompanied by a high-contrast dark scrim backdrop (`rgba(0, 11, 48, 0.60)`).

## Shapes

The design system uses a balanced geometric radius approach:

- **Containers & Cards:** Set to a strict 12px corner radius (`rounded-lg`), balancing soft handling with structured, professional clarity.
- **Interactive Controls:** Input fields, buttons, and status banners adopt 8px (`rounded-md`) to maintain clear interactive affordance distinct from large structural containers.
- **SOS Critical Button:** The primary SOS trigger is an exception: a prominent circular or large pill container designed for instant identification and rapid thumb acquisition.

## Components

### Buttons
- **Emergency SOS Button:** Circular or large-block CTA with Urgent Crimson Red (`#A61C1C`) fill, crisp white typography, minimum height of 64px, and bold uppercase text. Features prominent tactile press-and-hold interaction to eliminate accidental triggers.
- **Primary Institutional Button:** Deep Navy Blue (`#000B30`) background, 48px minimum height, 8px border radius, white bold text.
- **Secondary Action Button:** Accent Teal (`#1E73A8`) or white surface with an Accent Teal 1.5px border, designed for non-critical dispatch or status confirmations.

### Cards
- **Emergency Information Cards:** Surface Pure White (`#FFFFFF`) background, 12px border radius, 16px internal padding, styled with `0 4px 12px rgba(0, 11, 48, 0.08)`. High-urgency cards incorporate a 4px solid Crimson Red left edge indicator.
- **Status & Navigation Cards:** Surface white with teal or navy icon badges, title, body description, and a persistent chevron.

### Chips & Status Badges
- **Status Badges:** Compact 28px height, 6px border radius, uppercase bold text (`label-sm`).
- **Urgent Badge:** Red background (`#A61C1C`) with white text.
- **Active / Monitoring Badge:** Light Teal tint background (`rgba(30, 115, 168, 0.12)`) with `#1E73A8` text.

### Form Inputs & Selectors
- **Input Fields:** 48px height, Surface Pure White background, 1px solid border (`rgba(0, 11, 48, 0.16)`), 8px border radius. Focused state transitions to a 2px Accent Teal outline with zero layout shift.
- **Radio & Checkboxes:** 24x24px hit target, rendered with Deep Navy Blue active fills and high-contrast white indicators, encased within 48px minimum clickable container rows.

### Lists
- **Incident Directory & Contacts:** Clean rows separated by 1px subtle divider lines (`rgba(0, 11, 48, 0.06)`). Each item features a minimum height of 56px, high-contrast labels, and direct tap-to-call or tap-to-locate interactions.