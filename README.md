# 🏋️ IRONCLAD GYM — Forge Your Legend

> A fully-featured gym landing page template built with pure HTML, CSS & JavaScript. No frameworks, no dependencies (except Three.js for the 3D background).

![IRONCLAD Preview](https://img.shields.io/badge/Status-Live-ff4500?style=for-the-badge)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---

## 🔥 Live Demo

**[→ View Live Site](https://jatinjaangir007-cloud.github.io/void-website/)**

---

## ✨ Features

### 🎨 Frontend & UI
- **3D Particle Background** — Three.js powered animated particle field with floating wireframe rings and icosahedron
- **Custom Cursor** — Fire-colored dot with lagging ring trail
- **3D Rotating Cube** — CSS `preserve-3d` hero decoration
- **Flip Cards** — Trainer cards with 3D card flip on hover
- **Scroll Reveal Animations** — Elements fade up as you scroll
- **Animated Stats Counter** — Numbers count up when entering viewport
- **Infinite Marquee Bands** — Two scrolling text strips in opposite directions
- **Parallax Hero** — Hero content and decoration scroll at different speeds
- **Responsive Design** — Fully mobile-friendly layout

### 🔐 Authentication System
- **Sign Up** — Full registration with name, email, phone, password, and fitness goal
- **Login** — Validates against registered accounts stored in `localStorage`
- **Persistent Sessions** — Stay logged in across page refreshes
- **Live Nav Update** — Navbar shows user avatar + dropdown when authenticated
- **Form Validation** — Client-side checks for all fields, duplicate email detection

### 💳 Payment Integration (Demo)
- **3-Step Checkout Flow** — Plan summary → Card details → Confirmation
- **Card Formatting** — Auto-formats card number and expiry date as you type
- **Billing Options** — Toggle between monthly and annual billing (20% discount)
- **Promo Code Field** — Ready to hook into a real coupon system
- **Processing Animation** — Realistic loading state before success screen
- **Plan Activation** — Automatically updates user account after payment

### 👤 Member Dashboard
- **Overview Tab** — Classes booked, day streak, and Forge Points stats
- **Schedule Tab** — Upcoming class bookings for the week
- **Billing Tab** — Active plan, cost, next billing date, payment method
- **Profile Tab** — Editable name and fitness goal with live save

### 🛠️ Admin Panel
> Access via the hidden **"Staff Portal ⬡"** link in the footer

| Credentials | Value |
|-------------|-------|
| Username    | `admin` |
| Password    | `forge2026` |

**5 Dashboard Tabs:**

| Tab | Description |
|-----|-------------|
| **Overview** | KPI cards, revenue bar chart, recent signups |
| **Members** | Full member list — includes real registered users |
| **Bookings** | Class bookings with filter and confirm/cancel actions |
| **Revenue** | Payment history and per-plan revenue breakdown |
| **Coaches** | Coach roster with ratings and class counts |

---

## 📁 Project Structure

```
ironclad-gym/
│
├── index.html          # Single-file application — all HTML, CSS & JS
└── README.md           # This file
```

> Everything lives in one self-contained `index.html` — perfect for GitHub Pages deployment.

---

## 🚀 Getting Started

### Option 1 — Open directly
Just download `index.html` and open it in any modern browser. No build step, no server needed.

### Option 2 — GitHub Pages (recommended)
1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Your site will be live at `https://YOUR-USERNAME.github.io/REPO-NAME/`

### Option 3 — Local server
```bash
# Python
python -m http.server 8000

# Node
npx serve .
```

---

## 🏗️ Sections

| # | Section | Description |
|---|---------|-------------|
| 1 | **Hero** | Full-screen headline with 3D cube decoration |
| 2 | **Stats Bar** | Animated counters — members, coaches, classes, locations |
| 3 | **Services** | 6 program cards with hover animations |
| 4 | **Trainers** | 3 flip cards with coach bios and booking CTA |
| 5 | **Pricing** | 3-tier membership plans (Warrior / Champion / Legend) |
| 6 | **CTA** | Free week offer with sign-up prompt |
| 7 | **Footer** | Links, brand info, staff portal access |

---

## 🎭 Demo Accounts

You can create real accounts via the Sign Up flow, or use the admin panel to see pre-seeded data.

**Test payment card:**
```
Card Number:  4242 4242 4242 4242
Expiry:       Any future date
CVV:          Any 3 digits
ZIP:          Any 5 digits
```

---

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| HTML5 | Structure and semantic markup |
| CSS3 | Animations, 3D transforms, Grid, Flexbox |
| Vanilla JavaScript | Auth, payment flow, admin logic |
| [Three.js r128](https://threejs.org/) | 3D particle background |
| Google Fonts | Bebas Neue, Barlow Condensed, Barlow |
| localStorage | Client-side user persistence |

---

## 🎨 Color Palette

| Name | Hex | Usage |
|------|-----|-------|
| Fire | `#ff4500` | Primary accent, buttons, highlights |
| Ember | `#ff8c00` | Hover states, gradients |
| Chrome | `#e0e0e0` | Primary text |
| Steel | `#b0bec5` | Secondary text |
| Void | `#050505` | Page background |
| Dark | `#0d0d0d` | Card backgrounds |

---

## 📱 Browser Support

| Browser | Support |
|---------|---------|
| Chrome 90+ | ✅ Full |
| Firefox 88+ | ✅ Full |
| Safari 14+ | ✅ Full |
| Edge 90+ | ✅ Full |
| Mobile (iOS/Android) | ✅ Responsive |

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🙌 Credits

Built with 💪 by **jatinjaangir007-cloud**

> *"Where iron meets willpower."*
