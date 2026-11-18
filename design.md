---
name: Precision Slate & Indigo
colors:
  surface: '#faf8ff'
  surface-dim: '#d2d9f4'
  surface-bright: '#faf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3ff'
  surface-container: '#eaedff'
  surface-container-high: '#e2e7ff'
  surface-container-highest: '#dae2fd'
  on-surface: '#131b2e'
  on-surface-variant: '#464555'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#777587'
  outline-variant: '#c7c4d8'
  surface-tint: '#4d44e3'
  primary: '#3525cd'
  on-primary: '#ffffff'
  primary-container: '#4f46e5'
  on-primary-container: '#dad7ff'
  inverse-primary: '#c3c0ff'
  secondary: '#505f76'
  on-secondary: '#ffffff'
  secondary-container: '#d0e1fb'
  on-secondary-container: '#54647a'
  tertiary: '#005338'
  on-tertiary: '#ffffff'
  tertiary-container: '#006e4b'
  on-tertiary-container: '#67f4b7'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e2dfff'
  primary-fixed-dim: '#c3c0ff'
  on-primary-fixed: '#0f0069'
  on-primary-fixed-variant: '#3323cc'
  secondary-fixed: '#d3e4fe'
  secondary-fixed-dim: '#b7c8e1'
  on-secondary-fixed: '#0b1c30'
  on-secondary-fixed-variant: '#38485d'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  display:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.03em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.025em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.02em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.015em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: -0.011em
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: -0.006em
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0em
  label-md:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: -0.005em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0em
  caption:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.02em
  code:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0em
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
  margin-desktop: 2rem
  space-2xs: 0.125rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-lg: 1rem
  space-xl: 1.5rem
  space-2xl: 2rem
  space-3xl: 3rem
---

## Brand & Style

This design system establishes a high-craft, disciplined productivity environment tailored for solo creators, social media managers, and boutique agencies. Drawing direct inspiration from the refined utility of Linear and the typographic clarity of Notion, the aesthetic balances austere functionalism with subtle digital tactile warmth.

The interface prioritizes content ingestion, multi-platform publishing schedules, and metric synthesis over decorative UI chrome. Rather than overwhelming users with saturated marketing flourishes, it provides an architectural canvas where operational states—drafts, queues, approvals, and live analytics—are instantly legible.

Key design attributes:
- **Atmospheric restraint:** Generous negative space and subtle neutral shifts guide focus toward user media and copy.
- **Architectural boundaries:** Structural organization is communicated via hair-thin borders (`#E2E8F0`) and discrete elevation steps rather than dramatic dropshadows.
- **Micro-tactility:** Interactive surfaces leverage low-saturation tint shifts, crisp 1px borders, and quick spring-like micro-transitions (120ms–160ms) to feel responsive and precise.

## Colors

The palette relies on a surgical light mode built around cool slate foundations and an energetic indigo focal point. 

### Core Palette Hierarchy
- **Canvas (`#F8FAFC`):** Slate 50 acts as the global backdrop, establishing immediate distinction when higher-level white cards are placed upon it.
- **Surface (`#FFFFFF`):** Pure white is reserved strictly for interactive tiles, workspace cards, data grids, and modals to elevate them from the canvas.
- **Text & Structure:**
  - High Emphasis (`#0F172A`): Slate 900 for headlines, key figures, and high-priority labels.
  - Secondary / Muted (`#64748B`): Slate 500 for descriptions, secondary metadata, table column headers, and inactive navigation markers.
  - Hairline Borders (`#E2E8F0`): Slate 200 used universally for 1px structural framing, dividers, and card envelopes.
- **Primary Accent (`#4F46E5`):** Indigo 600 provides intentional visual anchor points for main CTAs, active timeline scrubbers, and focused inputs.
  - Subdued Indigo Tint (`#EEF2FF`): Indigo 50 is used for interactive hover layers, active sidebar items, and selected table rows.

