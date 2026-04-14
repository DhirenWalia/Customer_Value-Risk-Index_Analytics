# EPSILON 7.0 — DEL-RPI Customer Analytics Framework

---

**Competition:** EPSILON 7.0 Analytics Case Competition  
**Presented by:** Dhiren Walia (Dw7)  
**Institution:** National Forensic Sciences University, New Delhi  
**Course:** BBA-MBA Integrated, 1st Year  

---

## About

This project was created for an analytics case competition.
The objective was to evaluate customer value beyond revenue by considering growth, risk, and investment potential.
I developed a framework to rank customers using multiple factors and presented the results through a Power BI dashboard.

## Tools Used

- Power BI
- Microsoft Excel
- PowerPoint
- Data Analysis
- Business Strategy

## What I Built

Most companies rank customers by revenue, frequency, or LTV.
I thought that's incomplete — it ignores risk, volatility, and 
how much value you can actually unlock with investment.

So I built **DEL-RPI** — a custom customer scoring index inspired 
by energy dynamics and portfolio risk logic.

## The Framework — DEL-RPI

**Dynamic Energy & Leverage Risk-Adjusted Performance Index**

I modelled each customer as a portfolio of four forces:

| Component | What it measures |
|-----------|-----------------|
| **Stored Energy (SE)** | Historical revenue strength — stability |
| **Kinetic Energy (KE)** | Growth momentum — purchase frequency, recency |
| **Friction (F)** | Value erosion — return rate, refund ratio, volatility |
| **Strategic Leverage (SL)** | How much ₹1 of investment can unlock |

## The Math:
| Function | Formula |
|----------|---------|
| Base Energy (BE)         | SE + KE |
| Risk-Adjusted Energy (RAE) | BE × (1 − F) |
| DEL-RPI                  | (RAE × 0.6) + (SL × 0.4) |

The 60-40 split: present stability matters more than hypothetical 
upside — but leverage drives future transformation.

---

## Customer Segments (from DEL-RPI scores)

| Segment | Profile | Strategy |
|---------|---------|----------|
| 🏔️ Anchored Titans | High stability, strong stored energy | Protect & retain |
| 🚀 Emerging Rockets | High growth + high leverage | Aggressively scale |
| ⚡ Volatile Sprinters | High growth but high friction | Fix before investing |
| 🌱 Dormant Assets | Low energy, low leverage | Minimal capital |

---

## Capital Allocation (₹1 Crore Strategy)

| Segment | Allocation | Reason |
|---------|-----------|--------|
| Emerging Rockets | ~40% | Highest DEL-RPI uplift potential |
| Anchored Titans | ~30% | Protect the stable revenue base |
| Volatile Sprinters | ~20% | Reduce friction → convert unstable revenue |
| Dormant Assets | ~10% | Automation only |

---

## Power BI Dashboard (3 Pages)

**Page 1 — Strategic Customer Portfolio Overview**  
Customer count, total DEL-RPI score, return rate, subscription 
penetration, stability index, growth power, segment distribution

**Page 2 — Strategic Performance, Risk & Investment Intelligence**  
Risk scoring by segment, growth power vs engagement behavior, 
app usage vs growth, financial stress vs cart abandonment

**Page 3 — Strategic Action Framework & Capital Allocation Roadmap**  
DEL-RPI vs risk by segment, risk category breakdown, 
strategic action recommendations per segment

---

## Files

| File | Description |
|------|-------------|
| `Dw7_EPSILON7_0.pbix` | Full Power BI dashboard |
| `Dw7_EPSILON7_0.xlsx` | Dataset (4 sheets — revenue, demographics, behavior, psychology) |
| `Dw7_EPSILON7_0.pptx` | Competition presentation (7 slides) |

## Dataset Sheets

- **Revenue Engine Metrics** — spend, return rate, conversion, loyalty
- **Customer Identity & Socio-Demographics** — age, income, country, occupation
- **Digital Engagement & Behavioral** — session time, app usage, impulse buying
- **Financial Psychology & Lifestyle** — budgeting style, financial stress

---

## What I Learned

- How to build a custom scoring framework from scratch — not just use existing ones
- Applying physics and portfolio theory concepts to a business problem
- Building multi-page Power BI dashboards with DAX measures
- Thinking about capital allocation as a strategy, not just a number
- Presenting complex ideas in a way that's clear and structured

## Reflections

- This was built for a competition — the framework is theoretical 
  and would need real business validation before deployment
- The 60-40 weight in DEL-RPI is an assumption — 
  real-world testing could refine it

## Final Recommendations
- Invest more in high-growth customer segments
- Reduce friction in risky segments
- Focus on stable and scalable customers
- Improve portfolio quality, not just revenue

---

## How to Open

- **Dashboard:** Open `.pbix` in Power BI Desktop (free from Microsoft)
- **Presentation:** Open `.pptx` in PowerPoint or Google Slides
- **Data:** Open `.xlsx` in Excel
