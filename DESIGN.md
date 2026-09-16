---
name: Campus Foodtech & Quick-Bite Modern UI
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
  on-surface-variant: '#e0c0b1'
  inverse-surface: '#dae2fd'
  inverse-on-surface: '#283044'
  outline: '#a78b7d'
  outline-variant: '#584237'
  surface-tint: '#ffb690'
  primary: '#ffb690'
  on-primary: '#552100'
  primary-container: '#f97316'
  on-primary-container: '#582200'
  inverse-primary: '#9d4300'
  secondary: '#4edea3'
  on-secondary: '#003824'
  secondary-container: '#00a572'
  on-secondary-container: '#00311f'
  tertiary: '#ffb783'
  on-tertiary: '#4f2500'
  tertiary-container: '#e5812c'
  on-tertiary-container: '#522700'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdbca'
  primary-fixed-dim: '#ffb690'
  on-primary-fixed: '#341100'
  on-primary-fixed-variant: '#783200'
  secondary-fixed: '#6ffbbe'
  secondary-fixed-dim: '#4edea3'
  on-secondary-fixed: '#002113'
  on-secondary-fixed-variant: '#005236'
  tertiary-fixed: '#ffdcc5'
  tertiary-fixed-dim: '#ffb783'
  on-tertiary-fixed: '#301400'
  on-tertiary-fixed-variant: '#713700'
  background: '#0b1326'
  on-background: '#dae2fd'
  surface-variant: '#2d3449'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 48px
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 30px
    fontWeight: '800'
    lineHeight: 38px
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '700'
    lineHeight: 30px
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '600'
    lineHeight: 20px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 18px
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-desktop: 1.5rem
  margin: 1rem
  margin-tablet: 2rem
  margin-desktop: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

The design system embodies a modern, high-velocity campus dining experience that merges the sleek precision of contemporary consumer fintech with the tactile warmth of artisanal cafe ordering. Engineered specifically for university students, faculty, and busy campus visitors, the interface communicates immediacy, freshness, and frictionless checkout during peak campus breaks.

The design movement synthesizes **Modern High-Contrast Dark-Mode Architecture** with **Tactile Surface Glassmorphism**:
- Deep navy and slate abyssal canvases evoke high-end mobile apps.
- Pristine, elevated card surfaces provide maximum legibility for food photography and order tracking.
- Radiant amber, citrus zest accents, and vivid emerald botanicals inject energy, speed, and unmistakable dietary clarity (such as pure veg vs non-veg indicators).
- Fine specular micro-borders, luminous glow badges, and smooth container radiuses create an elevated physical product aesthetic tailored for rapid thumb-driven touchscreens and dynamic kiosk displays.

## Colors

The palette leverages a deep midnight infrastructure juxtaposed against radiant culinary accents and crisp, functional status indicators.

### Primary Accents & Energy
- **Primary Flame Amber (`#F97316`)**: The lead action tone for primary CTA buttons, dynamic timers, and active cart badges.
- **Secondary Citrus Tint (`#FB923C`)**: Reserved for micro-highlights, hover illumination, active category chips, and glowing aura rings around pending orders.

### Culinary & Dietary Semantics
- **Emerald Garden (`#10B981`)**: The campus vegetarian indicator, organic item badge, successful order confirmation, and balance recharges.
- **Ruby Crimson (`#EF4444`)**: Campus non-veg badge, critical order alerts, sold-out notices, and cancellation states.
- **Dairy & Caffeine Gold (`#EAB308`)**: Express breakfast flags, pickup slot notifications, and loyalty coffee points.

### Backgrounds & Surfaces
- **Canvas Void (`#090D16`)**: Root background for immersive, battery-efficient dark presentation.
- **Slate Bedrock (`#0F172A`)**: Secondary canvas base for navigation bars, sub-headers, and drawer modals.
- **Card Surface Slate (`#1E293B`)**: Layered container level providing deep visual separation.
- **Crisp Surface Bright (`#FFFFFF`)**: High-contrast, card popouts for active menus, receipt summaries, and kiosk interaction zones.
- **Border Stroke (`rgba(255, 255, 255, 0.08)`)**: Subtle specular glass hairline rim defining card boundaries.

## Typography

The typographical pairing sets a bold, contemporary cadence using **Plus Jakarta Sans** for expressiveness and punchy product titles, balanced by the utilitarian clarity of **Inter** for descriptions, nutritional specs, item modifications, and price tables.

- **Display & Headlines**: Rendered in Plus Jakarta Sans with tighter tracking (`-0.02em`) and heavier weights (`700` and `800`) to anchor scanning eyes across crowded menus during rushed campus intervals.
- **Body & Nutritional Copy**: Driven by Inter with neutral kerning and generous line spacing to ensure legibility on glare-heavy campus screens or outdoor cafe seating.
- **Labels, Badges, & Timers**: Set in Plus Jakarta Sans (`600` or `700`) with uppercase transformations on small badges (`label-sm`), ensuring immediate recognition of order queue numbers, countdown timers, and dietary classifications.

## Layout & Spacing

The layout is built upon an 8-point base spacing rhythm within a responsive grid framework calibrated for handheld mobile ordering, counter tablets, and wide-format self-checkout kiosks.

