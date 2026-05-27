---
name: Lasana Cahaya Gemilang (LCG)
description: Committed color with bold expressive typography on warm paper. Contemporary design platform aesthetic. Light theme. Minimal motion. Work is hero.

colors:
  # Primary brand accent: one bold color carrying 30-60% of the surface
  brand-primary: "oklch(65% 0.22 280)"           # Vibrant blue-purple
  brand-primary-dark: "oklch(55% 0.22 280)"      # Hover/active state
  brand-primary-light: "oklch(75% 0.18 280)"     # Subtle backgrounds, borders

  # Warm paper neutrals (light theme, editorial feel)
  surface-primary: "oklch(98% 0.003 280)"        # Warm off-white, page background
  surface-secondary: "oklch(95% 0.003 280)"      # Slightly tinted surface
  surface-tertiary: "oklch(92% 0.002 280)"       # Card backgrounds

  # Text & semantic
  text-primary: "oklch(8% 0.01 280)"             # Deep charcoal, body copy
  text-secondary: "oklch(40% 0.01 280)"          # Mid-gray, supporting text
  text-tertiary: "oklch(60% 0.01 280)"           # Light gray, meta/captions
  text-inverse: "oklch(98% 0 0)"                 # For dark backgrounds

  # Semantic colors (minimal palette)
  success: "oklch(55% 0.19 150)"                 # Green-toned
  warning: "oklch(65% 0.18 65)"                  # Amber
  error: "oklch(55% 0.20 25)"                    # Red
  info: "oklch(60% 0.15 200)"                    # Blue

  # Borders & dividers
  border-primary: "oklch(85% 0.003 280)"         # Subtle hairlines
  border-secondary: "oklch(80% 0.003 280)"       # Slightly stronger

typography:
  display:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: "clamp(2rem, 5vw, 3.5rem)"
    fontWeight: 700
    lineHeight: 1.1
    letterSpacing: "-0.02em"

  headline-xl:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: "clamp(1.5rem, 3vw, 2.5rem)"
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: "-0.01em"

  headline:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: "clamp(1.25rem, 2.5vw, 1.75rem)"
    fontWeight: 600
    lineHeight: 1.3

  body:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: "1rem"
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: "0"

  body-lead:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: "1.125rem"
    fontWeight: 400
    lineHeight: 1.65

  label:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: "0.875rem"
    fontWeight: 500
    letterSpacing: "0.02em"

  caption:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: "0.75rem"
    fontWeight: 400
    lineHeight: 1.4
    letterSpacing: "0.01em"

  mono:
    fontFamily: "Monaco, Courier New, monospace"
    fontSize: "0.8125rem"
    fontWeight: 400

spacing:
  xs: "4px"
  sm: "8px"
  md: "16px"
  lg: "24px"
  xl: "32px"
  2xl: "48px"
  3xl: "64px"
  4xl: "96px"

radius:
  none: "0"
  sm: "4px"
  md: "8px"
  lg: "12px"
  xl: "16px"

components:
  button-primary:
    backgroundColor: "{colors.brand-primary}"
    textColor: "{colors.text-inverse}"
    typography: "{typography.label}"
    padding: "12px 24px"
    radius: "{radius.md}"
    fontWeight: 600

  button-primary-hover:
    backgroundColor: "{colors.brand-primary-dark}"

  button-secondary:
    backgroundColor: "transparent"
    borderColor: "{colors.brand-primary}"
    borderWidth: "1px"
    textColor: "{colors.brand-primary}"

  input-text:
    backgroundColor: "{colors.surface-secondary}"
    borderColor: "{colors.border-primary}"
    borderWidth: "1px"
    radius: "{radius.md}"
    padding: "10px 14px"

  card:
    backgroundColor: "{colors.surface-secondary}"
    borderColor: "{colors.border-primary}"
    borderWidth: "1px"
    radius: "{radius.lg}"
    padding: "24px"

  card-feature:
    backgroundColor: "{colors.surface-primary}"
    borderColor: "{colors.border-secondary}"
    borderWidth: "2px"
    radius: "{radius.xl}"
    padding: "32px"

---

# Design System: Lasana Cahaya Gemilang (LCG)

## 1. Vision: Contemporary Platform, Work-Centered

**Creative North Star: "The Craft-Forward Platform"**

LCG is a creative platform that gets out of the way. The interface is contemporary, inspired by design tools like Figma and Framer—clean, digital-native, minimal in ornament—but with **bold typographic voice** and **committed color strategy**. The aesthetic celebrates the creator's work above all; the interface is confident, expressive, and unafraid of contrast.

Light theme with warm paper tones keep the focus on creative work. A single bold brand color (blue-purple) carries 30–60% of the interface surface, making it unmissably present without overwhelming. Typography uses bold weights and varied scales to create visual hierarchy and personality. Motion is minimal—only transitions that confirm state or guide attention. The result feels like a contemporary design platform designed for creators, not a generic SaaS.

