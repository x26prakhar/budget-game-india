<div align="center">

# If You Were Finance Minister

**A budget simulation for India's Union Budget 2026-27.**
Allocate ₹50 lakh crore across sectors — and see where your money goes.

[![Live](https://img.shields.io/badge/live-Netlify-22c55e?style=flat-square)](https://india-budget-game-2026.netlify.app)
[![Stack](https://img.shields.io/badge/stack-HTML%2FJS%2FFirebase-f59e0b?style=flat-square)]()
[![License](https://img.shields.io/badge/license-MIT-0078d4?style=flat-square)]()

[What is it](#what-is-it) · [How to Play](#how-to-play) · [Tech Stack](#tech-stack) · [Run Locally](#run-locally)

</div>

---

## What is it?

A browser-based interactive game where you play India's Finance Minister. You're given a fixed budget and asked to allocate it across key government sectors — Education, Health, Defence, Infrastructure, Agriculture, and more.

Your choices are stored anonymously and compared against how real users allocate the budget. A shareable results card is generated at the end.

---

## How to Play

1. **Enter your income** — see your estimated tax contribution
2. **Allocate the budget** — drag or input amounts across sectors
3. **See your choices** — compare with the actual Union Budget 2026-27
4. **Download & share** — get a results card image for social media

---

## Tech Stack

| Component | Technology |
|-----------|------------|
| UI | Vanilla HTML, CSS, JavaScript |
| Data persistence | Firebase Firestore |
| Share card | html2canvas |
| Fonts | Google Fonts (Inter) |
| Deployment | Netlify |

---

## File Structure

```
budget-game-india/
└── index.html    # Entire app — UI, logic, Firebase config, styles
```

---

## Run Locally

```bash
git clone https://github.com/x26prakhar/budget-game-india.git
cd budget-game-india
# Open index.html in your browser
# Note: Firebase features require a live origin or localhost server
npx serve .
```

---

## Data & Privacy

- No user accounts or personal data collected
- Budget allocations stored anonymously in Firebase Firestore
- No tracking or analytics beyond aggregate response counts

---

<div align="center">
  Built by <a href="https://www.linkedin.com/in/prakharsingh96/">Prakhar Singh</a>
  &nbsp;·&nbsp;
  <a href="https://www.instagram.com/prakhar.vc/">@prakhar.vc</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/x26prakhar/budget-game-india">GitHub</a>
</div>