### Semantic Status Tokens
State indicators utilize muted pastel backings alongside saturated text and border definitions to prevent visual noise across dense scheduling calendars:
- **Published / Approved:** Emerald (`#10B981`), surface fill `#ECFDF5`, border `#A7F3D0`.
- **Scheduled / Pending:** Amber (`#F59E0B`), surface fill `#FFFBEB`, border `#FDE68A`.
- **Draft / Inactive:** Slate (`#64748B`), surface fill `#F1F5F9`, border `#CBD5E1`.
- **Alert / Disconnected:** Rose (`#EF4444`), surface fill `#FEF2F2`, border `#FECACA`.

## Typography

The typographic strategy pairs **Plus Jakarta Sans** for structural display and section headings with **Inter** for data tables, editorial body text, and dense metadata.

- **Headlines (Plus Jakarta Sans):** Employs geometric clarity and tight negative tracking (`-0.02em` to `-0.03em`) to mimic the refined, contemporary feel of modern developer tools.
- **Body & Controls (Inter):** Leverages neutral grotesque proportions with optimized x-height to maximize scannability inside high-density multi-account streams, asset managers, and comment threads.
- **Captions & Metadata:** Rendered in `label-sm` or `caption` with medium font weights (`500`) to guarantee contrast against `#64748B` even at reduced dimensions.

## Layout & Spacing

This design system uses an 8-point base rhythm, supplemented by a 4-point micro-scale for compact interface widgets (e.g., tags, button paddings, inline metric badges).

### Grid & Viewport Adaptability
- **Desktop (>= 1280px):** Employs a collapsible 240px utility sidebar with an adaptive fluid multi-column work area. Data tables and calendar boards maintain a strict 24px outer margin (`margin-desktop`) and 24px gutters (`gutter-desktop`).
- **Tablet (768px – 1279px):** Collapses navigational sidebars into an icon rail (64px) or slide-over drawer. Gutters scale down to 16px (`gutter`).
- **Mobile (< 768px):** Single-column stack with persistent 16px edge padding (`margin`). Multi-channel composer docks become full-screen modal overlays to preserve keyboard and view real estate.

Horizontal rhythm inside cards relies on strict internal padding: standard density cards use `space-xl` (24px), while compact analytical and calendar tiles drop to `space-lg` (16px).

## Elevation & Depth

Visual hierarchy is maintained primarily through **tonal separation** and **1px low-contrast borders**, bypassing heavy or fuzzy shadows to keep the workspace tactile and sharp.

### Elevation Levels
1. **Level 0 (Base Canvas):** Background rendered in `#F8FAFC`. Zero elevation, non-bordered.
2. **Level 1 (Card & Workspace Panels):** Surface `#FFFFFF` enclosed with a crisp border: `1px solid #E2E8F0`. Shadow is strictly ambient and nearly imperceptible: `0 1px 2px 0 rgba(15, 23, 42, 0.04)`.
3. **Level 2 (Hover States & Active Cards):** Border shifts slightly to `#CBD5E1` with an elevated micro-shadow: `0 4px 6px -1px rgba(15, 23, 42, 0.05), 0 2px 4px -2px rgba(15, 23, 42, 0.05)`.
4. **Level 3 (Popovers, Dropdowns, Date Pickers):** Background `#FFFFFF` framed in `1px solid #E2E8F0` with floating depth: `0 10px 15px -3px rgba(15, 23, 42, 0.08), 0 4px 6px -4px rgba(15, 23, 42, 0.04)`.
5. **Level 4 (Modals & Command Palettes):** Framed in `1px solid #E2E8F0` over a muted backdrop overlay (`#0F172A` at 30% opacity with a `backdrop-blur(2px)` effect). Shadow: `0 20px 25px -5px rgba(15, 23, 42, 0.1), 0 8px 10px -6px rgba(15, 23, 42, 0.04)`.

## Shapes

The geometric architecture is defined by disciplined, purposeful curvature that balances sharp utility with modern software warmth. 

