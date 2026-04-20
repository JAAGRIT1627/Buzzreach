# BuzzReach — WhatsApp Marketing that Actually Works

> A full Neo-brutalist SaaS landing website built as a competitor study to AiSensy.  
> Researched the WhatsApp Business API space, studied AiSensy's product structure, and built an original competing platform from scratch.

---

## 🚀 Live Demo

🔗 **[buzzreach.vercel.app](https://buzzreach.vercel.app)** ← ✏️ Replace with your actual live URL

---

## 📁 Project Structure

```
buzzreach/
├── index.html              ← Main landing page (all sections)
├── pages/
│   ├── pricing.html        ← Pricing tiers + FAQ
│   ├── about.html          ← Founder story + mission
│   ├── contact.html        ← Contact form + WhatsApp support
│   ├── signup.html         ← Sign-up flow
│   └── login.html          ← Login page
├── css/
│   └── style.css           ← Extracted styles (CSS variables, animations)
├── js/
│   └── main.js             ← FAQ accordion, industry tabs, scroll effects
├── assets/
│   └── founder.jpg         ← ✏️ Replace with your actual photo
├── .gitignore
└── README.md
```

---

## ✨ What's Built

### Design
- **Neo-brutalist aesthetic** — thick black borders, bold offset shadows, raw typography
- **Syne + DM Sans** font pairing — display font that stands out from generic Inter/Roboto choices
- **Green / Yellow / Black** palette — deliberately different from AiSensy's green-heavy corporate look
- **Animated WhatsApp chat mockup** in the hero with floating metric cards
- **Fully responsive** — mobile-first layout across all breakpoints

### Sections (in order)
1. **Announcement bar** — live offer / news strip
2. **Sticky navbar** — scroll-aware active state highlighting
3. **Hero** — punchy headline, founder voice sub-copy, animated WA mockup, real stats
4. **Logo ticker** — infinite CSS scroll of client brands
5. **How It Works** — 3-step visual flow (Connect → Build → Grow)
6. **Broadcast section** — dark background, live campaign analytics UI
7. **Stats bar** — WhatsApp open rate vs email/SMS
8. **Why WhatsApp Wins** — Email vs SMS vs WhatsApp comparison cards
9. **Features grid** — 6 feature cards with accent color top borders
10. **Perks ticker** — yellow marquee of free inclusions
11. **Use Cases** — 6 real before/after business scenarios
12. **Competitor table** — BuzzReach vs AiSensy vs Interakt, row by row
13. **Pricing** — 3-tier pricing (Free / Growth / Enterprise)
14. **Industry tabs** — 6 industries with dedicated use case content
15. **Integrations grid** — 12 integration cards
16. **Setup section** — 4-step onboarding with live progress UI
17. **Founder section** — personal story, photo, social links
18. **Testimonials** — 3-card layout with dark middle card
19. **FAQ accordion** — 7 questions, vanilla JS open/close
20. **CTA section** — final conversion push
21. **Footer** — 4-column with social links + legal pages

### Technical
- **Zero dependencies** — pure HTML, CSS, vanilla JavaScript
- **CSS custom properties** throughout for consistent theming
- **IntersectionObserver** for scroll-triggered stat animations
- **CSS-only animations** — ticker, float, fade-up, pulse
- **Semantic HTML** — proper section/nav/footer structure

---

## 🛠 How to Run Locally

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/buzzreach.git
cd buzzreach

# Option 1: Open directly in browser
open index.html

# Option 2: Local server (recommended — avoids path issues)
npx serve .
# or
python3 -m http.server 3000
```

Then open `http://localhost:3000`

---

## 🌐 Deploy to GitHub Pages

```bash
# Step 1: Initialise git in your project folder
git init

# Step 2: Stage all files
git add .

# Step 3: First commit
git commit -m "Initial commit: BuzzReach SaaS landing page"

# Step 4: Rename branch to main
git branch -M main

# Step 5: Connect to your GitHub repo (create it on github.com first)
git remote add origin https://github.com/YOUR_USERNAME/buzzreach.git

# Step 6: Push
git push -u origin main
```

Then: GitHub repo → **Settings** → **Pages** → Source: `main` branch → **Save**

Your site goes live at:
```
https://YOUR_USERNAME.github.io/buzzreach/
```

---

## 🎨 Design Decisions

| Choice | Reason |
|--------|--------|
| Neo-brutalist style | Visually distinctive — stands out from every other SaaS landing page in this space |
| Syne display font | Bold, geometric, memorable — AiSensy uses a softer corporate feel |
| Green + Yellow + Black | High contrast, energetic — feels more like a product people want to use |
| Floating chat mockup | Shows the actual WhatsApp experience in context, not just a dashboard screenshot |
| Competitor table | Directly answers "why not just use AiSensy?" without the visitor having to ask |
| Founder section | Adds human credibility — most SaaS sites lack this and feel faceless |
| Use cases section | Turns abstract features into concrete before/after results |
| Why WhatsApp section | Educates visitors who are still on email/SMS — removes the biggest objection |

---

## 📊 How BuzzReach Differs from AiSensy

| Feature | BuzzReach | AiSensy |
|---------|-----------|---------|
| Free forever plan | ✅ Yes | ✅ Limited |
| In-chat UPI payments | ✅ Native | 🔄 Beta |
| Multi-agent live chat | ✅ Unlimited on paid | 💲 Paid add-on |
| Revenue per message tracking | ✅ Yes | ❌ No |
| Real human WhatsApp support | ✅ Always on | 🔄 Business hours |
| Zero setup fee | ✅ Always | ✅ Yes |
| Neo-brutalist design | ✅ Obviously | ❌ Corporate SaaS |

---

## 🔬 Research Process

This project was built using a structured competitor research process:

1. **Studied AiSensy** — mapped every section, feature, pricing tier, and CTA on their homepage
2. **Studied GrowBrow.ai** — a similar competitor study project for comparison
3. **Identified gaps** — sections AiSensy has, sections it's missing, and opportunities to go further
4. **Designed original** — same industry, completely different visual language and copy voice
5. **Added original sections** — Competitor Table, Why WhatsApp Wins, Use Cases, Founder Story — none of which AiSensy has

---

## 🏆 What Makes This Different from a Template

- Written in **founder voice** — not corporate marketing copy
- **No UI frameworks** — every component hand-built
- **Context-specific design** — every visual choice tied to the WhatsApp/India market
- **Competitor-aware** — the site actively answers "why not AiSensy?" inside the page itself
- **Honest placeholder markers** — clearly shows what needs real data vs what's done

---

## ✏️ Personalisation Checklist

Before publishing as your own product, replace:

- [ ] `BuzzReach` → your actual brand name (everywhere)
- [ ] Hero sub-copy → your real founding story
- [ ] Logo ticker → your actual clients (even 3-4 real ones)
- [ ] Founder section → your photo + name + city + social links
- [ ] Testimonials (×3) → real quotes from real users
- [ ] Hero stats → your real numbers
- [ ] Pricing → your actual plan prices
- [ ] Competitor table → verify all feature claims
- [ ] CTA links → your actual signup/demo URLs
- [ ] `index.html` title tag → your brand name

---

## 👤 Built By

**Jaagrit Sachdeva**  
[LinkedIn →](https://www.linkedin.com/in/jaagritsachdeva16)

---

## 📄 License

MIT — free to use, adapt, and build on.
