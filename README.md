[README.md](https://github.com/user-attachments/files/27785530/README.md)
# ActuaWiki

A free, single-page actuarial study reference for university students. Probability, distributions, algebra, integration, and statistics — all in one zero-install HTML file with interactive plots, full LaTeX formulas, and worked examples.

**Live demo:** _(add your GitHub Pages link here)_

---

## What's inside

ActuaWiki covers the core math you need for actuarial coursework and early exams:

- **Probability & Random Variables** — conditional probability, Bayes' theorem, expectations, CDFs, joint distributions, survival functions, order statistics, MGFs and PGFs
- **Distributions for Actuaries** — discrete, continuous, frequency and severity distributions with interactive Chart.js plots
- **Algebraic & Differentiation Basics** — series, summation identities, differentiation rules, logs, exponentials
- **Integration Basics** — definite and improper integrals, integration by parts, Fubini swaps, actuarial applications
- **Statistics Basics** — Z, t, χ², and F tests; estimation (MoM, MLE); ANOVA and regression F-tests
- **RStudio Basics** — _coming soon_

## Features

- Single self-contained `index.html` — no build step, no dependencies to install
- Light and dark themes with system preference detection
- Interactive distribution plots powered by Chart.js
- LaTeX math rendering (MathJax)
- Glassmorphism UI with smooth transitions
- Fully responsive — works on phones, tablets, and desktops
- Accessibility-first: skip links, focus styles, reduced-motion support

## Getting started

Clone the repo and open the file in any modern browser:

```bash
git clone https://github.com/<your-username>/actuawiki.git
cd actuawiki
open index.html      # macOS
# or just double-click index.html
```

That's it — there is no build step.

## Deploy to GitHub Pages

1. Push the repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Source**, choose your `main` branch and the `/ (root)` folder.
4. Save — your site will be live at `https://<your-username>.github.io/actuawiki/` within a minute.

## Tech stack

- Plain HTML, CSS, and vanilla JavaScript
- [Chart.js](https://www.chartjs.org/) for interactive plots
- [MathJax](https://www.mathjax.org/) for LaTeX rendering
- Google Fonts (Inter, JetBrains Mono)

## Contributing

Found a typo, a wrong formula, or want to add a topic? Open an issue or send a PR. Suggestions for new sections (especially the upcoming R content) are welcome.

## License

MIT — free to use, fork, and adapt for your own study notes or course materials.
