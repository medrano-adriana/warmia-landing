---
name: WarmIA Emprendedora
colors:
  surface: '#f9f9ff'
  surface-dim: '#d3daef'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f3ff'
  surface-container: '#e9edff'
  surface-container-high: '#e1e8fd'
  surface-container-highest: '#dce2f7'
  on-surface: '#141b2b'
  on-surface-variant: '#3d4946'
  inverse-surface: '#293040'
  inverse-on-surface: '#edf0ff'
  outline: '#6d7a77'
  outline-variant: '#bdc9c5'
  surface-tint: '#006b5f'
  primary: '#00685d'
  on-primary: '#ffffff'
  primary-container: '#008376'
  on-primary-container: '#f4fffb'
  inverse-primary: '#72d8c8'
  secondary: '#6e3aca'
  on-secondary: '#ffffff'
  secondary-container: '#8856e5'
  on-secondary-container: '#fffbff'
  tertiary: '#006b2e'
  on-tertiary: '#ffffff'
  tertiary-container: '#00873c'
  on-tertiary-container: '#f7fff3'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#8ff4e3'
  primary-fixed-dim: '#72d8c8'
  on-primary-fixed: '#00201c'
  on-primary-fixed-variant: '#005047'
  secondary-fixed: '#ebddff'
  secondary-fixed-dim: '#d3bbff'
  on-secondary-fixed: '#250059'
  on-secondary-fixed-variant: '#581db3'
  tertiary-fixed: '#66ff8e'
  tertiary-fixed-dim: '#3de273'
  on-tertiary-fixed: '#002109'
  on-tertiary-fixed-variant: '#005322'
  background: '#f9f9ff'
  on-background: '#141b2b'
  surface-variant: '#dce2f7'
typography:
  display-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 38px
    fontWeight: '800'
    lineHeight: 48px
    letterSpacing: -0.02em
  display-hero-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 30px
    fontWeight: '800'
    lineHeight: 38px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '700'
    lineHeight: 30px
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 19px
    fontWeight: '600'
    lineHeight: 26px
  body-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '500'
    lineHeight: 28px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 17px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 23px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '700'
    lineHeight: 22px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  touch-target-min: 3.375rem
  card-p-mobile: 1.25rem
  card-p-desktop: 2rem
  gutter-mobile: 1rem
  gutter-desktop: 1.5rem
  stack-gap-sm: 0.75rem
  stack-gap-md: 1.25rem
  stack-gap-lg: 2rem
  section-gap-mobile: 3.5rem
  section-gap-desktop: 5.5rem
---

## Brand & Style

This design system targets Peruvian female entrepreneurs aged 40 and older—bodega owners, market stall merchants, and neighborhood store managers. The brand voice is warm, deeply respectful, crystal-clear, and empowering, stripping away fintech jargon in favor of approachable conversational reassurance.

The visual style merges **Modern Tactile Minimalism** with **Familiar Conversational Interfaces**:
- **Clarity over cleverness**: High contrast, expansive tap targets, and immediate legibility ensure effortless reading in busy, brightly lit retail environments or under direct sunlight.
- **Rooted confidence**: Combines the reassuring familiarity of WhatsApp's conversational ecosystem with the structured, forward-thinking institutional dignity of NEURA's deep-purple heritage.
- **Physical reassurance**: Cards resemble crisp, clean physical receipt pads or pristine notebooks, grounded by soft ambient shadows that communicate real-world tactility without sensory overload.

## Colors

The palette establishes immediate familiarity while maintaining authoritative financial trust and accessibility for older eyes:

- **Primary (`#128C7E`) & Tertiary Accent (`#25D366`)**: Direct conversational triggers. The deep emerald green serves as the high-contrast button anchor, while the bright WhatsApp green serves as an energetic notification, online badge, and pulse indicator.
- **Secondary (`#5B21B6` / `#4C1D95`)**: NEURA’s signature purple. Applied deliberately to corporate trust markers, category chips, verification seals, and security badges, anchoring the playful conversational greens in technological rigour.
- **Canvas (`#F1F8F3`)**: A clean, calming leaf-green tint that reduces glare compared to pure paper-white. It hosts a delicate, 5% opacity grid pattern that evokes ledger paper.
- **Surface (`#FFFFFF`)**: Pure brilliant white reserved for interactive cards, dialog bubbles, and transaction summaries to create distinct, high-contrast focal points.
- **Neutrals (`#111827` Primary Text, `#374151` Body Text, `#6B7280` Secondary Meta)**: Deep carbon tones ensuring contrast ratios consistently exceed WCAG AAA standards (7:1+) against white backgrounds.

## Typography

The design system relies entirely on **Plus Jakarta Sans** for its open apertures, tall x-height, and warm geometric roundness that feels human rather than mechanical.

