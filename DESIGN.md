---
name: Pathak Educational Foundation
colors:
  surface: '#faf8ff'
  surface-dim: '#dad9e0'
  surface-bright: '#faf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f3f9'
  surface-container: '#efedf3'
  surface-container-high: '#e9e7ee'
  surface-container-highest: '#e3e2e8'
  on-surface: '#1a1b20'
  on-surface-variant: '#444650'
  inverse-surface: '#2f3035'
  inverse-on-surface: '#f1f0f6'
  outline: '#757682'
  outline-variant: '#c5c6d2'
  surface-tint: '#435b9f'
  primary: '#00113a'
  on-primary: '#ffffff'
  primary-container: '#002366'
  on-primary-container: '#758dd5'
  inverse-primary: '#b3c5ff'
  secondary: '#705d00'
  on-secondary: '#ffffff'
  secondary-container: '#fcd400'
  on-secondary-container: '#6e5c00'
  tertiary: '#001903'
  on-tertiary: '#ffffff'
  tertiary-container: '#003009'
  on-tertiary-container: '#46a24e'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#b3c5ff'
  on-primary-fixed: '#00174a'
  on-primary-fixed-variant: '#2a4386'
  secondary-fixed: '#ffe16d'
  secondary-fixed-dim: '#e9c400'
  on-secondary-fixed: '#221b00'
  on-secondary-fixed-variant: '#544600'
  tertiary-fixed: '#99f899'
  tertiary-fixed-dim: '#7edb7f'
  on-tertiary-fixed: '#002105'
  on-tertiary-fixed-variant: '#005316'
  background: '#faf8ff'
  on-background: '#1a1b20'
  surface-variant: '#e3e2e8'
typography:
  h1:
    fontFamily: notoSerif
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  h2:
    fontFamily: notoSerif
    fontSize: 36px
    fontWeight: '600'
    lineHeight: '1.3'
  h3:
    fontFamily: notoSerif
    fontSize: 28px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: beVietnamPro
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: beVietnamPro
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: beVietnamPro
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.08em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  container-max: 1200px
  gutter: 24px
---

## Brand & Style

The design system is built on a "Premium Nurturing" philosophy. It balances the high-end, academic prestige required to gain parental trust with the warmth and approachability of an early childhood environment. The style is **Soft-Modernism**: a blend of clean, professional layouts with organic, tactile elements that feel safe and inviting.

The target audience consists of discerning parents who seek the best for their children. To evoke an emotional response of security and inspiration, the UI utilizes generous whitespace, delicate animations, and a sophisticated color palette that avoids the harshness of typical primary-colored "kids' apps."

- **Core Aesthetic:** Sophisticated, airy, and gentle.
- **Visual Movement:** Smooth, easing-heavy transitions that mimic natural movement.
- **Imagery Style:** High-quality photography featuring soft focus, natural lighting, and authentic interactions.

## Typography

Typography establishes the "Premium Educational" tone. **Noto Serif** (serving the role of Playfair Display) is used for headlines to convey heritage and academic excellence. Its elegant serifs provide a rhythmic contrast to the UI's rounded shapes.

**Be Vietnam Pro** (serving the role of DM Sans) handles all functional and body text. Its contemporary, slightly geometric but open letterforms ensure high legibility for busy parents.

- **Headlines:** Always use Noto Serif. Maintain tight letter spacing for large titles to keep them looking editorial.
- **Body:** Use Be Vietnam Pro with generous line heights (1.6) to ensure the interface feels breathable and easy to scan.

## Layout & Spacing

The layout philosophy follows a **Fixed-Width Centered Grid** for desktop to maintain an editorial feel, transitioning to a fluid model for mobile. We utilize a soft 8px spatial grid. 

Margins are intentionally wide to prevent the UI from feeling "crowded," which can cause anxiety. Vertical rhythm is driven by the "L" and "XL" spacing tokens to separate major content sections, creating a sense of calm progression as the user scrolls.

- **Grid:** 12-column system with 24px gutters.
- **Padding:** Use "MD" (24px) for internal card padding and "LG" (48px) for section vertical padding.

## Elevation & Depth

This design system avoids harsh shadows. Depth is achieved through **Ambient Diffused Shadows** and **Tonal Layering**. 

Components use long, soft blurs with very low opacity (5-10%) tinted with the Primary Royal Blue color. This makes elements appear as if they are gently floating above the pastel background rather than casting a heavy shadow. 

- **Surface Tiers:** Background (Pastel) > Card (Pure White) > Floating Action (White with Shadow).
- **Shadow Profile:** 0px Y-offset, 20px blur, 0px spread, 5% opacity of #002366.

## Shapes

The shape language is defined by large, friendly radii. There are no sharp corners in the design system. This "soft-touch" approach makes the digital environment feel child-safe and modern.

- **Standard Elements:** 0.5rem (8px) for inputs and small tags.
- **Containers & Cards:** 1rem (16px) for main content blocks.
- **Featured Elements:** 1.5rem (24px) for hero images or large call-out cards.

## Components

### Buttons
Primary buttons use the Royal Blue with white text and a 24px (Pill-style) radius. Secondary buttons should use a Soft Yellow background with Royal Blue text to maintain warmth and high legibility. All buttons feature a subtle "lift" on hover via an expanded shadow.

### Cards
Cards are the primary container. They must be Pure White with a 16px corner radius and a soft ambient shadow. Avoid borders; use depth to define the card's perimeter against the pastel background.

### Input Fields
Inputs use a Soft Pastel Blue background with a subtle 1px border in a darker tint of the same color. Focus states transition the border to Royal Blue and add a soft outer glow.

### Chips & Tags
Used for categories like "Ages 3-5" or "Creative Arts." These use the Light Green (Growth) palette with dark green text, featuring a fully rounded (pill) shape.

### Progress Indicators
Educational milestones are tracked using "Growing Vines" or soft-stepper bars using the Light Green tertiary color.

### Additional Components
- **Testimonial Bubbles:** Large, rounded speech bubbles for parent reviews.
- **Nurture Badges:** Circular, high-end seals for certifications or foundation achievements.