# House of Bijou — Icon Guide

## Overview
All emojis have been replaced with professional **Font Awesome 6.4** icons. The site now uses consistent, scalable, and accessible icon graphics throughout.

---

## Color Scheme for Icons

All icons are styled using the House of Bijou brand color palette:

| Color Name | Hex Code | Icon Use |
|------------|----------|----------|
| **Primary Red** | `#e53d3d` | Story context icons, tier numbers, CTA icons, primary accents |
| **Accent Gold** | `#d4a25a` | Feature card icons, pain point icons, secondary accents |
| **Text Dark** | `#2d2d2d` | Supporting text elements |
| **Text Light** | `#f5f5f5` | Icons on dark backgrounds |

**Icon transitions:** Smooth color changes (0.3s ease) on hover and interaction states.

---

## Icon Usage by Section

### Problem Section
| Icon | Use | Appears As | Color |
|------|-----|-----------|-------|
| `fas fa-search` | Digital Tracking & Control | Magnifying glass | Red (#e53d3d) |
| `fas fa-building` | Banking Exclusion | Bank building | Red (#e53d3d) |
| `fas fa-gavel` | Criminalization & Custody Threats | Gavel/judge | Red (#e53d3d) |
| `fas fa-ban` | Erasure & Inauthenticity | Ban/prohibition sign | Red (#e53d3d) |

### Respondent Cards
| Icon | Use | Appears As | Color |
|------|-----|-----------|-------|
| `fas fa-heart` | Survivor respondent | Heart | Red (#e53d3d) |
| `fas fa-shield-alt` | Stealth/Disguise pain point | Shield | Gold (#d4a25a) |
| `fas fa-wallet` | Account Control pain point | Wallet | Gold (#d4a25a) |
| `fas fa-accessible-icon` | Accessibility First pain point | Accessibility symbol | Gold (#d4a25a) |
| `fas fa-lock` | Traceless Support pain point | Lock | Gold (#d4a25a) |
| `fas fa-transgender` | Trans/Gender-Queer respondent | Transgender symbol | Red (#e53d3d) |
| `fas fa-map-marker-alt` | Location Privacy pain point | Location pin | Gold (#d4a25a) |
| `fas fa-exclamation-circle` | Panic Response pain point | Exclamation in circle | Gold (#d4a25a) |
| `fas fa-coins` | Hard-to-Freeze Income pain point | Coins | Gold (#d4a25a) |
| `fas fa-rainbow` | Authentic Space pain point | Rainbow | Gold (#d4a25a) |

### Solution/Features Section
| Icon | Use | Appears As | Color |
|------|-----|-----------|-------|
| `fas fa-calculator` | Stealth Mode | Calculator | Gold (#d4a25a) → Red (#e53d3d) on hover |
| `fas fa-exclamation-triangle` | Panic Alert | Warning triangle | Gold (#d4a25a) → Red (#e53d3d) on hover |
| `fas fa-location-dot` | Mutual Check-Ins | Location dot | Gold (#d4a25a) → Red (#e53d3d) on hover |
| `fas fa-comments` | Encrypted Chat | Comments/chat bubbles | Gold (#d4a25a) → Red (#e53d3d) on hover |
| `fas fa-money-bill-wave` | Low-Trace Transfers | Waving money bill | Gold (#d4a25a) → Red (#e53d3d) on hover |
| `fas fa-handshake` | Mutual Aid | Handshake | Gold (#d4a25a) → Red (#e53d3d) on hover |

### Tech Stack Section
| Icon | Use | Appears As | Color |
|------|-----|-----------|-------|
| `fas fa-rocket` | Rails + PostgreSQL | Rocket | Red (#e53d3d) |
| `fas fa-palette` | Hotwire + Tailwind | Artist palette | Red (#e53d3d) |
| `fas fa-mobile-alt` | Turbo Native | Mobile phone | Red (#e53d3d) |
| `fas fa-phone-alt` | USSD + SMS | Phone | Red (#e53d3d) |
| `fas fa-shield-alt` | AES-256 + Signal Protocol | Shield | Red (#e53d3d) |
| `fas fa-database` | Local-First | Database | Red (#e53d3d) |

### Economic Empowerment Tiers
| Icon | Use | Appears As | Color |
|------|-----|-----------|-------|
| `fas fa-first-aid` | Tier 1: Emergency Survival | First aid kit | Red (#e53d3d) |
| `fas fa-briefcase` | Tier 2: Sustainable Income | Briefcase | Red (#e53d3d) |
| `fas fa-star` | Tier 3: Economic Autonomy | Star | Red (#e53d3d) |
| `fas fa-users` | Tier 4: Collective Power | Multiple users | Red (#e53d3d) |

### Roadmap Section
| Icon | Use | Appears As | Color |
|------|-----|-----------|-------|
| `fas fa-tools` | Phase 1: MVP | Tools/wrench | Red (#e53d3d) |
| `fas fa-mobile-alt` | Phase 2: Mobile & Scale | Mobile phone | Red (#e53d3d) |
| `fas fa-rocket` | Phase 3: Ecosystem & Sustainability | Rocket | Red (#e53d3d) |

### CTA & Values Section
| Icon | Use | Appears As | Color |
|------|-----|-----------|-------|
| `fas fa-handshake` | Community leadership | Handshake | Red (#e53d3d) |
| `fas fa-bolt` | Economic empowerment | Lightning bolt | Red (#e53d3d) |
| `fas fa-lock` | Privacy and security | Lock | Red (#e53d3d) |
| `fas fa-heart` | Authentic spaces | Heart | Red (#e53d3d) |
| `fas fa-universal-access` | Accessibility | Universal access symbol | Red (#e53d3d) |
| `fas fa-envelope` | Partner With Us button | Envelope/email | White on Red background |
| `fab fa-github` | See Our Code button | GitHub logo | White on Gold background |

### Footer/Social Links
| Icon | Use | Appears As | Color |
|------|-----|-----------|-------|
| `fab fa-twitter` | Twitter link | Twitter logo | Gold (#d4a25a) |
| `fab fa-instagram` | Instagram link | Instagram logo | Gold (#d4a25a) |
| `fab fa-github` | GitHub link | GitHub logo | Gold (#d4a25a) |

---

## CSS Styling Applied

All icons inherit from a base style that:
- Sets `display: inline-block` for proper alignment
- Adds `margin-right: 0.5rem` for spacing from text
- Includes smooth color transitions (`transition: color 0.3s ease`)

### Size Variations

**Feature Icons (large)**
- Font size: 3rem (desktop), 2.5rem (mobile)
- Color: Gold (`#d4a25a`) by default
- Hover color: Red (`#e53d3d`)
- Scale transforms on hover: 1.1x

**In-text Icons (small)**
- Font size: 0.95em (inherits from context)
- Color: Gold (`#d4a25a`) for secondary accents, Red (`#e53d3d`) for primary
- Smooth transitions between color states (0.3s ease)

**Story Context Icons**
- Color: Red (`#e53d3d`)
- Margin right: 0.75rem
- Used in problem section boxes

**Pain Point Icons**
- Color: Gold (`#d4a25a`)
- Margin right: 0.75rem
- Used in respondent cards

**Tier Card Icons**
- Color: Red (`#e53d3d`) for tier numbers and headings
- Margin right: 0.75rem
- Used in economic empowerment section

---

## Color Palette Reference

The icons use the House of Bijou brand color scheme:

```css
--primary: #e53d3d;           /* Red - Primary accent */
--accent: #d4a25a;            /* Gold - Secondary accent */
--text-dark: #2d2d2d;         /* Dark charcoal text */
--text-light: #f5f5f5;        /* Light text on dark bg */
```

---

## Technical Details

**Font Awesome Version:** 6.4.0  
**CDN Link:** `https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css`

**Icon Prefixes Used:**
- `fas` = Solid icons
- `fab` = Brand/logo icons

**Total Icons on Page:** 50+  
**All icons are accessible:** Wrapped in semantic HTML with proper contrast ratios

---

## Benefits of Icon-Based Design

✅ **Professional Look:** Font Awesome icons are universally recognized and professional  
✅ **Scalable:** Icons remain crisp at any size (unlike emojis which have limited quality)  
✅ **Consistent:** All icons follow the same design system and style  
✅ **Accessible:** Icons have proper semantic meaning and color contrast  
✅ **Lightweight:** SVG-based icons are smaller than emoji alternatives  
✅ **Customizable:** Colors, sizes, and transforms applied via CSS  
✅ **Responsive:** Icons scale appropriately on mobile/tablet/desktop  

---

## Notes for GitHub Pages Deployment

The Font Awesome CDN is embedded in the HTML `<head>`, so:
- No additional files need to be downloaded
- Icons will display correctly on any GitHub Pages deployment
- No build step needed; works as-is
- Fallback colors ensure readability even if CDN is unreachable

---

**Last Updated:** March 2026  
**For Questions:** Check Font Awesome documentation at https://fontawesome.com
