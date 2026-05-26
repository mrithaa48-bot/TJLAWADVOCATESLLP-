# TJ Law Advocates LLP — Website

Official website for **TJ Law Advocates LLP**, a leading Kenyan law firm based in Nairobi.

## Stack
Single-file HTML/CSS/JS — no build tools, no dependencies. Ready to deploy anywhere.

## Files
```
index.html     — Main website (all CSS + JS inline)
logo.jpeg      — Firm logo (place in same folder)
README.md      — This file
```

> **Important:** Place your `logo.jpeg` in the same directory as `index.html` before deploying. The site falls back to the "TJ" monogram if the image is missing.

## Features
- ✅ Light parchment/gold theme — professional and easy to read
- ✅ AI Legal Assistant (powered by Claude) — floating chat widget
- ✅ Mobile-first responsive design with 48px touch targets
- ✅ WhatsApp direct links throughout (floating button + CTA buttons)
- ✅ Click-to-call and email links in contact section
- ✅ Blog article filter + modal reader
- ✅ Contact form with mailto fallback
- ✅ Fade-in scroll animations
- ✅ Fixed navbar with mobile hamburger menu
- ✅ No external JS dependencies

## Deployment — HostPinnacle

1. Log in to HostPinnacle cPanel
2. Open **File Manager** → navigate to `public_html`
3. Upload `index.html` and `logo.jpeg`
4. Visit your domain — done ✅

## Email

Update the contact email in two places in `index.html` if needed:
- The `mailto:` links in the contact section
- The form submit handler (search `info@tjlawadvocates.co.ke`)

## AI Assistant

The AI assistant uses the Anthropic Claude API. The API key is handled by the claude.ai embed environment. If hosting standalone, you will need to add your own API key or proxy — see [Anthropic docs](https://docs.anthropic.com).

## Contact
- 📞 +254 714 222 142
- 📍 Suite 3.0, Plot 4, Muchai Drive, 408 Mbaruk Road, Off Ngong Road, Nairobi, Kenya