**Key Characteristics:**
- Warm paper light theme (maximum contrast for work viewing)
- Bold, expressive typography (statement scales, strong weight contrast)
- Committed color strategy: one vibrant accent carrying 30–60% of the interface
- Contemporary design-platform aesthetic (Figma-adjacent, not trendy)
- Minimal motion (transitions only, respect prefers-reduced-motion)
- Flat surfaces with subtle borders; no drop shadows except on hover/elevation

## 2. Colors: The Committed Palette

One bold brand color as the hero, with warm neutrals and semantic colors supporting it.

### Brand Primary
- **oklch(65% 0.22 280)** — Vibrant blue-purple. The one voice. CTAs, active states, navigation highlights, hero accents. Used decisively at 30–60% of the surface (committed strategy).
- **Dark variant** (oklch(55% 0.22 280)): Hover/active/pressed states. Slightly darkened for interaction feedback.
- **Light variant** (oklch(75% 0.18 280)): Subtle backgrounds, focus rings, light accents. Never as body copy.

### Warm Paper Neutrals (Light Theme)
- **Surface Primary** (oklch(98% 0.003 280)): Page background. Nearly white with imperceptible warm tint.
- **Surface Secondary** (oklch(95% 0.003 280)): Card backgrounds, input fields. Slightly tinted for separation.
- **Surface Tertiary** (oklch(92% 0.002 280)): Nested/elevated surfaces. Maximum tonal separation without color.

### Text
- **Primary** (oklch(8% 0.01 280)): Deep charcoal body copy. Readable at any size.
- **Secondary** (oklch(40% 0.01 280)): Supporting text, labels, less important information.
- **Tertiary** (oklch(60% 0.01 280)): Captions, metadata, very subtle information.
- **Inverse** (oklch(98% 0 0)): Text on dark/brand backgrounds. Pure white for maximum contrast.

### Semantic (Minimal)
- **Success** (oklch(55% 0.19 150)): Green. Confirmations, completed states.
- **Warning** (oklch(65% 0.18 65)): Amber. Cautions, in-progress, pending.
- **Error** (oklch(55% 0.20 25)): Red. Errors, destructive actions, blocking issues.
- **Info** (oklch(60% 0.15 200)): Blue. Informational messages, helpful context.

### Borders
- **Primary** (oklch(85% 0.003 280)): Hairline borders on cards, inputs, subtle dividers.
- **Secondary** (oklch(80% 0.003 280)): Slightly stronger for active elements or card outlines.

### Named Rules

**The Committed Color Rule.** Brand Primary carries 30–60% of any given screen. This commitment is the defining visual choice—it's not a secondary accent, it's the interface voice. Use it on CTAs, navigation, hero sections, data highlights, and interactive states without restraint.

**The One Palette Rule.** Only the five semantic colors exist beyond brand and neutral. No tertiary accent, no "brand secondary." If you need additional visual distinction, use typography weight or scale, not a new color.

