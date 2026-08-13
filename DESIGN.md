---
name: SaaS Éducatif de Simulation d'Affaires
colors:
  surface: '#0b1326'
  surface-dim: '#0b1326'
  surface-bright: '#31394d'
  surface-container-lowest: '#060e20'
  surface-container-low: '#131b2e'
  surface-container: '#171f33'
  surface-container-high: '#222a3d'
  surface-container-highest: '#2d3449'
  on-surface: '#dae2fd'
  on-surface-variant: '#bbcabf'
  inverse-surface: '#dae2fd'
  inverse-on-surface: '#283044'
  outline: '#86948a'
  outline-variant: '#3c4a42'
  surface-tint: '#4edea3'
  primary: '#4edea3'
  on-primary: '#003824'
  primary-container: '#10b981'
  on-primary-container: '#00422b'
  inverse-primary: '#006c49'
  secondary: '#adc6ff'
  on-secondary: '#002e6a'
  secondary-container: '#0566d9'
  on-secondary-container: '#e6ecff'
  tertiary: '#ffb95f'
  on-tertiary: '#472a00'
  tertiary-container: '#e29100'
  on-tertiary-container: '#523200'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#6ffbbe'
  primary-fixed-dim: '#4edea3'
  on-primary-fixed: '#002113'
  on-primary-fixed-variant: '#005236'
  secondary-fixed: '#d8e2ff'
  secondary-fixed-dim: '#adc6ff'
  on-secondary-fixed: '#001a42'
  on-secondary-fixed-variant: '#004395'
  tertiary-fixed: '#ffddb8'
  tertiary-fixed-dim: '#ffb95f'
  on-tertiary-fixed: '#2a1700'
  on-tertiary-fixed-variant: '#653e00'
  background: '#0b1326'
  on-background: '#dae2fd'
  surface-variant: '#2d3449'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.05em
  numeric-data:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  container-padding: 24px
  gutter: 16px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style
The design system is rooted in a **Professional Fintech** aesthetic, optimized for high-density data visualization and immersive business simulations. It balances the seriousness of financial software with the clarity required for educational tools.

The visual style is **Corporate Modern with a Tech-Forward edge**, utilizing deep slate backgrounds to reduce eye strain during long analytical sessions. The emotional response should be one of confidence, precision, and strategic control. The interface uses subtle depth and high-contrast accents to guide the user through complex decision-making processes.

## Colors
This design system operates exclusively in **Dark Mode** to evoke a high-end command center environment.

- **Background Palette**: The primary canvas is a deep slate navy (`#0F172A`), with containers utilizing a slightly lighter slate (`#1E293B`) to establish hierarchy.
- **Accents**: Emerald Green (`#10B981`) is reserved for positive performance indicators (ROI, growth) and primary calls to action. Vibrant Blue (`#3B82F6`) identifies interactive components like sliders, links, and selection states.
- **Functional Colors**: Amber is utilized for warnings or moderate risk simulations, while Slate Blue is used for inactive or neutral data points.

## Typography
The typography system prioritizes legibility and technical precision. **Inter** serves as the primary typeface for its exceptional readability in dense layouts.

For financial figures, data tables, and simulation logs, **JetBrains Mono** is employed to ensure tabular figures align perfectly, aiding in quick vertical scanning of numerical columns. 

All headings are in French and should follow standard sentence-case capitalization to maintain a professional yet accessible tone. Use "Label-Caps" for section headers in sidebars or small metadata tags.

## Layout & Spacing
The design system utilizes a **Fluid Grid** model with high-density spacing to maximize the information visible on a single screen without overcrowding.

- **Desktop**: A 12-column grid with 16px gutters. Margins are fixed at 24px.
- **Dashboard Philosophy**: Layouts should prioritize a "modular dashboard" approach where cards can reflow. 
- **Density**: Use tight vertical spacing (`stack-sm`) for data entry rows and moderate spacing (`stack-md`) for distinct content groups within cards. 
- **Breakpoints**: 
  - Mobile: < 768px (single column, full width).
  - Tablet: 768px - 1280px (2-column layouts).
  - Desktop: > 1280px (Full multi-panel dashboard).

## Elevation & Depth
Depth is achieved through **Tonal Layering** rather than traditional shadows. This maintains a crisp, "flat-plus" fintech aesthetic.

- **Level 0 (Base)**: `#0F172A` - The main application background.
- **Level 1 (Cards)**: `#1E293B` - Content containers. These use a 1px solid border (`#334155`) to define boundaries.
- **Level 2 (Overlays/Modals)**: `#1E293B` with a subtle 10% white inner glow on the top edge and a deep, 20% opacity black drop shadow with a 20px blur.
- **Interactions**: On hover, interactive cards should slightly brighten their border color to `#475569` rather than lifting via shadow.

## Shapes
The shape language is disciplined and professional. A **Soft (0.25rem)** roundedness is the standard for most components (buttons, input fields, and small cards) to keep the UI feeling modern but structurally sound.

Larger dashboard containers and modals may use `rounded-lg` (0.5rem) to provide a clear visual container for complex data. Interactive elements like sliders and toggle tracks use fully rounded caps (pill-shaped) to distinguish them from static data containers.

## Components
Consistent styling across functional components ensures the simulation feels like a cohesive tool.

- **Buttons**:
    - *Primary (CTA)*: Emerald background, white text. No gradient.
    - *Secondary*: Transparent background, 1px Blue border, Blue text.
    - *Ghost*: No border, Slate-400 text, lightens on hover.
- **Interactive Sliders**: The track is a dark slate; the active fill is Vibrant Blue. The "thumb" (handle) is a white circle with a subtle blue ring.
- **Data Tables**: Headings use `label-caps` in Slate-400. Rows are separated by 1px borders (`#334155`). Alternate row striping is not used; use hover states to highlight rows.
- **Charts**: Use a minimalist approach. Grid lines should be faint (`#1E293B` or slightly lighter). Line charts for ROI use Emerald Green with a subtle gradient area fill.
- **Input Fields**: Dark backgrounds (`#0F172A`) with a 1px border. Focus state is a 1px Blue border with a 2px Blue outer glow (soft).
- **KPI Chips**: Small badges for "ROI", "Budget", "Croissance". Positive = Green background (10% opacity) with Green text. Warning = Amber background (10%) with Amber text.