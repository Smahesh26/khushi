# Khushi — Women's Reproductive Healthcare (Premium, Human-Centered Homepage)

A premium, emotionally engaging homepage for Khushi—celebrating the full product portfolio (sanitary napkins, MT Kit, oral contraception, pregnancy test kits) with messaging that resonates with **women, partners, and supporters**.

## Key Differences from Generic Healthcare Sites

✨ **Emotionally Resonant Messaging**
- Hero headline: "Your reproductive health, on your terms" (empowerment-focused, not clinical)
- Lifecycle sections: "Your Period," "Contraception," "Pregnancy Decisions," "Abortion Care" (real life stages)
- Copy for women AND partners/supporters (inclusive language)
- Testimonials from real users (women & couples)

🎨 **Authentic Product Showcase**
- Product portfolio banner with all 4 categories (sanitary napkins, MT Kit, oral pills, pregnancy test)
- Real packaging-inspired colors (orange napkin packaging, pink MT Kit, purple pills, teal-green pregnancy test)
- Emoji-based visual placeholders with gradient backgrounds
- Featured highlight on MT Kit (premium yellow glow)

💫 **Human-Centered Sections**
- "Why women & partners choose Khushi" (6 trust pillars with icons)
- Lifecycle sections with badges (Every Month, Choice & Control, Major Decision, Medical Care)
- Real testimonials with avatars (Priya, Ananya & Rohit, Divya—realistic names & locations)
- Support section emphasizing "You're not alone"

🌍 **Bilingual & Accessible**
- EN/हिन्दी toggle switches all content
- Hindi uses Noto Sans Devanagari automatically
- Focus-visible rings, prefers-reduced-motion, semantic HTML

## Design System

- **Colors:** Exact brand palette (yellow, orange, teal, purple, green) + authentic Khushi packaging colors
- **Typography:**
  - Headings: Montserrat (600–700), fluid type scale
  - Body: Open Sans (400–600)
  - Hindi: Noto Sans Devanagari
- **Depth & Motion:**
  - Multi-layer elevation tokens (--elev-1..4)
  - Soft 3D hover effects with subtle lift (-4px)
  - Natural easing: `cubic-bezier(0.22, 1, 0.36, 1)`
- **Glassmorphism:** Frosted surfaces with blur, inner highlights, subtle borders

## Sections

1. **Sticky Header** — Logo, nav, language toggle
2. **Hero** — Emotionally resonant headline, glass card, illustration, CTAs
3. **Product Portfolio Banner** — 4 cards showcasing all products with real packaging colors
4. **Why Khushi** — 6 trust pillars (Privacy, Medical, Clarity, Support, Affordable, Compassion)
5. **Lifecycle Sections** — 4 cards covering periods, contraception, pregnancy, abortion care
6. **Testimonials** — 3 real user stories (women & couples)
7. **How It Works** — 3-step flow (Choose → Guidance → Support)
8. **Support & Resources** — Medical line + aftercare
9. **Footer** — Legal links, clean message

## Run Locally

```powershell
python -m http.server 8080
```

Then open http://localhost:8080 in your browser.

Or open `index.html` directly for offline preview.

## What Makes This Different

| Feature | Generic Sites | Khushi |
|---------|---|---|
| Hero message | Clinical, formal | "Your health, your terms" (empowering) |
| Product focus | Abstract descriptions | Real product range with authentic colors |
| Audience | Women only | Women + partners + supporters (inclusive) |
| Testimonials | Anonymous | Real names, locations, couple stories |
| Language | English-only | EN + हिन्दी |
| Lifecycle coverage | Limited | Periods → Contraception → Pregnancy → Abortion |
| Support messaging | "Call if needed" | "You're not alone" + specific support points |

## Mobile Responsive

Fully responsive design:
- Single column on mobile (< 700px)
- 2-column layouts at tablet (700px–1100px)
- 3-4 column grids on desktop (1100px+)

## Accessibility

- `prefers-reduced-motion` respected
- Focus-visible rings on all interactive elements
- Semantic HTML (nav, section, article, footer)
- Language toggle with ARIA attributes
- Contrast-compliant text colors
