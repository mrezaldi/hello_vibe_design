---
name: Caffeinated Brutalist
colors:
  surface: '#fff8f6'
  surface-dim: '#f2d3ce'
  surface-bright: '#fff8f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fff0ee'
  surface-container: '#ffe9e5'
  surface-container-high: '#ffe2dd'
  surface-container-highest: '#fbdcd6'
  on-surface: '#281714'
  on-surface-variant: '#564338'
  inverse-surface: '#3f2c28'
  inverse-on-surface: '#ffedea'
  outline: '#8a7266'
  outline-variant: '#ddc1b3'
  surface-tint: '#9a4600'
  primary: '#974400'
  on-primary: '#ffffff'
  primary-container: '#bb5808'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb68d'
  secondary: '#635f49'
  on-secondary: '#ffffff'
  secondary-container: '#e9e3c7'
  on-secondary-container: '#69654f'
  tertiary: '#006290'
  on-tertiary: '#ffffff'
  tertiary-container: '#007bb5'
  on-tertiary-container: '#fcfcff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbc9'
  primary-fixed-dim: '#ffb68d'
  on-primary-fixed: '#321200'
  on-primary-fixed-variant: '#763400'
  secondary-fixed: '#e9e3c7'
  secondary-fixed-dim: '#cdc7ad'
  on-secondary-fixed: '#1e1c0b'
  on-secondary-fixed-variant: '#4b4733'
  tertiary-fixed: '#cae6ff'
  tertiary-fixed-dim: '#8dcdff'
  on-tertiary-fixed: '#001e30'
  on-tertiary-fixed-variant: '#004b70'
  background: '#fff8f6'
  on-background: '#281714'
  surface-variant: '#fbdcd6'
typography:
  display-lg:
    fontFamily: Bricolage Grotesque
    fontSize: 56px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Bricolage Grotesque
    fontSize: 40px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Bricolage Grotesque
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Bricolage Grotesque
    fontSize: 28px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Bricolage Grotesque
    fontSize: 24px
    fontWeight: '700'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Bricolage Grotesque
    fontSize: 18px
    fontWeight: '500'
    lineHeight: '1.6'
  body-md:
    fontFamily: Bricolage Grotesque
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-lg:
    fontFamily: Bricolage Grotesque
    fontSize: 14px
    fontWeight: '700'
    lineHeight: '1.0'
    letterSpacing: 0.05em
  label-md:
    fontFamily: Bricolage Grotesque
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.0'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 4px
  xs: 8px
  sm: 16px
  md: 24px
  lg: 48px
  xl: 80px
  gutter: 20px
  margin-mobile: 16px
  margin-desktop: 40px
---

## Brand & Style
This design system blends the raw, high-energy impact of **Neubrutalism** with the aromatic warmth of a specialty coffee house. The brand personality is unapologetically bold yet inviting—like a double shot of espresso served in a cozy, sun-drenched nook. It targets urban professionals and coffee enthusiasts who appreciate craft, transparency, and high-quality materials.

The UI avoids subtle gradients and soft shadows in favor of hard-edged shapes, thick borders, and high-contrast layering. The emotional response is one of clarity and vigor, tempered by a "creamy" organic color palette that prevents the brutalist structures from feeling cold or clinical. Every interaction should feel tactile and decisive, mirroring the physical ritual of coffee preparation.

## Colors
The palette is built on a foundation of "Deep Espresso" (#2C1B18) for all structural elements (borders, shadows, text), ensuring a cohesive, high-contrast look. 

- **Primary (Rich Cocoa):** Used for primary actions and energetic brand moments.
- **Secondary (Cornsilk):** Acts as the primary surface color for cards and containers, providing a "milk-foam" softness against the white background.
- **Accent (Saddle Brown):** Reserved for highlights, secondary CTAs, and active states.
- **Background (Off-white Linen):** A warm, low-strain canvas that keeps the high-energy elements grounded.

## Typography
The system utilizes **Bricolage Grotesque** across all levels to maintain a cohesive, idiosyncratic character. To lean into the "warmth" of the coffee shop aesthetic, we avoid light weights. 

- **Headlines:** Use Bold (700) or ExtraBold (800) with tight tracking to create "blocks" of text that feel like physical signage.
- **Body:** Use Medium (500) for standard reading to ensure the variable widths of Bricolage feel intentional and sturdy.
- **Labels:** Always set in SemiBold or Bold, often in uppercase, to mirror industrial coffee packaging.

## Layout & Spacing
The layout follows a **Fluid Grid** model with a hard-coded 4px rhythm, echoing the 4px hard shadows of the UI elements. 

- **Desktop:** 12-column grid with 20px gutters. Content is contained within a max-width of 1280px but margins expand to fill the viewport.
- **Mobile:** 4-column grid with 16px margins. 
- **Rhythm:** Spacing between related items (like a label and an input) should be `xs` (8px). Spacing between sections should be `lg` (48px) to allow the "Off-white Linen" background to act as a visual palate cleanser. 
- **Borders:** All container elements must use a 2px solid stroke of "Deep Espresso."

## Elevation & Depth
In this design system, depth is not simulated via light physics but via **Hard Offsets**. 

- **Standard Elevation:** Elements (Cards, Buttons) feature a 4px horizontal and 4px vertical offset shadow using the "Deep Espresso" color (#2C1B18). 
- **Interactive States:** On hover, the offset increases to 6px/6px. On click/active, the offset resets to 0px (as if the element is being physically pressed into the page).
- **Tonal Layering:** Use "Cornsilk" (#FFF8DC) for the primary surface of elevated components to create a soft contrast against the "Off-white Linen" background.
- **Outlines:** Every elevated element must have a 2px solid "Deep Espresso" border.

## Shapes
We use a **Soft (0.25rem)** roundedness level. While traditional Brutalism uses sharp corners, this "Coffee House" variation adds a subtle radius to mimic the softened edges of wooden furniture and ceramic mugs.

- **Small elements (Checkboxes, Chips):** 0.25rem radius.
- **Medium elements (Buttons, Inputs):** 0.5rem radius (`rounded-lg`).
- **Large elements (Cards, Modals):** 0.75rem radius (`rounded-xl`).
- **Icons:** Use thick, 2px strokes with rounded caps to match the typography's weight.

## Components

- **Buttons:** Primary buttons use a "Rich Cocoa" background with "Cornsilk" text. They feature the signature 2px border and 4px hard shadow. Secondary buttons use a "Cornsilk" background with "Deep Espresso" text.
- **Inputs:** Text fields use a white background with a 2px "Deep Espresso" border. Focus states change the border color to "Rich Cocoa" and increase the shadow depth.
- **Cards:** Product cards for coffee beans or menu items should use "Cornsilk" as the surface color. The price should be highlighted in a "Rich Cocoa" badge.
- **Chips:** Used for coffee notes (e.g., "Fruity," "Nutty"). These are 2px outlined boxes with a 2px offset shadow, utilizing the "Saddle Brown" accent for the text.
- **Lists:** Use heavy 2px horizontal dividers between items. Bullet points should be replaced with small 4px x 4px solid "Deep Espresso" squares.
- **Navigation:** The header should be a fixed bar with a bottom 2px solid "Deep Espresso" border, using high-contrast bold typography for menu links.