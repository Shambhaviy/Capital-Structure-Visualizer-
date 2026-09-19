# Capital Structure Visualizer

An interactive tool for modeling how a company is financed, valued, and stress-tested — built to demonstrate applied finance fundamentals in a working, shareable format rather than a static Excel file.

**[Live Demo →](https://shambhaviy.github.io/Capital-Structure-Visualizer-/)**

## What it does

The tool models a company's entire capital structure — senior debt, subordinated debt, convertible notes, preferred stock, and common equity — and shows how that structure drives valuation, risk, and cost of capital. Every module shares one underlying data model, so changing an input in one tab updates everything downstream.

- **Capital Stack** — visualizes every financing layer in order of seniority, with Enterprise Value calculated live (EV = Debt + Preferred + Equity − Cash)
- **Recovery Waterfall** — models exactly who gets paid, and how much, at any exit or liquidation value, following strict payout priority
- **WACC Calculator** — computes Weighted Average Cost of Capital using the live capital structure weights, with automatic tax-adjustment on the cost of debt
- **Credit Metrics** — calculates Debt/EBITDA, Net Debt/EBITDA, and Interest Coverage, flagging any breach of user-set covenant thresholds
- **Pre/Post Deal Comparison** — save a "before" snapshot, then model a transaction and see the impact on EV, leverage, and cost of capital
- **Export Summary** — generates a downloadable one-page Markdown summary pulling live figures from every module

## Why I built this

Most student finance projects are either a static model or a market-research writeup. This is meant to mirror how an analyst actually thinks — where one change (adding a debt tranche, adjusting an exit assumption) immediately shows its effect across valuation, downside risk, and cost of capital, all in one coherent tool.

## Tech

Single-file, self-contained HTML/CSS/JavaScript — no framework, no backend, no external data dependency. Fully client-side, so it's easy to host, share, and demo from a link.

## Finance concepts covered

Capital structure & seniority · Enterprise Value · bankruptcy/liquidation waterfalls · WACC & the interest tax shield · leverage and coverage covenants · transaction impact analysis

---
Built by Shambhavi Yadav — https://www.linkedin.com/in/shambhavi-y/
