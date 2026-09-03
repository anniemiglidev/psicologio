---
name: Serene Psychology Narrative
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f4'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#464555'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f0f1f1'
  outline: '#777587'
  outline-variant: '#c7c4d8'
  surface-tint: '#4f44e2'
  primary: '#4d41df'
  on-primary: '#ffffff'
  primary-container: '#675df9'
  on-primary-container: '#fffbff'
  inverse-primary: '#c4c0ff'
  secondary: '#964732'
  on-secondary: '#ffffff'
  secondary-container: '#fd997f'
  on-secondary-container: '#762f1c'
  tertiary: '#5c51a0'
  on-tertiary: '#ffffff'
  tertiary-container: '#756abb'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e3dfff'
  primary-fixed-dim: '#c4c0ff'
  on-primary-fixed: '#100069'
  on-primary-fixed-variant: '#3622ca'
  secondary-fixed: '#ffdbd1'
  secondary-fixed-dim: '#ffb5a1'
  on-secondary-fixed: '#3c0800'
  on-secondary-fixed-variant: '#78311d'
  tertiary-fixed: '#e5deff'
  tertiary-fixed-dim: '#c8bfff'
  on-tertiary-fixed: '#1a065c'
  on-tertiary-fixed-variant: '#463b89'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  headline-lg:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Manrope
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: Manrope
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  button:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-margin: 20px
  stack-gap-sm: 8px
  stack-gap-md: 16px
  stack-gap-lg: 32px
  section-padding: 48px
---

## Brand & Style

This design system is built for a professional psychology practice, emphasizing empathy, trust, and mental well-being. The visual narrative balances clinical authority with a warm, approachable human touch.

The chosen style is **Modern Corporate with Soft Accents**, utilizing large, welcoming photography and a structured, legible layout. For the mobile experience, the focus shifts to ease of navigation and a "safe-space" feel, achieved through generous white space and soft tonal transitions. The aesthetic avoids sharp medical coldness in favor of a "living room" warmth—professional but deeply personal.

- **Emotional Response:** Comforted, heard, safe, and hopeful.
- **Visual Strategy:** High-quality portrait photography paired with solid blocks of brand purple to create a rhythmic "scroll story" that guides the user from pain points to solutions.

## Colors

The palette is anchored by a deep, calming purple and energized by a soft terracotta-orange for actions. 

- **Primary (Purple):** Used for section backgrounds and brand identity. It provides a sense of depth and stability. On mobile, use varying tints of this purple to differentiate content blocks.
- **Secondary (Terracotta/Orange):** Reserved exclusively for Call-to-Action (CTA) elements. This high-contrast color ensures the "Book a Consultation" action is always visible.
- **Neutral (White/Grey):** High-white backgrounds are used to provide "breathing room" between dense information sections.
- **Tonal Accents:** Light lavender or off-white shades are used for card backgrounds to prevent visual fatigue.

## Typography

The design system utilizes **Manrope** for its exceptional legibility and modern, geometric character that remains friendly. 

- **Headlines:** Use Bold weights for primary page titles to establish clear hierarchy. Use Italic variations (as seen in the reference) sparingly for subheaders to add a personal, "spoken" quality.
- **Body:** Standardized at 16px for mobile to ensure accessibility. Line height is kept generous (1.5x) to aid reading of long-form therapeutic explanations.
- **Scalability:** Large headlines on desktop scale down significantly on mobile to avoid excessive line breaks and "widows" in the text.

## Layout & Spacing

For the mobile experience, the layout follows a **Fluid Single-Column Grid**.

- **Margins:** A consistent 20px horizontal margin ensures content doesn't touch the edges of the device.
- **Vertical Rhythm:** Sections are separated by 48px to 64px of vertical space, creating a "breathable" flow. 
- **Content Stacking:** On mobile, multi-column desktop grids (like the benefits or service cards) must reflow into a vertical stack.
- **Visual Breaks:** Use full-bleed background colors (brand purple) to break up the long scroll and signal a change in context (e.g., transitioning from "About" to "Services").

## Elevation & Depth

This design system uses **Tonal Layers** and **Soft Ambient Shadows** to create a sense of tactile professionalism.

- **Cards:** Elevation is achieved through a subtle 1px border or a very soft, diffused shadow (0px 4px 20px rgba(0,0,0,0.05)). Avoid heavy shadows.
- **Overlays:** For mobile menus or appointment modals, use a light backdrop blur (Glassmorphism) to keep the user grounded in their current context.
- **Tonal Tiering:** Use a slightly darker shade of white or a very light lavender (#F4F4FF) for container backgrounds to distinguish nested content without adding "weight."

## Shapes

The shape language is consistently **Rounded**, reinforcing the themes of softness and approachability.

- **Standard Radius:** 8px (0.5rem) for cards and input fields.
- **Large Radius:** 16px (1rem) for decorative containers or image masks.
- **Pill Shape:** Fully rounded corners for primary buttons and chips to make them feel "clickable" and friendly.
- **Image Treatment:** Use consistent corner rounding on all photography to integrate portraits into the UI seamlessly.

## Components

- **Buttons:** Primary buttons use the secondary orange (#F08F75) with white text. They are pill-shaped with a subtle hover/active state (slightly darker). On mobile, buttons should be full-width for easy thumb reach.
- **Benefit Cards:** Use a numbered circle (light purple background) followed by a bold title and body text. In mobile view, these are vertically stacked with 16px spacing.
- **Service Cards:** Feature a background image with a semi-transparent purple overlay. Titles are centered and white. Ensure the text remains legible over images by using a 40-60% black or purple gradient scrim.
- **Accordions (FAQ):** Use a 1px solid border with a chevron icon. On mobile, these are essential for reducing "scroll fatigue" by hiding long answers until requested.
- **Testimonial Cards:** Simple white backgrounds with a soft shadow. Include a small avatar and star rating (orange) to build social proof.
- **Input Fields:** 8px rounded corners, 1px grey border that turns purple on focus. Labels sit clearly above the input.