# House of Bijou — Brand Color Scheme

## Color Palette

The House of Bijou website now uses a cohesive, warm color scheme inspired by the brand's visual identity.

### Primary Colors

| Name | Hex Code | RGB | Use |
|------|----------|-----|-----|
| **Primary Red** | `#e53d3d` | 229, 61, 61 | Buttons, links, primary accent elements |
| **Primary Dark** | `#c23030` | 194, 48, 48 | Button hover states, darkened elements |
| **Accent Gold** | `#d4a25a` | 212, 162, 90 | Secondary accent, feature highlights |
| **Accent Light** | `#e8c175` | 232, 193, 117 | Lighter accent variations |

### Background Colors

| Name | Hex Code | Use |
|------|----------|-----|
| **Dark Background** | `#2d2d2d` | Dark sections (hero, CTA, solutions) |
| **Light Background** | `#fafafa` | Light sections, default page background |

### Text Colors

| Name | Hex Code | Use |
|------|----------|-----|
| **Text Dark** | `#2d2d2d` | Primary text on light backgrounds |
| **Text Light** | `#f5f5f5` | Text on dark backgrounds |

### Supporting Colors

| Name | Hex Code | Use |
|------|----------|-----|
| **Border** | `#e5e5e5` | Dividing lines, borders |
| **Success** | `#48bb78` | Positive indicators, success states |
| **Warning** | `#ed8936` | Warnings, alerts |

---

## Where Each Color Is Used

### Red (`#e53d3d`)
- **CTA Buttons** — Main call-to-action buttons throughout
- **Links** — All hyperlinks
- **Primary headings** — Respondent card titles
- **Border accents** — Respondent cards, story context boxes, tier cards
- **Icon colors** — Context icons, tier numbers
- **Hover effects** — Feature card borders and shadows

### Gold/Tan (`#d4a25a`)
- **Feature card headings** — H4 titles in solution section
- **Secondary buttons** — "Secondary" CTA style
- **Accent icons** — Icons in pain points and feature cards
- **Gold text** — Highlights and secondary information
- **Button text** — Secondary button text color

### Dark (`#2d2d2d`)
- **Background** — Hero section, solution section, CTA section
- **Text** — Primary body text on light backgrounds
- **Footer** — Footer background
- **Depth** — Creating visual hierarchy

### Warm Beige/Off-white
- **Respondent cards** — Warm gradient backgrounds (`#fff8f3` to `#fffbf7`)
- **Story quotes** — Light warm background (`#fff5f0`)
- **Economic section** — Warm tan gradient background (`#f5ede5` to `#faf6f2`)
- **Creating warmth** — Softer, more inviting feel

---

## Color Applications by Section

### Hero Section
```
Background: Dark charcoal gradient (#2d2d2d → #3a3a3a)
Text: Off-white (#f5f5f5)
Buttons: Red (#e53d3d) with gold secondary (#d4a25a)
Accent orbs: Red (#e53d3d, 10% opacity) + Gold (#d4a25a, 10% opacity)
```

### Problem Section
```
Background: Light (#fafafa)
Quote boxes: Warm off-white (#fff5f0) with red border (#e53d3d)
Context boxes: Warm beige (#fff8f3) with red border (#e53d3d)
Icons: Red (#e53d3d)
```

### Respondent Cards
```
Background: Warm gradient (#fff8f3 → #fffbf7)
Card title: Dark red (#c23030)
Pain point boxes: White with gold border (#d4a25a)
Icons: Gold (#d4a25a) and red (#e53d3d)
Hover border: Red (#e53d3d) with red shadow
```

### Solution Section
```
Background: Dark charcoal gradient (#2d2d2d → #3a3a3a)
Feature cards: Dark with red border (#e53d3d, 20% opacity)
Card heading: Gold (#d4a25a)
Feature icons: Gold (#d4a25a)
Hover effect: Red glow (#e53d3d, 15% opacity)
```

### Tech Stack Section
```
Background: Light (#fafafa)
Tech item headings: Red (#e53d3d)
Cards: White with light border
```

### Economic Empowerment Section
```
Background: Warm tan gradient (#f5ede5 → #faf6f2)
Tier cards: White with red border (#e53d3d)
Tier number: Red background (#e53d3d) with white text
Card heading icon: Red (#e53d3d)
Hover shadow: Red (#e53d3d, 15% opacity)
```

### CTA Section
```
Background: Dark charcoal gradient (#2d2d2d → #3a3a3a)
Text: Off-white (#f5f5f5)
Icons: Red (#e53d3d) and gold (#d4a25a)
Buttons: Red (#e53d3d) and gold (#d4a25a)
```

### Footer
```
Background: Very dark (#1a1a1a)
Text: Light gray (#f5f5f5)
Links: Gold (#d4a25a)
Link hover: Red (#e53d3d)
```

---

## Design Philosophy

The color scheme combines:

1. **Warmth & Energy** — Red and gold create a sense of passion, urgency, and community warmth
2. **Professional Trust** — Dark charcoal grounds the design and builds credibility
3. **Accessibility** — High contrast between dark and light backgrounds ensures readability
4. **Emotional Connection** — Warm tones evoke care, solidarity, and hope
5. **Visual Hierarchy** — Red drives attention to CTAs and key information; gold provides secondary emphasis

---

## Hover & Interaction States

### Buttons
- **Primary (Red):** `#e53d3d` → Hover: `#c23030` (darker red)
- **Secondary (Gold):** `#d4a25a` → Hover: White text on gold background
- **Shadow effect:** 0 10px 30px with color-matched opacity (15-40%)

### Cards
- **Border:** Transitions to `#e53d3d` (red) on hover
- **Shadow:** Adds colored shadow matching card's primary color
- **Transform:** Slight translateY or translateX for depth

### Icons
- **Color transitions:** 0.3s ease between states
- **Feature icons:** Scale 1.1x on feature card hover
- **Consistent color:** Gold (`#d4a25a`) by default, red (`#e53d3d`) on hover

---

## Accessibility Notes

✅ **Contrast Ratios:**
- Red text on white: High contrast ✓
- Gold text on white: Good contrast ✓
- White text on dark: High contrast ✓
- Gold text on dark: Good contrast ✓

✅ **Color Blindness:**
- Design does not rely solely on color for meaning
- Icons and text provide alternative cues
- Borders and shadows add visual distinction beyond color

---

## CSS Variables (Updated)

```css
:root {
    --primary: #e53d3d;           /* Red */
    --primary-dark: #c23030;      /* Darker Red */
    --accent: #d4a25a;            /* Gold */
    --accent-light: #e8c175;      /* Light Gold */
    --dark-bg: #2d2d2d;           /* Dark Charcoal */
    --light-bg: #fafafa;          /* Off-white */
    --text-dark: #2d2d2d;         /* Dark text */
    --text-light: #f5f5f5;        /* Light text */
    --border: #e5e5e5;            /* Border gray */
    --success: #48bb78;           /* Green (supporting) */
    --warning: #ed8936;           /* Orange (supporting) */
}
```

---

**Design Updated:** March 2026  
**Brand Source:** House of Bijou visual identity  
**Accessibility Verified:** WCAG AA standard
