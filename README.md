# From Provider Abroad to Caregiver at Home: Beth's Story Beyond Gender Norms

A long-form editorial feature story examining how one Filipino mother navigated the dual roles of overseas worker and primary caregiver, challenging conventional gender norms through lived experience.

**Course:** MO-SS086 Gender and Society
**Author:** James Ongo

---

## Live Site

[View on GitHub Pages](https://baelfyre.github.io/genderAndSociety/index-enhanced.html)

---

## Project Structure

```
genderAndSociety/
├── index.html                # Original Vite + React production build
├── index-enhanced.html       # Standalone premium editorial layout (recommended)
├── assets/
│   ├── *.png                 # Photo assets (7 images)
│   ├── index-*.css           # Compiled Tailwind stylesheet
│   └── index-*.js            # Compiled React bundle
├── Magazine Editorial Layout.pdf
├── Magazine Editorial Layout.zip
├── .github/
│   └── workflows/
│       └── deploy.yml        # GitHub Pages deployment workflow
└── README.md
```

---

## Pages

| File | Description |
|---|---|
| `index-enhanced.html` | Standalone magazine editorial layout - no build step required |
| `index.html` | Original React/Vite/Tailwind production bundle |

---

## Design Features (index-enhanced.html)

- Magazine-style long-form editorial layout
- Warm cream palette with full dark mode (persisted via `localStorage`)
- Scroll-driven reading progress bar
- Drop cap opening paragraph
- Pull quotes, callout boxes, and literary blockquotes
- Responsive photo grid (7 images with captions)
- Back-to-top button
- Google Fonts: Lora (serif) + Inter (sans)
- Zero dependencies, zero build step

---

## Content Note

All article text is preserved verbatim from the original source. No content was added, removed, rewritten, or summarized. Design-only enhancements were applied.

---

## Deployment

This site is deployed automatically via GitHub Actions on every push to `master`. See [`.github/workflows/deploy.yml`](.github/workflows/deploy.yml).

To enable GitHub Pages manually:
1. Go to **Settings > Pages**
2. Set source to **GitHub Actions**
3. Push to `master` to trigger deployment

---

## References

- Republic Act No. 11861 (Expanded Solo Parents Welfare Act). Philippine Commission on Women.
  https://pcw.gov.ph/republic-act-no-11861-expanded-solo-parents-welfare-act/

- Philippine Statistics Authority poverty threshold benchmark (2023).
  https://business.inquirer.net/475138/psa-p13873-month-budget-for-basic-needs-enough-for-family
