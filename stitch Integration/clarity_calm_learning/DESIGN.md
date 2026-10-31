---
name: Clarity & Calm Learning
colors:
  surface: '#f8f9ff'
  surface-dim: '#ccdbf4'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e6eeff'
  surface-container-high: '#dde9ff'
  surface-container-highest: '#d5e3fd'
  on-surface: '#0d1c2f'
  on-surface-variant: '#3e4947'
  inverse-surface: '#233144'
  inverse-on-surface: '#ebf1ff'
  outline: '#6e7977'
  outline-variant: '#bdc9c6'
  surface-tint: '#006a63'
  primary: '#005c55'
  on-primary: '#ffffff'
  primary-container: '#0f766e'
  on-primary-container: '#a3faef'
  inverse-primary: '#80d5cb'
  secondary: '#006b5f'
  on-secondary: '#ffffff'
  secondary-container: '#6df5e1'
  on-secondary-container: '#006f64'
  tertiary: '#475452'
  on-tertiary: '#ffffff'
  tertiary-container: '#5f6c6a'
  on-tertiary-container: '#dfedea'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#9cf2e8'
  primary-fixed-dim: '#80d5cb'
  on-primary-fixed: '#00201d'
  on-primary-fixed-variant: '#00504a'
  secondary-fixed: '#71f8e4'
  secondary-fixed-dim: '#4fdbc8'
  on-secondary-fixed: '#00201c'
  on-secondary-fixed-variant: '#005048'
  tertiary-fixed: '#d7e5e2'
  tertiary-fixed-dim: '#bcc9c7'
  on-tertiary-fixed: '#121e1c'
  on-tertiary-fixed-variant: '#3d4947'
  background: '#f8f9ff'
  on-background: '#0d1c2f'
  surface-variant: '#d5e3fd'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 38px
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
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
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
  gutter-sm: 0.75rem
  margin: 1.25rem
  margin-lg: 1.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.25rem
  space-xl: 1.75rem
  space-2xl: 2.5rem
---

## Brand & Style

This design system is tailored for an educational learning environment that reduces cognitive fatigue and encourages sustained focus. It pairs the natural composure of deep sea teal with the soft, inviting radiance of warm, slate-tinted whites.

The aesthetic philosophy centers on **Refined Soft-Tactile Minimalism**:
- **Clarity over Clutter:** Every surface prioritizes legibility, spacious touch targets, and visual comfort.
- **Atmospheric Depth:** Gentle gradient washes and tinted surfaces evoke breathing room rather than rigid device constraints.
- **Friendly Authority:** Rounded corner radiuses, soft pill accents, and balanced micro-interactions welcome the student without patronizing them.
- **Target Audience:** Self-directed learners, secondary and higher-ed students, and lifelong knowledge seekers who benefit from calm, distraction-free study sessions.

## Colors

The palette establishes an ambient, low-strain canvas accented by deliberate, jewel-toned teal hierarchy markers.

### Palette Implementation
- **Primary Teal (`#0F766E`):** Serves as the bedrock for active navigation, key action triggers, authoritative headline emphasis, and high-emphasis states.
- **Accent Teal (`#14B8A6`):** Highlights progress indicators, achievements, live state badges, and dynamic focus glows.
- **Soft Teal Surface (`#E6F4F1`):** Grounds secondary containers, completed module items, and callout banners with gentle chromatic warmth.
- **Light Teal Border (`#C7E7E1`):** Provides delicate perimeter boundaries without harsh contrast.
- **Backgrounds:** Canvas utilizes `#F8FAFC`, backed by subtle atmospheric radial or linear top-to-bottom gradients transitioning from `rgba(20, 184, 166, 0.06)` down to `#F8FAFC`.
- **Surfaces:** Pure White (`#FFFFFF`) holds primary card contents, quizzes, input panels, and modals.
- **Typography Colors:** Primary Text is anchored to `#334155` for high-readability without harsh black contrast; Secondary Text resides at `#64748B` for metadata, timestamps, and subtitles.
- **Functional Semantics:** Success is calibrated to Forest Green (`#15803D`) and Warning/Attention to Amber Gold (`#D97706`).

## Typography

Typography is powered entirely by **Plus Jakarta Sans**, utilizing its geometric clarity, tall x-height, and contemporary humanist curves to maintain readability across complex educational contexts like flashcards, code snippets, and long-form prose.

### Usage Hierarchy
- **Display & Large Headlines (`display-lg`, `headline-lg`):** Reserved for course landing headers, milestone completion screens, and module overviews.
- **Section Headers (`headline-md`, `headline-sm`):** Anchor card collections, lesson units, and test question titles.
- **Body (`body-lg`, `body-md`, `body-sm`):** Set at comfortable line-heights (1.5–1.55) to optimize visual parsing during sustained reading.
- **Labels & Microcopy (`label-lg`, `label-md`, `label-sm`):** Slightly elevated font weights (`600`) with subtle letter-spacing for tags, progress counts, navigation pills, and interactive buttons.

## Layout & Spacing

The layout model emphasizes single-column clarity optimized for hand-held mobile devices, scaling into centered ergonomic sheets on tablets.

