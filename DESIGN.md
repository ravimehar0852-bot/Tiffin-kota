---
name: TiffinKota Design System
colors:
  surface: '#fbf9f9'
  surface-dim: '#dbdad9'
  surface-bright: '#fbf9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f3'
  surface-container: '#efeded'
  surface-container-high: '#e9e8e7'
  surface-container-highest: '#e3e2e2'
  on-surface: '#1b1c1c'
  on-surface-variant: '#584235'
  inverse-surface: '#303031'
  inverse-on-surface: '#f2f0f0'
  outline: '#8c7263'
  outline-variant: '#e0c0af'
  surface-tint: '#994700'
  primary: '#994700'
  on-primary: '#ffffff'
  primary-container: '#ff7a00'
  on-primary-container: '#5c2800'
  inverse-primary: '#ffb68b'
  secondary: '#615e57'
  on-secondary: '#ffffff'
  secondary-container: '#e7e2d9'
  on-secondary-container: '#67645d'
  tertiary: '#5f5e5e'
  on-tertiary: '#ffffff'
  tertiary-container: '#a2a0a0'
  on-tertiary-container: '#373737'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbc8'
  primary-fixed-dim: '#ffb68b'
  on-primary-fixed: '#321200'
  on-primary-fixed-variant: '#753400'
  secondary-fixed: '#e7e2d9'
  secondary-fixed-dim: '#cbc6bd'
  on-secondary-fixed: '#1d1b16'
  on-secondary-fixed-variant: '#494640'
  tertiary-fixed: '#e5e2e1'
  tertiary-fixed-dim: '#c8c6c5'
  on-tertiary-fixed: '#1c1b1b'
  on-tertiary-fixed-variant: '#474746'
  background: '#fbf9f9'
  on-background: '#1b1c1c'
  surface-variant: '#e3e2e2'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  title-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-margin: 24px
  gutter: 16px
  stack-sm: 4px
  stack-md: 12px
  stack-lg: 24px
  section-gap: 48px
---

## Brand & Style
The design system for TiffinKota is built on a "Premium-Bistro" aesthetic—combining the efficiency of a modern tech startup with the warmth of a high-end culinary experience. The brand personality is professional, appetizing, and trustworthy.

The visual style utilizes a **Modern-Tactile** approach. It leans heavily into high-quality whitespace and elegant card structures to suggest cleanliness and care in food handling. We incorporate subtle **Glassmorphism** for navigational overlays and floating headers to maintain a sense of depth and context without cluttering the user's field of view. The goal is to evoke a "concierge" feeling rather than a "utility" feeling, making the act of ordering food feel like a curated event.

## Colors
This design system employs a warm, appetizing palette designed to stimulate appetite while maintaining high legibility.

- **Primary Orange (#FF7A00):** Used for primary actions, price points, and status indicators. It represents heat, energy, and freshness.
- **Warm Cream (#FFF9F0):** The primary canvas color. It is softer on the eyes than pure white and provides a "paper menu" feel that enhances the premium narrative.
- **Deep Black (#1A1A1A):** Reserved for primary headings and body text to ensure maximum contrast and a grounded, professional tone.
- **Surface White (#FFFFFF):** Used exclusively for elevated cards and modals to make them pop against the cream background.

## Typography
We use **Inter** across all levels to maintain a clean, systematic, and modern appearance. The typographic hierarchy relies on significant weight shifts (Bold for headers vs. Regular for descriptions) to guide the user through complex menus.

- **Headlines:** Use tight letter spacing and heavy weights to create a sense of authority.
- **Body:** Standardized at 16px for optimal readability on mobile devices.
- **Labels:** Small caps are used for category tags (e.g., "VEGAN", "SPICY") to provide clear metadata without distracting from the dish names.

## Layout & Spacing
This design system uses a **Fluid Grid** approach for mobile and a **Fixed Max-Width (1280px)** approach for desktop.

- **Mobile (Base):** 4-column grid with 24px side margins. The generous margins emphasize the "premium" nature of the brand.
- **Desktop:** 12-column grid. Components are grouped into logical "sections" with a 48px vertical gap to prevent the UI from feeling cramped.
- **Spacing Rhythm:** All spacing is derived from an 8px base unit. Internal card padding should consistently be 16px (2 units) or 20px for a more airy feel in featured items.

## Elevation & Depth
Elevation is used to distinguish between the "environment" (Cream background) and "interactive objects" (White cards).

1.  **Low Elevation (Resting Cards):** A very soft, diffused shadow: `0px 4px 20px rgba(26, 26, 26, 0.05)`.
2.  **High Elevation (Active/Hover):** Increase shadow spread and slightly lift the element: `0px 12px 32px rgba(26, 26, 26, 0.12)`.
3.  **Glassmorphism (Overlays):** For bottom navigation bars and floating filters, use a background blur of `20px` with a `white / 80% opacity` fill. Add a subtle `0.5px` white border to define the edge of the glass.

## Shapes
The shape language is "Soft-Modern." We avoid sharp corners to keep the brand feeling friendly and accessible.

- **Cards & Containers:** Use `16px` (rounded-lg) for main food cards and menu sections.
- **Buttons:** Use `12px` or full pill-shape for primary CTA buttons.
- **Input Fields:** Use `8px` to maintain a professional, structured look for data entry.
- **Images:** Food photography should always have rounded corners to match the container, never square.

## Components

### Food Service Cards
- **Structure:** Large-scale imagery (top), followed by a White surface.
- **Content:** Title in `title-md`, price in `primary-orange`.
- **Detail:** Include a "Quick Add" button—a circular `+` icon in Primary Orange—positioned at the bottom right corner of the card.

### Bottom Navigation (Mobile)
- **Style:** Glassmorphic background (80% blur).
- **Icons:** Thin-stroke 24px icons. Active state uses Primary Orange; inactive uses Deep Black at 40% opacity.

### Input Fields
- **Background:** Pure white.
- **Border:** 1px solid `#E2E2E2`. On focus, the border shifts to `Primary Orange` with a subtle orange outer glow (2px).
- **Labels:** Positioned above the field in `label-caps`.

### Status Indicators
- **Animated Tracking:** Use a "pulse" animation for active orders.
- **Color Logic:** Preparing (Orange), In-Transit (Blue), Delivered (Green).
- **Visual:** Use a horizontal progress bar with rounded caps and micro-illustrations of the tiffin box.

### Primary Buttons
- **Style:** Solid Primary Orange background with White text (`Inter Bold`). 
- **Interaction:** On press, the button scales down slightly (98%) to provide tactile feedback.