# 30 · 60 · 90 Online Course Launch Plan

A client-ready, browser-based launch plan for coaches and course creators. Built as a single HTML file — no dependencies, no frameworks, no build step required.

---

## What's Inside

A fully designed, interactive reference document covering every phase of a webinar-based online course launch, including:

- **Phase 1 (Days 1–30)** — Validation, product development, offer strategy, and full tech stack setup
- **Phase 2 (Days 31–60)** — Lead generation, pre-webinar email nurture sequence, SMS reminders, and audience warm-up
- **Phase 3 (Days 61–90)** — Live launch execution, post-webinar sales sequence, conversion optimization, and evergreen automation setup
- **Core Sales Funnel** — Architecture overview from landing page through course delivery
- **Webinar Script Structure** — Minute-by-minute breakdown of a 60-minute conversion webinar
- **Email Sequences** — Full copy direction for pre-webinar nurture and post-webinar sales sequences
- **SMS Copy** — Written-out message templates for every trigger point
- **Tech Stack Deep Dive** — Thinkific, ActiveCampaign, WebinarJam, and Twilio
- **Key Metrics + Benchmarks** — Targets and troubleshooting guidance
- **Strategic Principles** — The six things most course creators miss
- **Glossary** — 20 plain-English definitions of industry terms clients encounter throughout the plan

---

## Tech Stack Covered

| Platform | Role |
|---|---|
| Thinkific | Course hosting, checkout, and student onboarding |
| ActiveCampaign | Email automation, segmentation, and SMS triggers |
| WebinarJam | Live and evergreen webinar hosting |
| Twilio | SMS delivery via ActiveCampaign integration |

---

## How to Use

### View locally
Download `course_launch_plan.html` and open it in any browser. No server or installation needed.

### Host on GitHub Pages
1. Fork or clone this repository
2. Go to **Settings → Pages**
3. Under *Source*, select `main` branch and `/ (root)`
4. Click **Save** — your plan will be live at `https://yourusername.github.io/repository-name`

### Share with clients
Once GitHub Pages is enabled, copy the live URL and share it directly. To keep it private, consider password-protecting access via a tool like [Tiiny.host](https://tiiny.host) or sharing the raw file instead.

---

## Customization

All styling is contained within the `<style>` block at the top of `course_launch_plan.html`. Key variables to adjust:

```css
:root {
  --cream: #F7F3EE;       /* Background color */
  --ink: #1A1714;         /* Primary text + dark sections */
  --gold: #C9963A;        /* Accent color throughout */
  --phase1: #2D4A3E;      /* Days 1-30 color (green) */
  --phase2: #2A3A5C;      /* Days 31-60 color (blue) */
  --phase3: #5C2A2A;      /* Days 61-90 color (red) */
}
```

To update with your own branding, replace the `--gold` accent with your brand color and adjust the phase colors to match.

---

## File Structure

```
/
├── course_launch_plan.html   # The entire document — single self-contained file
└── README.md                 # This file
```

---

## Fonts Used

- [Playfair Display](https://fonts.google.com/specimen/Playfair+Display) — headings and display text
- [DM Sans](https://fonts.google.com/specimen/DM+Sans) — body copy
- [DM Mono](https://fonts.google.com/specimen/DM+Mono) — labels, tags, and metadata

Loaded via Google Fonts. An internet connection is required for fonts to render correctly.

---

## License

This document is intended for use by the purchasing client only. Not for redistribution or resale.
