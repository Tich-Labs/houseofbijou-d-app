# House of Bijou — Icon Guide

## Overview
All emojis have been replaced with professional **Font Awesome 6.4** icons. The site now uses consistent, scalable, and accessible icon graphics throughout.

---

## Icon Usage by Section

### Problem Section
| Icon | Use | Appears As |
|------|-----|-----------|
| `fas fa-search` | Digital Tracking & Control | Magnifying glass |
| `fas fa-building` | Banking Exclusion | Bank building |
| `fas fa-gavel` | Criminalization & Custody Threats | Gavel/judge |
| `fas fa-ban` | Erasure & Inauthenticity | Ban/prohibition sign |

### Respondent Cards
| Icon | Use | Appears As |
|------|-----|-----------|
| `fas fa-heart` | Survivor respondent | Heart |
| `fas fa-shield-alt` | Stealth/Disguise pain point | Shield |
| `fas fa-wallet` | Account Control pain point | Wallet |
| `fas fa-accessible-icon` | Accessibility First pain point | Accessibility symbol |
| `fas fa-lock` | Traceless Support pain point | Lock |
| `fas fa-transgender` | Trans/Gender-Queer respondent | Transgender symbol |
| `fas fa-map-marker-alt` | Location Privacy pain point | Location pin |
| `fas fa-exclamation-circle` | Panic Response pain point | Exclamation in circle |
| `fas fa-coins` | Hard-to-Freeze Income pain point | Coins |
| `fas fa-rainbow` | Authentic Space pain point | Rainbow |

### Solution/Features Section
| Icon | Use | Appears As |
|------|-----|-----------|
| `fas fa-calculator` | Stealth Mode | Calculator |
| `fas fa-exclamation-triangle` | Panic Alert | Warning triangle |
| `fas fa-location-dot` | Mutual Check-Ins | Location dot |
| `fas fa-comments` | Encrypted Chat | Comments/chat bubbles |
| `fas fa-money-bill-wave` | Low-Trace Transfers | Waving money bill |
| `fas fa-handshake` | Mutual Aid | Handshake |

### Tech Stack Section
| Icon | Use | Appears As |
|------|-----|-----------|
| `fas fa-rocket` | Rails + PostgreSQL | Rocket |
| `fas fa-palette` | Hotwire + Tailwind | Artist palette |
| `fas fa-mobile-alt` | Turbo Native | Mobile phone |
| `fas fa-phone-alt` | USSD + SMS | Phone |
| `fas fa-shield-alt` | AES-256 + Signal Protocol | Shield |
| `fas fa-database` | Local-First | Database |

### Economic Empowerment Tiers
| Icon | Use | Appears As |
|------|-----|-----------|
| `fas fa-first-aid` | Tier 1: Emergency Survival | First aid kit |
| `fas fa-briefcase` | Tier 2: Sustainable Income | Briefcase |
| `fas fa-star` | Tier 3: Economic Autonomy | Star |
| `fas fa-users` | Tier 4: Collective Power | Multiple users |

### Roadmap Section
| Icon | Use | Appears As |
|------|-----|-----------|
| `fas fa-tools` | Phase 1: MVP | Tools/wrench |
| `fas fa-mobile-alt` | Phase 2: Mobile & Scale | Mobile phone |
| `fas fa-rocket` | Phase 3: Ecosystem & Sustainability | Rocket |

### CTA & Values Section
| Icon | Use | Appears As |
|------|-----|-----------|
| `fas fa-handshake` | Community leadership | Handshake |
| `fas fa-bolt` | Economic empowerment | Lightning bolt |
| `fas fa-lock` | Privacy and security | Lock |
| `fas fa-heart` | Authentic spaces | Heart |
| `fas fa-universal-access` | Accessibility | Universal access symbol |
| `fas fa-envelope` | Partner With Us button | Envelope/email |
| `fab fa-github` | See Our Code button | GitHub logo |

### Footer/Social Links
| Icon | Use | Appears As |
|------|-----|-----------|
| `fab fa-twitter` | Twitter link | Twitter logo |
| `fab fa-instagram` | Instagram link | Instagram logo |
| `fab fa-github` | GitHub link | GitHub logo |

---

## CSS Styling Applied

All icons inherit from a base style that:
- Sets `display: inline-block` for proper alignment
- Adds `margin-right: 0.5rem` for spacing from text
- Includes smooth color transitions (`transition: color 0.3s ease`)

### Size Variations

**Feature Icons (large)**
- Font size: 3rem (desktop), 2.5rem (mobile)
- Color: `--accent` (cyan)
- Hover color: `--primary` (magenta)
- Scale transforms on hover: 1.1x

**In-text Icons (small)**
- Font size: 0.95em (inherits from context)
- Color matches context (accent, success, warning, etc.)
- Smooth transitions between color states

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