**The Warm Paper Rule.** Always use Surface Primary (oklch(98% 0.003 280)), never pure white (#fff). The warmth creates editorial calm and makes brand color read as intentional, not slapped-on.

## 3. Typography: Bold & Expressive

**Primary Font:** Inter (with system-ui fallback)  
**Character:** Clean geometric sans-serif. Bold weights and dramatic scale contrast create personality without decoration.

### Hierarchy (Strong Contrast / Varied Scales)

- **Display** (700, clamp(2rem, 5vw, 3.5rem), line-height 1.1): Hero titles. Maximum boldness.
- **Headline XL** (700, clamp(1.5rem, 3vw, 2.5rem), line-height 1.2): Section headers.
- **Headline** (600, clamp(1.25rem, 2.5vw, 1.75rem), line-height 1.3): Subsections.
- **Body** (400, 1rem, line-height 1.6): Paragraph copy. Capped at 65–75ch for readability.
- **Body Lead** (400, 1.125rem, line-height 1.65): Lead paragraphs. Slightly larger for emphasis.
- **Label** (500, 0.875rem, letter-spacing 0.02em): CTA labels, form labels, badges.
- **Caption** (400, 0.75rem): Meta text, timestamps, supporting info.
- **Monospace** (400, 0.8125rem): Code blocks, terminal-style text, command display.

### Named Rules

**The Weight Contrast Rule.** Hierarchy is built on weight (400 vs 600 vs 700) and scale together, never weight alone. A 600-weight heading at 1.5rem reads heavier than a 700 Display at 3.5rem because scale dominates. Each step should be visually distinct.

**The 1.6 Body Rule.** Body copy always has 1.6 line-height. Not 1.5, not 1.7. This is the readability foundation for the system.

**The Fluid Headlines Rule.** All headings use `clamp()` for fluid sizing; body copy uses fixed `rem`. Fluid body text wanders off spec.

**The Expressive Scale Rule.** Use the full range: Display is *big*, Body is *normal*, Caption is *small*. No "safe middle." This creates visual personality and hierarchy.

## 4. Elevation & Shadows

Flat by default. Shadows appear only as a response to state (hover, active, lifted).

### Shadow Vocabulary
- **None (at rest)**: All surfaces are flat. No shadow on cards by default.
- **Hover lift** (0 4px 16px rgba(0,0,0,0.08)): On interactive cards and buttons when hovered.
- **Elevated surface** (0 8px 32px rgba(0,0,0,0.12)): Modals, dropdowns, popovers that float above the page.
- **Subtle focus** (0 0 0 3px oklch(65% 0.22 280 / 0.2)): Brand-tinted focus ring on keyboard-navigable elements.

### Named Rules

**The Flat-by-Default Rule.** Surfaces are flat at rest. Reach for shadows only on hover or deliberate elevation.

**The Low-Alpha Rule.** Shadows use ≤0.12 alpha. Higher alphas read dated.

## 5. Components

### Buttons
- **Primary**: Brand Primary background, white text, 600 weight, slight rounded corners (md).
- **Hover**: Slightly darker brand color (brand-primary-dark), small lift (2px).
- **Secondary**: Transparent background, brand-primary border, brand-primary text. Same hover treatment.
- **Focus**: Browser default focus ring + the hover state for keyboard navigation.

### Cards
- **Default**: Surface Secondary background, subtle border (primary), 12px radius.
- **Hover**: Slight shadow lift, no color change.
- **Feature cards**: Thicker border (2px), larger padding, rounded xl.

### Inputs / Fields
- **Text input**: Surface Secondary background, border-primary hairline, 8px radius. Focus shifts border to brand-primary with light focus ring.
- **Textarea / select**: Same styling as input.

### Navigation
- **Approach**: Top bar or side nav depending on layout.
- **Default**: text-primary links on surface-primary background.
- **Hover / Active**: Smooth transition to brand-primary color, 200ms.
- **Indicator**: Underline or background shift to mark active section. Kept minimal.

### Layout & Spacing

- **Max width**: Content at 900px, full-width sections at 100vw with internal padding.
- **Spacing scale**: 4 / 8 / 16 / 24 / 32 / 48 / 64 / 96px. Use these consistently.
- **Rhythm**: 48–96px between sections, 16–32px between components within a section.
- **Grid**: `repeat(auto-fit, minmax(250px, 1fr))` for responsive layouts. Avoid rigid breakpoints.
- **Prose**: Body copy capped at 65–75ch (`max-width: 75ch`).

## 6. Motion

Minimal. Only transitions that serve purpose.

- **State transitions** (color, opacity): 150–200ms, linear or ease-out.
- **Hover lift** (transform): 200ms, ease-out-quad.
- **Entrance animations** (if any): 300–400ms, ease-out.
- **Respect prefers-reduced-motion**: All motion collapses to instant (transition: none) when user has enabled motion preferences.

### Named Rules

**The Minimal Motion Rule.** Only three types of motion are allowed:
1. **Confirmation** (color/opacity change on interaction)
2. **Lift** (small transform on hover)
3. **Entrance** (initial page/modal load only)

No decorative animation. No bounces, no elastic easing.

**The prefers-reduced-motion Rule.** Every transition must respect the user's motion preferences. Use:
```css
@media (prefers-reduced-motion: reduce) {
  * { transition: none !important; }
}
```

## 7. Do's and Don'ts

### Do:
- **Do** use brand-primary (oklch(65% 0.22 280)) on 30–60% of any screen.
- **Do** use bold weights (600, 700) for headlines. Hierarchy through weight + scale.
- **Do** keep surfaces flat at rest. Shadows on hover/elevation only.
- **Do** use warm paper (oklch(98% 0.003 280)) as the default background.
- **Do** use fluid sizing for headlines; fixed `rem` for body copy.
- **Do** respect `prefers-reduced-motion` on every animation.
- **Do** cap body line length at 65–75ch.
- **Do** use the spacing scale (4/8/16/24/32/48/64/96px) consistently.

### Don't:
- **Don't** use pure white (#fff) or pure black (#000). Always the tinted tokens.
- **Don't** add a second accent color. One brand color is the rule.
- **Don't** use rounded rectangles with drop shadows (generic SaaS tell).
- **Don't** animate layout properties (width, height, padding). Use transform and opacity only.
- **Don't** nest cards inside cards. Flatten the hierarchy.
- **Don't** use identical card grids (same size, same layout, repeated).
- **Don't** use glassmorphism or blur effects as decoration.
- **Don't** hedge in interface copy. Be direct and confident.
- **Don't** exceed a 1.6 line-height on body copy.
- **Don't** use motion without respecting prefers-reduced-motion.