Typography rules for the 40+ demographic:
- Never drop primary readable body copy below 16px; secondary helper captions must not fall below 14px.
- Line heights remain generous (minimum 1.45–1.55x font size) to prevent lines from crowding together when read quickly behind a shop counter.
- Weights are stepped deliberately: Body copy utilizes Medium (500) where standard apps use Regular (400) to ensure thin stroke renders remain visible on low-cost Android displays.
- High-contrast carbon (`#111827`) is enforced across all titles and values; muted grey text is strictly limited to non-essential timestamps and decorative metadata.

## Layout & Spacing

The layout is built mobile-first, prioritizing one-handed vertical operation:

- **Mobile Viewport (up to 640px)**: 4-column layout with fixed 16px outer margins. Content blocks stack vertically without horizontal multi-column splits to reduce cognitive load.
- **Tablet (641px–1024px)**: 8-column layout with 24px margins and gutters. Cards arrange into 2-column balancing grids.
- **Desktop (1025px+)**: 12-column layout capped at a maximum width of 1140px, centered with generous breathing room.

Every clickable surface adheres to the **54px minimum touch-target** rule (surpassing the standard 48px baseline) to accommodate quick taps by market vendors with busy hands. Vertical spacing between logical sections enforces a 56px rhythm on mobile to prevent accidental scrolling past critical actions.

## Elevation & Depth

Visual hierarchy leverages crisp surface separation instead of heavy, murky drop-shadows:

- **Canvas (Level 0)**: `#F1F8F3` base filled with a subtle, non-intrusive 24px-by-24px repeating geometric grid in `#E2EFE5`, communicating structure and accounting precision.
- **Resting Cards (Level 1)**: Crisp `#FFFFFF` surface with a delicate 1px perimeter border in `#E5E7EB` combined with an ambient shadow: `0 4px 16px -2px rgba(17, 24, 39, 0.05)`.
- **Interactive Focus & Floating CTA (Level 2)**: Elevated interaction layers featuring `0 10px 25px -4px rgba(18, 140, 126, 0.18)`—a soft emerald tint that lifts buttons and active WhatsApp preview chat bubbles directly toward the thumb.
- **Modals & Overlays (Level 3)**: `#FFFFFF` sheets set over an accessible 60% opacity carbon backdrop (`rgba(17, 24, 39, 0.6)`), utilizing a high-dispersion shadow `0 20px 40px -10px rgba(0, 0, 0, 0.2)`.

## Shapes

The shape system adopts a confident **Rounded (Level 2)** posture:
- Standard buttons and cards use `16px` (`rounded-lg`) border radii, evoking the friendly curves of mobile chat bubbles while preserving clear structural boundaries.
- Badges, pills, and status chips leverage full pill geometry (`9999px`) to immediately distinguish informational tags from interactive rectangular cards.
- Avatar frames and illustrative bodega iconography balance smooth rounded squares (`18px` squircle) with recognizable everyday silhouettes (cash registers, scales, coins, storefront awnings).

## Components

### Action Buttons (CTAs)
- **Primary CTA ("Empezar por WhatsApp")**: Minimum height of `56px`. Emerald `#128C7E` or vibrant `#25D366` background with pure white `#FFFFFF` or dark carbon `#064E3B` text, bold weight (700), font size 17px. Always includes an unmissable WhatsApp vector icon on the leading side and an arrow on the trailing end. Full width across mobile viewports.
- **Secondary Action**: White card background with a solid 2px border in NEURA Purple (`#5B21B6`), height 54px, text colored `#5B21B6` with bold weight.

### Conversational Preview Cards (Interactive Demos)
- Designed to replicate WhatsApp chat messages verbatim:
  - Inbound WarmIA bubbles: White background, left-aligned, soft 1px grey border, tail pointing left, featuring the WarmIA avatar, bold greeting, and actionable bullet points.
  - User response bubbles: Muted pastel green background (`#DCF8C6`), right-aligned, simulating realistic voice notes or simple everyday bodega queries (e.g., *"¿Cuánto debo cobrar por kilo de arroz hoy?"* or *"Anota fiado a Doña Carmen S/ 15"*).

### Trust & Institutional Badges
- Compact capsules featuring NEURA Morado (`#5B21B6` background with white text or `#F3E8FF` lavender background with `#4C1D95` text). Placed alongside headings to guarantee institutional credibility and bank-grade data security.

### Metric & Feature Cards
- Sturdy `#FFFFFF` containers with generous 20px interior padding.
- Each feature card leads with a high-contrast icon tile (48x48px, rounded 12px, soft green or purple wash).
- Titles use 19px bold carbon text, followed by 16px body copy that never exceeds 3 lines per paragraph.

### Floating Action Bar (Sticky Mobile Bottom Bar)
- Persistent pinned bottom bar spanning 100% width with a protective translucent blur (`backdrop-filter: blur(12px)`) over `#FFFFFF` at 92% opacity.
- Houses the single primary tap action: *"Hablar con WarmIA gratis"*, accompanied by the WhatsApp logo, guaranteeing immediate conversion without hunting through content.