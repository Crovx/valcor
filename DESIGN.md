---
name: Valcor Studio
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
  on-surface-variant: '#424654'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#737785'
  outline-variant: '#c3c6d6'
  surface-tint: '#0056d2'
  primary: '#0040a1'
  on-primary: '#ffffff'
  primary-container: '#0056d2'
  on-primary-container: '#ccd8ff'
  inverse-primary: '#b2c5ff'
  secondary: '#565e74'
  on-secondary: '#ffffff'
  secondary-container: '#dae2fd'
  on-secondary-container: '#5c647a'
  tertiary: '#004395'
  on-tertiary: '#ffffff'
  tertiary-container: '#005ac2'
  on-tertiary-container: '#c9d8ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2ff'
  primary-fixed-dim: '#b2c5ff'
  on-primary-fixed: '#001847'
  on-primary-fixed-variant: '#0040a1'
  secondary-fixed: '#dae2fd'
  secondary-fixed-dim: '#bec6e0'
  on-secondary-fixed: '#131b2e'
  on-secondary-fixed-variant: '#3f465c'
  tertiary-fixed: '#d8e2ff'
  tertiary-fixed-dim: '#adc6ff'
  on-tertiary-fixed: '#001a42'
  on-tertiary-fixed-variant: '#004395'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.1em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 32px
  section-padding-desktop: 120px
  section-padding-mobile: 64px
---

## Brand & Style
The design system for Valcor Studio is built on the principles of **Precision Minimalism**. It is designed to evoke a sense of authoritative growth and high-end craftsmanship. The UI focuses on clarity, allowing the agency's portfolio and results-oriented data to take center stage.

The aesthetic blends **Modern Corporate** reliability with **Premium Minimalism**. Every element is placed with intentionality, utilizing generous whitespace to communicate confidence and "breathing room." The visual language is sharp and professional, avoiding decorative clutter in favor of functional elegance and smooth, purposeful transitions.

## Colors
The palette is rooted in a deep, professional "Valcor Blue" that symbolizes stability and growth. 

- **Primary Blue (#0056D2):** Used for key actions, the monogram, and highlighting growth metrics.
- **Deep Navy (#0F172A):** Utilized for high-contrast sections, footers, and primary headings to provide a sophisticated, grounded feel.
- **Surface Colors:** The default state is a crisp White (#FFFFFF) with subtle off-white (#F8FAFC) used to differentiate background sections.
- **Accents & States:** A lighter Tertiary Blue is used for hover states and secondary emphasis, while a range of Slate Grays handles borders and supporting body copy.

## Typography
This design system uses **Inter** exclusively to maintain a systematic, utilitarian, yet highly polished appearance. 

The hierarchy relies on significant scale contrasts and tracking adjustments. **Display** and **Headline** roles should use negative letter spacing to feel tight and authoritative. **Label-caps** are used for overlines (e.g., "OUR SERVICES") and should feature generous tracking (10%) to enhance the premium, editorial feel. Body copy is optimized for readability with a comfortable 1.6x line height.

## Layout & Spacing
The layout follows a **Fixed-Fluid Hybrid Grid**. Content is housed within a 1280px central container for desktop viewing, ensuring optimal line lengths for readability.

- **Rhythm:** An 8px base unit governs all spatial relationships.
- **Grid:** A 12-column grid is used for desktop, 6-column for tablet, and 2-column for mobile.
- **Whitespace:** We embrace "Luxury Gap" spacing. Major sections should be separated by at least 120px on desktop to emphasize the minimalist, high-end nature of the brand. Vertical spacing between components should be generous, typically using 48px or 64px increments.

## Elevation & Depth
Depth is conveyed through **Subtle Ambient Shadows** and **Tonal Layering**. 

1.  **Level 0 (Flat):** Default background surfaces.
2.  **Level 1 (Soft):** For cards and interactive containers. Use a very diffused shadow: `0px 4px 20px rgba(0, 0, 0, 0.05)`.
3.  **Level 2 (Hover):** Upon interaction, elements lift slightly with a more pronounced but still soft shadow: `0px 12px 30px rgba(0, 86, 210, 0.1)`.

Avoid heavy gradients or stark borders. Use 1px borders in a soft Slate-200 (#E2E8F0) for structural definition on light backgrounds.

## Shapes
The shape language is **Refined and Modern**. 

A standard corner radius of 8px (0.5rem) is applied to buttons, input fields, and small cards. For larger containers or featured imagery, use 16px (1rem) to soften the professional edges and make the interface feel more approachable. Buttons should never be fully pill-shaped; they remain "Soft-Rectangular" to maintain the corporate, structured aesthetic.

## Components

- **Buttons:** Primary buttons use the Valcor Blue background with white text. Hover states should involve a subtle shift to the Tertiary Blue and a slight upward translate (2px). Secondary buttons use a 1px border with primary text.
- **Inputs:** Fields use a 1px Slate-200 border. On focus, the border transitions to Valcor Blue with a 2px soft outer glow (ring).
- **Cards:** White backgrounds with Level 1 shadows. Content inside cards should have at least 32px of internal padding.
- **Lists:** Use custom icons for bullet points, specifically a stylized "upward arrow" glyph derived from the logo monogram to reinforce the growth narrative.
- **Chips/Tags:** Small, 4px rounded containers with a light blue tinted background (#EFF6FF) and Primary Blue text for categorization.
- **Interactive States:** All transitions (hover, focus, active) must use a 300ms "ease-out" curve to ensure the "smoothness" requested in the brand style.