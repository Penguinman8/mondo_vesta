---
name: Mondo Vesta Design System
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e4e2e1'
  on-surface: '#1b1c1c'
  on-surface-variant: '#4d453c'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0f0'
  outline: '#7f756b'
  outline-variant: '#d1c4b9'
  surface-tint: '#715b3e'
  primary: '#715b3e'
  on-primary: '#ffffff'
  primary-container: '#8b7355'
  on-primary-container: '#0a0400'
  inverse-primary: '#dfc29f'
  secondary: '#395f94'
  on-secondary: '#ffffff'
  secondary-container: '#9ec2fe'
  on-secondary-container: '#284f83'
  tertiary: '#5e5c58'
  on-tertiary: '#ffffff'
  tertiary-container: '#777470'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#fcdeba'
  primary-fixed-dim: '#dfc29f'
  on-primary-fixed: '#281903'
  on-primary-fixed-variant: '#574329'
  secondary-fixed: '#d5e3ff'
  secondary-fixed-dim: '#a7c8ff'
  on-secondary-fixed: '#001c3b'
  on-secondary-fixed-variant: '#1e477b'
  tertiary-fixed: '#e6e2dd'
  tertiary-fixed-dim: '#cac6c1'
  on-tertiary-fixed: '#1d1b19'
  on-tertiary-fixed-variant: '#484643'
  background: '#fcf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e1'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '600'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '500'
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
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  container-max: 1440px
  gutter: 32px
  margin-desktop: 80px
  margin-mobile: 20px
  stack-sm: 12px
  stack-md: 24px
  stack-lg: 64px
---

## Brand & Style
The design system embodies the "Art of Living" through a philosophy of **Curated Minimalism**. It balances the weight of luxury furniture with the lightness of coastal Mediterranean serenity. The target audience expects exclusivity and taste; therefore, the UI avoids traditional e-commerce urgency in favor of editorial discovery.

The visual style utilizes generous whitespace, sophisticated layering, and a focus on high-fidelity photography. It bridges the gap between a high-end interior design magazine and a digital gallery, prioritizing tactile cues and serene transitions to drive physical store visits.

## Colors
The palette is grounded in organic, architectural tones.
- **Surface (Primary Background):** `#F5F0EB` (Cream). This serves as the canvas for all content, providing a warmer, more sophisticated feel than pure white.
- **On-Surface (Text):** `#2C2C2C` (Charcoal). Used for maximum legibility while maintaining a softer contrast than pure black.
- **Accent (Wood/Earth):** `#8B7355`. Reserved for decorative elements, icon accents, and subtle dividers to evoke natural materials.
- **Action (Slate Blue):** `#4A6FA5`. A refined, muted blue used exclusively for primary calls-to-action (CTAs) and navigational highlights.

## Typography
The typography system relies on a high-contrast pairing between a classic serif and a systematic sans-serif. 

**Playfair Display** is used for all headlines and display text. It should be typeset with slightly tighter letter spacing in large formats to emphasize its editorial elegance. **Inter** handles all functional text, ensuring clarity and modern balance. 

For mobile, display sizes scale aggressively to ensure imagery remains the primary focus while maintaining a clear hierarchy.

## Layout & Spacing
This design system utilizes a **Fixed Grid** on desktop and a **Fluid Grid** on mobile. 
- **Desktop:** A 12-column grid with a maximum width of 1440px. Large 80px outer margins provide "breathing room" that mirrors luxury retail environments.
- **Mobile:** A 4-column fluid grid with 20px margins. 

Spacing rhythm follows a "Section-First" approach: use large vertical stacks (`stack-lg`) between different furniture collections to maintain a sense of curation and avoid visual clutter.

## Elevation & Depth
Depth is expressed through **Tonal Layers** and **Ambient Shadows** rather than structural borders. 
- **Tiers:** Elements sit on the `#F5F0EB` base. Secondary containers (like "In-Store Exclusive" callouts) use a slightly lighter version or a subtle white tint.
- **Shadows:** Only used on floating elements like navigation bars or image "polaroids." Shadows must be ultra-diffused: 15% opacity of the `#8B7355` accent color to create a warm, natural lift that feels like sunlight.
- **Overlays:** Full-bleed image backgrounds should use a 20% charcoal overlay when text is present to ensure accessibility without sacrificing the visual power of the furniture.

## Shapes
The shape language is **Soft (Level 1)**. 
Luxury furniture often features a mix of architectural straight lines and organic curves. The UI reflects this by using very subtle 4px (0.25rem) corner radii for buttons and cards. This provides a "finished" look that is friendlier than sharp corners but more professional and grounded than highly rounded shapes. 

Product frames and lifestyle photography should maintain sharp edges (0px) to feel like framed art pieces.

## Components
- **Primary Buttons:** Solid `#4A6FA5` (Slate Blue) with white Inter-medium text. Used for "Book a Showroom Visit."
- **Secondary Buttons:** Outlined charcoal (`#2C2C2C`) with 1px weight. Used for "View Collection."
- **Collection Cards:** Minimalist styling. A large 1:1 or 4:5 image ratio with the title in Playfair Display centered beneath it. No shadows on the card itself.
- **Showroom CTA:** A specialized component using a textured background or a subtle parallax effect on a photo of the Dénia storefront.
- **Navigation:** A centered logo with a transparent-to-cream transition on scroll. Navigation links use `label-sm` (uppercase) with a thin 1px underline on hover.
- **Interactive Map:** A stylized map component using the neutral palette to highlight the store's location in Dénia, avoiding standard Google Maps colors to maintain brand immersion.