- **Primary Cards & Modals (`rounded-lg` / 12px):** Applied to major surface containers, content scheduling columns, asset preview blocks, and floating sheets.
- **Controls & Interactive Elements (`rounded` / 8px):** Standardized across buttons, text fields, search bars, selects, and dropdown menus to deliver a unified tactile baseline.
- **Micro Tags & Badges (4px to 6px):** Sub-elements such as platform icons, status pills, and keyboard shortcut markers (`Kbd`) scale down their curvature to prevent visual ballooning.
- **Avatars & Platform Badges (`rounded-full`):** Retained exclusively for user profile imagery and social network icons (X, Instagram, LinkedIn, YouTube) to establish clear biological and brand differentiation from interface cards.

## Components

### Buttons
- **Primary:** Background `#4F46E5`, text `#FFFFFF`, border `1px solid transparent`, radius `8px`. Hover: `#4338CA`. Active: `#3730A3`. Focus-visible: outline `2px solid #4F46E5`, outline-offset `2px`.
- **Secondary / Subtle:** Background `#FFFFFF`, text `#0F172A`, border `1px solid #E2E8F0`, radius `8px`. Hover: background `#F8FAFC`, border `#CBD5E1`.
- **Ghost:** Background `transparent`, text `#64748B`, radius `8px`. Hover: background `#EEF2FF`, text `#4F46E5`.
- **Destructive:** Background `#FFFFFF`, text `#EF4444`, border `1px solid #FECACA`. Hover: background `#FEF2F2`.

### Chips & Semantic Status Badges
- Displayed with height `24px`, padding `0 8px`, border-radius `6px`, typography `label-sm` (font-size `12px`, weight `500`).
- **Published:** Text `#065F46`, background `#ECFDF5`, border `1px solid #A7F3D0`. Includes a `6px` circular pulse dot in `#10B981`.
- **Pending / In Queue:** Text `#92400E`, background `#FFFBEB`, border `1px solid #FDE68A`.
- **Draft:** Text `#475569`, background `#F1F5F9`, border `1px solid #CBD5E1`.
- **Error / Attention:** Text `#991B1B`, background `#FEF2F2`, border `1px solid #FECACA`.

### Form Inputs & Selects
- Height `36px`, horizontal padding `12px`, border `1px solid #E2E8F0`, border-radius `8px`, background `#FFFFFF`, text `body-md` (`#0F172A`).
- **Placeholder:** Text `#94A3B8`.
- **Focus:** Border color `#4F46E5`, ring `1px solid #4F46E5`, box-shadow `0 0 0 3px rgba(79, 70, 229, 0.12)`.
- **Error:** Border color `#EF4444`, box-shadow `0 0 0 3px rgba(239, 68, 68, 0.1)`.

### Cards & Calendar Schedule Blocks
- **Standard Card:** Background `#FFFFFF`, border `1px solid #E2E8F0`, border-radius `12px`, padding `16px` or `24px`.
- **Interactive Post Cell (Kanban/Calendar):** Background `#FFFFFF`, border `1px solid #E2E8F0`, border-radius `8px`, padding `12px`. Hover: transforms with `translateY(-1px)`, border `#CBD5E1`, and Level 2 elevation shadow.

### Checkboxes & Radios
- Size `16px x 16px`, border `1px solid #CBD5E1`, border-radius `4px` (checkbox) or `full` (radio).
- **Checked State:** Background `#4F46E5`, border-color `#4F46E5`, icon fill `#FFFFFF`. Transition `120ms ease-in-out`.

### Command Palette & Quick Composer (Linear-Style Pattern)
- Centered modal container (`640px` wide), background `#FFFFFF`, border `1px solid #E2E8F0`, radius `12px`, shadow Level 4.
- Embedded input: zero border, font size `16px`, text `#0F172A`, bottom divider `1px solid #F1F5F9`.
- Item row height `40px`, radius `6px`, margin `0 8px`, hover fill `#EEF2FF`, active text `#4F46E5`.