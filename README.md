# demo_site_real_esate
This is a single-file HTML website built for Zunnoon Group (Est. 2005, Lahore, Pakistan) — a multi-division enterprise with operations spanning eight business verticals. The site is designed to establish premium brand positioning while remaining fully functional across all screen sizes, from a 320px mobile screen to a 4K desktop display.
# Zunnoon Group — Corporate Website

> **Building Better Tomorrows** — A fully responsive, production-grade corporate website for Zunnoon Group, a diversified Pakistani conglomerate operating across Real Estate, Engineering, Travel, Education, Marketing, and Consumer Products.

---

## Live Preview

Open `zunnoon-group.html` directly in any browser — no build step, no dependencies, no server required.

---

## About the Project

This is a single-file HTML website built for **Zunnoon Group (Est. 2005, Lahore, Pakistan)** — a multi-division enterprise with operations spanning eight business verticals. The site is designed to establish premium brand positioning while remaining fully functional across all screen sizes, from a 320px mobile screen to a 4K desktop display.

The design language draws from the brand's existing visual identity: deep navy backgrounds, amber-gold accents, Playfair Display for headings, and DM Sans for body copy — chosen to project authority, trust, and legacy in the Pakistan real estate and services market.

---

## Features

- **Fully Responsive** — Three-tier breakpoint system (desktop / tablet / mobile) with a hamburger navigation, collapsible mobile menu, and adaptive grid layouts at every section
- **Animated Project Cards** — Hover interactions with image zoom, overlay fade, card lift, and gold border reveal using pure CSS transitions
- **Live Counter Animation** — Stats section counts up on scroll using IntersectionObserver
- **Scroll Progress Indicator** — Gold gradient progress bar fixed at the top of the viewport
- **Quick Inquiry Form** — Lead-capture form embedded in the hero section (desktop only)
- **WhatsApp Float Button** — Fixed bottom-right contact shortcut
- **Sticky Navigation** — Backdrop-blur nav with active link state
- **Utility Bar** — Contact info strip and social links above the nav (hidden on mobile)
- **Fade-Up Scroll Animations** — Staggered reveal on all cards and grid items as they enter the viewport
- **Brand Partners Strip** — Division showcase above the footer
- **Newsletter Signup** — Email capture field in the footer column

---

## Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 (semantic) |
| Styling | CSS3 — custom properties, CSS Grid, Flexbox, clamp() fluid sizing |
| Interactivity | Vanilla JavaScript (ES6+) — no frameworks |
| Icons | Tabler Icons (webfont, CDN) |
| Fonts | Google Fonts — Playfair Display + DM Sans |
| Images | Unsplash (placeholder — replace with production assets) |

Zero npm. Zero build tools. Zero dependencies to install.

---

## Sections

| # | Section | Description |
|---|---|---|
| 1 | Utility Bar | Phone, email, hours, social links |
| 2 | Sticky Nav | Logo, links, CTA button, mobile hamburger |
| 3 | Hero | Headline, subtext, CTA buttons, quick inquiry form |
| 4 | Stats Strip | Animated counters — clients, projects, years, support |
| 5 | Featured Projects | 4-card grid with hover image zoom animation |
| 6 | Services / Divisions | 6-card ecosystem overview with icons |
| 7 | Why Choose Us | Split layout — value props + retention stats |
| 8 | Testimonials | 3-card client review grid with star ratings |
| 9 | Brand Partners | Division pill strip |
| 10 | CTA | Centered call-to-action with decorative rings |
| 11 | Footer | Links, contact info, newsletter, social, legal |

---

## Getting Started

```bash
# Clone the repository
git clone https://github.com/your-username/zunnoon-group-website.git

# Navigate into the folder
cd zunnoon-group-website

# Open in browser (macOS)
open zunnoon-group.html

# Open in browser (Windows)
start zunnoon-group.html

# Open in browser (Linux)
xdg-open zunnoon-group.html
```

No `npm install`. No `webpack`. Just open the file.

---

## Customisation Guide

### Replace placeholder images
Search for `images.unsplash.com` in the HTML and swap each URL with your hosted image paths:

```html
<!-- Before -->
<img src="https://images.unsplash.com/photo-xxx?w=600&q=80" alt="...">

<!-- After -->
<img src="./assets/images/basharat-heights.jpg" alt="...">
```

### Update brand colors
All colors are defined as CSS custom properties at the top of the `<style>` block:

```css
:root {
  --gold:        #C8960A;
  --gold-light:  #E8B420;
  --navy:        #0A1628;
  --navy-mid:    #0D1E38;
}
```

### Update contact details
Replace the placeholder values in the utility bar, footer contact column, and the WhatsApp float button href.

### Connect the forms
The Quick Inquiry form and Newsletter input are currently static HTML. Wire them to your backend or a service like Formspree, EmailJS, or HubSpot:

```html
<!-- Formspree example -->
<form action="https://formspree.io/f/your-form-id" method="POST">
```

---

## Responsive Breakpoints

| Breakpoint | Layout behaviour |
|---|---|
| > 900px | Full desktop — utility bar visible, inline nav, hero form visible, 4-col stats |
| ≤ 900px | Tablet — hamburger nav, hero form hidden, 2-col stats, stacked why section |
| ≤ 600px | Mobile — single-col projects, stacked CTA buttons, simplified footer |
| ≤ 380px | Small mobile — single-col divisions, full-width buttons throughout |

---

## Project Structure

```
zunnoon-group-website/
├── zunnoon-group.html   # Entire site — self-contained single file
├── README.md            # This file
└── assets/              # Add your production images here
    └── images/
```

---

## Divisions Featured

- **Basharat Sons Estate & Builders** — Real Estate
- **Basharat Sons Engineering** — Construction & Engineering
- **Zunnoon Marketing** — Digital & Traditional Marketing
- **Educational Consultant** — Student Placement & Visa Services
- **Zunnoon Travel & Tours** — Hajj, Umrah & Corporate Travel
- **Qudrah Travel & Tours** — Travel
- **NaxGanic Foods** — Organic Food Products
- **NaxGanic Cosmetics** — Natural Beauty & Wellness

---

## Browser Support

| Browser | Support |
|---|---|
| Chrome 90+ | ✅ Full |
| Firefox 88+ | ✅ Full |
| Safari 14+ | ✅ Full |
| Edge 90+ | ✅ Full |
| IE 11 | ❌ Not supported |

---

## License

This project is proprietary. All rights reserved by **Zunnoon Group**.  
Unauthorised reproduction or distribution is prohibited.

---

## Contact

**Zunnoon Group**  
123, Business Bay, Gulberg, Lahore, Pakistan  
📞 +92 300 1234567  
📧 info@zunnoongroup.com  
🌐 [zunnoongroup.com](https://zunnoongroup.com)
