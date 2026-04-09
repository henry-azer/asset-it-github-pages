<p align="center">
  <img src="assets/logo-dark.png" alt="Asset It" width="80" height="80" style="border-radius: 16px;">
</p>

<h1 align="center">Asset It</h1>

<p align="center">
  <strong>Private Wealth & Budget Tracker</strong><br>
  Marketing site, privacy policy, and support page
</p>

<p align="center">
  <a href="https://asset-it-app.divinentra.com/">Website</a> &bull;
  <a href="https://asset-it-app.divinentra.com/privacy-policy.html">Privacy Policy</a> &bull;
  <a href="https://asset-it-app.divinentra.com/support.html">Support</a>
</p>

---

## About

This repository hosts the public-facing website for **Asset It** — a privacy-first mobile app for tracking wealth, budgets, and investments across currencies, gold, stocks, bank accounts, and more.

The site serves three purposes required for App Store and Google Play submissions:

| Page | Purpose |
|------|---------|
| [Landing Page](https://asset-it-app.divinentra.com/) | Marketing page with features, screenshots, and download links |
| [Privacy Policy](https://asset-it-app.divinentra.com/privacy-policy.html) | Full privacy policy covering data handling, third-party services, and user rights |
| [Support](https://asset-it-app.divinentra.com/support.html) | Contact form for help requests, bug reports, and app feedback |

## Features

- **App branding** — Matches Asset It's indigo/purple design system exactly
- **Dark mode** — System-preference detection with manual toggle, persisted in localStorage
- **Responsive** — Mobile-first layout adapting to phone, tablet, and desktop
- **Screenshot carousel** — Auto-advancing, swipeable phone mockups showing the app in action
- **Unified support form** — Three form types (Help, Bug Report, Feedback) routing to Google Forms
- **Star rating** — Interactive 5-star selector for app feedback
- **No dependencies** — Pure HTML, CSS, and vanilla JavaScript
- **Fast** — No build step, no frameworks, instant page loads

## Structure

```
.
├── index.html              # Marketing landing page
├── privacy-policy.html     # Privacy policy (17 sections)
├── support.html            # Support form with Google Forms integration
├── css/
│   └── styles.css          # Shared design system (tokens, components, responsive)
├── js/
│   └── main.js             # Dark mode, carousel, form router, animations
└── assets/
    ├── logo-light.png      # App icon (light variant)
    ├── logo-dark.png       # App icon (dark variant)
    └── screenshots/
        ├── dark/           # App screenshots (dark theme)
        └── light/          # App screenshots (light theme)
```

## Deployment

Hosted on [GitHub Pages](https://pages.github.com/) from the `main` branch.

To deploy your own version:

1. Fork this repository
2. Go to Settings → Pages
3. Set Source to `main` branch, root `/`
4. Your site will be live at `https://<username>.github.io/asset-it-github-pages/`

## App Store URLs

Use these in App Store Connect / Google Play Console:

| Field | URL |
|-------|-----|
| Marketing URL | `https://asset-it-app.divinentra.com/` |
| Privacy Policy URL | `https://asset-it-app.divinentra.com/privacy-policy.html` |
| Support URL | `https://asset-it-app.divinentra.com/support.html` |

## About Asset It

Asset It is a mobile app (iOS & Android) for tracking personal wealth and budgets with a privacy-first approach:

- **7 asset types** — Currencies, gold, stocks, bank accounts, credit cards, cash, loans
- **Live market data** — Real-time exchange rates, gold prices, and stock tracking
- **AES-256 encryption** — All data stored locally with military-grade encryption
- **Offline-first** — Works without internet for all core features
- **iCloud Sync** — Optional encrypted backup on iOS
- **Bilingual** — English and Arabic with full RTL support

## Author

**Henry Azer**

- [LinkedIn](https://www.linkedin.com/in/henry-azer)
- [GitHub](https://github.com/henry-azer)
- [Email](mailto:henry.azer@outlook.com)

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
