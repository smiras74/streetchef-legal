# StreetChef Marketing Site

Marketing and legal pages for StreetChef iOS app.

🌐 **Live site:** https://smiras74.github.io/streetchef-legal/marketing.html

📱 **TestFlight:** https://testflight.apple.com/join/vvVMT29B

---

## 📁 Structure

```
├── marketing.html    # Main landing page with carousel
├── index.html        # Entry point
├── privacy.html      # Privacy policy (5 languages)
├── support.html      # Support page
├── thanks.html       # Thank you page
├── icon.png          # App icon (120x120)
└── screenshots/      # App screenshots for carousel
    ├── 01.png        # Dashboard
    ├── 02.png        # Orders
    ├── 05.png        # Gas Tracking
    ├── 07.png        # Event Details
    └── 10.png        # Quotes/Invoice
```

---

## 🌍 Languages

Supported: **EN** | **RU** | **ES** | **DE** | **FR**

Language is auto-detected from browser, saved to localStorage.

---

## 🎨 Design System

### Colors
| Variable | Value | Usage |
|----------|-------|-------|
| `--accent` | `#ff6b35` | Buttons, highlights |
| `--accent-light` | `#ff8f5a` | Gradients |
| `--bg-dark` | `#0a0c10` | Background |
| `--text-primary` | `#fff` | Headings |
| `--text-secondary` | `#8b949e` | Body text |

### Typography
- **Font:** Plus Jakarta Sans (Google Fonts)
- **Weights:** 400, 500, 600, 700, 800

---

## 🎠 Carousel

The screenshot carousel uses CSS transforms for smooth animations:
- Active slide: `scale(1)`, full opacity
- Adjacent slides: `scale(0.88)`, 60% opacity  
- Other slides: `scale(0.8)`, 30% opacity

### Navigation
- ← → buttons
- Dot indicators (clickable)
- Click on any screenshot
- Keyboard arrows
- Touch swipe on mobile

---

## 🛠️ Development

### Quick edit
```bash
git clone https://github.com/smiras74/streetchef-legal.git
# make changes
git add . && git commit -m "description" && git push
```

### Deploy
Automatic via GitHub Pages. Changes appear in ~1-2 minutes after push.

---

## 📋 See Also

- [CHANGELOG.md](CHANGELOG.md) — Version history
