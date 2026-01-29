# Changelog

All notable changes to StreetChef marketing site.

## [1.2.0] - 2025-01-29

### Fixed
- **Carousel jumping bug** — Replaced dynamic `getBoundingClientRect()` calculation with stable CSS variable-based positioning
- Added `will-change: transform` for GPU acceleration
- Added `requestAnimationFrame` for proper initialization timing

### Changed
- Carousel now uses fixed `--phone-width` (260px) and `--phone-gap` (40px) variables
- Simplified transform calculation: `centerOffset - (currentSlide * slideWidth)`

---

## [1.1.0] - 2025-01-29

### Added
- **New carousel design** with navigation arrows and dot indicators
- Click on any screenshot to navigate to it
- Keyboard navigation (← → arrows)
- Touch/swipe support for mobile
- Active slide scaling effect (center = 100%, adjacent = 88%, others = 80%)
- Labels visible only for active screenshot

### Changed
- Replaced horizontal scroll with proper carousel
- Updated font from Inter to Plus Jakarta Sans
- Improved visual hierarchy with opacity transitions
- Footer year fixed from 2026 to 2025

### Removed
- Old horizontal scroll behavior
- Hidden scrollbar CSS hacks

---

## [1.0.0] - 2025-01-28

### Added
- Initial marketing page with iPhone mockups
- 5 app screenshots in horizontal scroll
- Multilingual support (EN, RU, ES, DE, FR)
- Language switcher with localStorage persistence
- Hero section with animated logo
- Feature cards grid (6 features)
- Statistics section (100% Offline, 5 Languages, ∞ Events)
- CTA sections with TestFlight link
- Privacy and Support page links
- Responsive design for mobile

### Technical
- Pure HTML/CSS/JS (no frameworks)
- Google Fonts: Inter
- CSS custom properties for theming
- Dark theme with orange accent (#ff6b35)

---

## Links

- **Repository:** https://github.com/smiras74/streetchef-legal
- **Live site:** https://smiras74.github.io/streetchef-legal/marketing.html
- **TestFlight:** https://testflight.apple.com/join/vvVMT29B