### Layout Mechanics
- **Canvas Margins:** Mobile screens apply a consistent `1.25rem` (20px) outer canvas margin. Expanded tablet screens adapt to `1.5rem` (24px) with fixed-width content containers capped at 680px for focused learning flows.
- **Grid & Gutters:** A 4-column fluid mobile grid utilizes `1rem` (16px) gutters between horizontal modules, cards, or metric pairs.
- **Vertical Rhythm:**
  - Content sections within a unit flow with `space-xl` (28px) separations.
  - Sibling items inside an exercise list stack with `space-md` (16px) gaps.
  - Micro-pairings (icon + label, question index + tag) employ `space-xs` (4px) or `space-sm` (8px).

## Elevation & Depth

This design system avoids dark or sharp drop shadows, opting instead for **soft atmospheric ambient shadows** and **tinted boundary rings**.

### Depth Layers
- **Base Level (Canvas):** `#F8FAFC` rendered with a gentle top-down radial gradient (`rgba(20, 184, 166, 0.05)` at `0%` fading into pure `#F8FAFC` at `280px`).
- **Surface Level 1 (Resting Cards & Modules):** Pure White `#FFFFFF` with a subtle composite shadow:
  - `0 1px 3px rgba(15, 118, 110, 0.04), 0 8px 24px -4px rgba(51, 65, 85, 0.06)`
  - Outlined by a soft border: `1px solid #C7E7E1` or `1px solid rgba(199, 231, 225, 0.6)`.
- **Surface Level 2 (Floating Sheets, Bottom Trays & Modals):**
  - Raised white surface with `0 12px 32px -6px rgba(15, 118, 110, 0.12), 0 4px 12px rgba(51, 65, 85, 0.04)`.
  - Border: `1px solid #C7E7E1`.
- **Interactive Depressed State:** Interactive cards subtly compress elevation on tap to `0 1px 2px rgba(15, 118, 110, 0.08)` to deliver tactile confirmation.

## Shapes

The geometric identity balances student-accessible softness with clean structural utility:
- **Cards & Primary Modules:** Standardized to a generous `18px` (falling directly in the 16–20px user threshold) to produce smooth visual framing.
- **Buttons & Input Controls:** Shaped at `12px` to `14px` border radius, echoing the card corners without morphing into full bubbles.
- **Status Tags, Category Chips, and Progress Pills:** Styled using complete pill forms (`9999px`) to immediately distinguish informational metadata from actionable cards.
- **Selection Highlights & Mini Badges:** Micro elements use `8px` corner radius.

## Components

### Buttons
- **Primary Action:** Solid background `#0F766E` with text `#FFFFFF` in `label-lg`. Subtly elevated with an inner glow or subtle `0 4px 12px rgba(15, 118, 110, 0.25)`. Corner radius `14px`, height `48px` or `52px` for comfortable thumb tap targets.
- **Secondary / Ghost:** Soft teal fill `#E6F4F1`, text color `#0F766E`, border `1px solid #C7E7E1`. Hover/Pressed state transitions to `#C7E7E1`.
- **Accent Action:** Subtle gradient from `#0F766E` to `#14B8A6` applied to key gamified buttons (e.g., "Start Quiz", "Claim Milestone").

### Cards & Lesson Tiles
- Built with a `#FFFFFF` surface, corner radius `18px`, and border `1px solid #C7E7E1`.
- Interior padding set to `space-lg` (20px).
- Incorporates a Soft Teal `#E6F4F1` decorative accent header or icon well to visually identify subject tracks.

### Chips & Filter Pills
- Fully rounded pills (`rounded-full`, 9999px).
- Unselected: Surface `#FFFFFF`, border `1px solid #C7E7E1`, text `#64748B`.
- Selected: Surface `#E6F4F1`, border `1.5px solid #14B8A6`, text `#0F766E`, font weight `600`.

### Form Fields & Inputs
- Height `48px`, `#FFFFFF` surface, border `1.5px solid #C7E7E1`, radius `12px`.
- Text `#334155` with placeholder `#94A3B8`.
- Focus State: Border transitions to `#14B8A6` accompanied by a soft teal focus shadow ring `0 0 0 3px rgba(20, 184, 166, 0.2)`.

### Selection Controls (Radio & Checkbox)
- Radio: Circular with border `2px solid #C7E7E1`. Active state displays solid `#0F766E` with an inner white core.
- Checkbox: `6px` rounded corners. Checked state fills with `#0F766E` featuring a crisp white check glyph.

### Learning-Specific Components
- **Progress Trackers:** Track base in `#E6F4F1` (height 8px, rounded 9999px) with active bar rendered in `#14B8A6` or a two-tone teal gradient (`#0F766E` to `#14B8A6`).
- **Streak & Stat Badges:** Compact badge with Soft Teal `#E6F4F1` background, warning gold accent `#D97706` for streaks, and deep teal `#0F766E` numerical data.
- **Flashcard Surfaces:** Reversible cards featuring `20px` radius, subtle teal-tinted atmospheric box shadows, and generous centered typography.