- **Mobile (<640px)**: 4-column fluid layout with `1rem` outer margins and `1rem` gutters. Menu categories scroll horizontally along a sticky sub-header; ordering cards stack into single full-width items with thumb-friendly height minimums (64px).
- **Tablet (640px–1024px)**: 8-column layout with `2rem` outer margins. Menu cards form a 2-column or 3-column asymmetric layout with a persistent, collapsible bottom sheet for the quick tray and live pickup slot.
- **Desktop & Kiosk (>1024px)**: 12-column layout with `3rem` margins and `1.5rem` gutters. Employs a dual-pane architecture: a fluid 8-column browsing grid for menu customization alongside a fixed 4-column live order ledger and split-payment panel.

## Elevation & Depth

Visual hierarchy uses layered dark surfaces accented with luminescent glows, glass micro-borders, and crisp focal popouts:

1. **Level 0 (Canvas Void)**: `#090D16`, deep matte backdrop. No elevation or drop shadows.
2. **Level 1 (Card & Category Tiers)**: `#1E293B` or frosted translucent slate (`rgba(30, 41, 59, 0.75)` with `backdrop-filter: blur(16px)`). Bound by a 1px border of `rgba(255, 255, 255, 0.08)`. Casts a subtle ambient drop shadow: `0 4px 20px -2px rgba(0, 0, 0, 0.5)`.
3. **Level 2 (Popout Focus Surfaces & High-Contrast Cards)**: Crisp white surfaces (`#FFFFFF`) used for active cart drawers, printable token receipts, and featured chef specials. Casts a weighted contrast shadow: `0 12px 32px -4px rgba(0, 0, 0, 0.45)`.
4. **Level 3 (Floating Actions & Modals)**: Glass sheets (`rgba(15, 23, 42, 0.92)`) bounded by `rgba(249, 115, 22, 0.25)` specular lighting. Augmented with colored ambient auras:
   - Primary action glow: `0 8px 24px -2px rgba(249, 115, 22, 0.35)`
   - Green pickup/success glow: `0 8px 24px -2px rgba(16, 185, 129, 0.3)`

## Shapes

The geometric framework favors generous, organic curves that feel approachable, ergonomic, and contemporary:

- **Core Containers & Food Cards**: Use `rounded-2xl` (1rem to 1.25rem) to soften dish presentation imagery and give kiosk touch targets a tactile, pebble-like quality.
- **Action Buttons & Inputs**: Standardized on `rounded-xl` (0.75rem to 1rem) for balanced thumb ergonomics.
- **Pills & Status Badges**: Fully rounded (`9999px`) for dietary labels (Veg, Non-Veg, Halal, Gluten-Free), prep timers, and incremental quantity counters.
- **Modal Drawers**: Top corners curved with dramatic 1.75rem smoothing to mimic modern native OS bottom-sheet cards.

## Components

### Buttons
- **Primary (Order/Checkout)**: Solid vibrant amber (`#F97316`) background with pure white text (`#FFFFFF`), `font-weight: 700`, `rounded-xl`, padded `0.875rem 1.5rem`. Paired with a warm atmospheric glow `rgba(249, 115, 22, 0.35)` on hover and active states.
- **Secondary (Customization/Add-on)**: Translucent slate background (`rgba(255, 255, 255, 0.06)`), frosted border `rgba(255, 255, 255, 0.12)`, text `#FFFFFF`. Turns `#F97316` on active selection.
- **Ghost/Destructive**: Clean transparent background with subtle text hover transitions to Ruby Crimson (`#EF4444`).

### Chips & Dietary Filters
- Segmented pills (`rounded-full`) with `1px` subtle outline.
- **Vegetarian**: Emerald border (`rgba(16, 185, 129, 0.3)`), faint background tint (`rgba(16, 185, 129, 0.12)`), sharp emerald text (`#10B981`) paired with the standard green square-and-circle icon.
- **Non-Vegetarian**: Crimson border and fill tint (`rgba(239, 68, 68, 0.12)`) with a crisp brown/red indicator.
- **Category Filter Chips**: Floating pill tabs in dark slate, converting to glowing orange fill with bold contrast typography when selected.

### Menu & Item Cards
- Styled with dual-mode versatility: dark slate surfaces (`#1E293B`) for everyday catalogue discovery, and optional crisp white (`#FFFFFF`) card faces for highlighted lunch bundles and featured chef promos.
- Edge boundary defined by subtle glassmorphism borders (`1px solid rgba(255, 255, 255, 0.08)`).
- Images occupy full bleed with a soft dark vignette on the bottom edge to host pricing and badge tags directly over the photography.

### Quantity Stepper & Add-to-Cart
- Pill-shaped capsule button (`rounded-full`) featuring a minus, numeric counter, and plus sign.
- In zero-state: Shows an outline pill "+ ADD". Upon tapping, expands smoothly into a solid slate/orange stepper with spring animation.

### Live Order Status Tracker (Campus Dine-in & Express Pickup)
- Floating dynamic card utilizing deep glass backdrop with an emerald pulsing halo.
- Progress bar composed of segmented glowing stadium steps: *Received* → *In Kitchen* → *Ready at Counter #3*.
- Prominent 3-digit order token displayed in monospaced, heavy Plus Jakarta Sans numerals for fast counter verification.

### Inputs & Search
- Integrated campus search fields featuring a slate fill (`#0F172A`), `1px` boundary stroke (`rgba(255, 255, 255, 0.1)`), and dynamic focus ring glowing with primary amber (`#F97316`).
- Quick-filter tags embedded directly in the search bar (e.g., "Under 10 mins", "Beverages", "Combos").