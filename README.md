# AIMMS Consulting

Strategic intelligence advisory site for **AIMMS Consulting**, founded by
Sohail Bashir Butt — a pharmaceutical, nutraceutical, and diagnostics
advisory practice based in Lahore, Pakistan.

🔗 **Live site:** `https://<your-username>.github.io/<repo-name>/`
*(replace with your actual GitHub Pages URL once deployed)*

---

## About

AIMMS Consulting reads pharma, nutraceutical, and diagnostics markets the
way a hydrographer reads the ocean floor — depth first, certainty second,
opinion last. The site is built around the firm's proprietary **Strategic
Intelligence Engine**, now expanded to eight analytical lenses.

## The Eight-Lens Framework

Presented on the site as a single vertical "depth gauge," running from the
Mariana Trench floor up through the surface and on up Mount Everest to the
executive summit:

| Depth / Altitude | Zone | Lens |
|---|---|---|
| +8,849 m | Summit vantage | **Strategic Management Advisor** |
| 5,364 – 8,849 m | Base Camp → Summit | **Mount-Everest-Level Growth of Business Development** |
| 0 m | Sea level | **Semantic BI Analyst** |
| -300 m | Sunlit zone | **Epistemic Rigor Lens** (Statistical Validity Analyst) |
| -1,200 m | Twilight zone | **Strategic Brand Differentiation Specialist** |
| -2,000 m | Midnight zone | **Behavioral & Cognitive Bias Lens** |
| -4,000 m | Abyssal zone | **Pre-Mortem Foresighted Intelligence Analyst** |
| -10,935 m | Challenger Deep | **Mariana Trench Level Market Researcher** |

Every engagement is graded using a three-tier evidence scheme —
**Verified / Plausible-Unverified / Affect-Driven-Unfalsifiable** — before
any recommendation is made.

## Pages

| File | Description |
|---|---|
| `index.html` | Home — Hero, Framework (8 lenses), Services, Approach, Signal, Contact |
| `projects.html` | Selected engagement archetypes across pharma, nutraceuticals, and diagnostics |
| `case-studies.html` | Longer-form walkthroughs: Situation → Descent → Surfaced with |
| `blog.html` | The AIMMS Insight Series — links out to LinkedIn for full posts |
| `aimms-consulting-single-page.html` | Everything above combined into one scrolling page |

Only **one** of `index.html` or `aimms-consulting-single-page.html` should
be used as the live homepage at a time — see `site-builder/` below for how
to switch which one GitHub Pages serves.

## Design

- **Palette:** navy, amber, coral — matching the AIMMS brand
- **Type:** Fraunces (display) + IBM Plex Sans / IBM Plex Mono (body / data)
- **Signature element:** a scroll-tracking "depth gauge" down the left rail,
  reading out the current lens as you scroll
- Fully self-contained HTML — logo is embedded as base64, no external
  image files or build step required to view any page

## Updating the Site

All content (lenses, projects, case studies, blog posts, services,
contact info) is defined in one place:

```
site-builder/aimms_master_build.py
```

Edit the data at the top of that file, then regenerate every page at once:

```bash
cd site-builder
python3 aimms_master_build.py
```

This rebuilds `index.html`, `projects.html`, `case-studies.html`,
`blog.html`, and `aimms-consulting-single-page.html` from the same source,
so they never drift out of sync with each other.

## Deployment

Hosted via **GitHub Pages**, serving directly from the `main` branch root.
Any commit to `main` updates the live site within a minute or two.

## Contact

- **Email:** aimmsconsulting@gmail.com
- **Phone:** +92-300-498-4896
- **LinkedIn:** [linkedin.com/in/aimms-consulting-35895439](https://www.linkedin.com/in/aimms-consulting-35895439)
- **Location:** Lahore, Pakistan

---

*Let's Color The Daring Dreams Together.*
