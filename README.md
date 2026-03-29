# Digital Research Ecosystem — Prof. Mahfoud Amara

> *Mapping sport, power, identity, and geopolitics across the MENA region through open, accessible, visual scholarship.*

**Associate Professor of Sport Social Sciences and Management**  
College of Sport Sciences · Qatar University  
ORCID: [0000-0002-1418-6710](https://orcid.org/0000-0002-1418-6710)

---

## Table of Contents

1. [Project Overview](#1-project-overview)
2. [Ecosystem Architecture](#2-ecosystem-architecture)
3. [Platform Directory](#3-platform-directory)
4. [Design Philosophy](#4-design-philosophy)
5. [Technical Structure](#5-technical-structure)
6. [Research Themes](#6-research-themes)
7. [Deployment Guide](#7-deployment-guide)
8. [Adding or Updating Publications](#8-adding-or-updating-publications)
9. [Accessibility](#9-accessibility)
10. [Academic Context](#10-academic-context)
11. [Roadmap](#11-roadmap)
12. [Citation](#12-citation)
13. [License](#13-license)

---

## 1. Project Overview

The **Digital Research Ecosystem** is a suite of interconnected, open-access, interactive web platforms that map over twenty years of peer-reviewed scholarship on sport and society across the MENA region. Built entirely with static HTML, CSS, and JavaScript — requiring no server infrastructure, no databases, and no frameworks — it is deployed freely via **GitHub Pages** and accessible to any researcher, student, journalist, or policy professional with an internet connection.

The project is guided by a core commitment: that rigorous academic knowledge should not be locked behind institutional paywalls or buried in conventional repository formats. Each platform transforms a body of publications into a visually engaging, navigable, and citable resource that bridges academic scholarship and public engagement.

The ecosystem currently comprises **six files**:

| File | Role |
|---|---|
| `index.html` | Central hub — the ecosystem landing page |
| `qatar-corniche.html` | Sport, Policy & Society in Qatar |
| `algerian-studies.html` | Sport & Algerian Studies |
| `arab-world.html` | Arab World Publications |
| `islam-muslim-communities.html` | Sport in Islam & Muslim Communities |
| `peninsula-archive.html` | The Peninsula Media Archive |

---

## 2. Ecosystem Architecture

```
mahfoudm33.github.io/
│
├── index.html                          ← Central Hub (this repository)
│
├── Sport-Policy-Society-Qatar/
│   └── index.html                      ← The Corniche Walk
│
├── Sport-and-Algerian-Studies/
│   └── index.html                      ← Stadium Interactive
│
├── Dr-Mahfoud-Amara-Publications-Arab-World/
│   └── index.html                      ← Arab World Publications
│
├── Sport-in-Islam-and-Muslim-Communities-Project/
│   └── index.html                      ← Islam & Muslim Communities
│
└── Dr-Mahfoud-Amara-in-the-Peninsula-/
    └── index.html                      ← The Peninsula Archive
```

Each platform is a **standalone GitHub repository** with its own `index.html`, deployed independently via GitHub Pages. The central hub (`index.html` at the root) links to all five and provides the scholarly and navigational context that makes them legible as a unified body of work rather than isolated pages.

---

## 3. Platform Directory

### 3.1 Central Hub — `index.html`
**URL:** `https://mahfoudm33.github.io/`

The atrium of the ecosystem. Introduces the scholarly identity, positions the five research areas within a coherent intellectual framework, routes visitors to the appropriate platform, and presents key metrics (publications, years, languages, research areas). Features a rotating Islamic star polygon, scroll-triggered count-up statistics, and a dark editorial aesthetic.

**Sections:**
- Hero with animated entrance and Islamic geometric motif
- Scholarly Identity — positioning statement, institutional affiliations, service roles
- Five Platform Cards — each with regional colour identity and descriptive text
- Five Core Research Themes — numbered, structured
- Statistics — count-up animation on scroll
- Footer with full platform directory

---

### 3.2 The Corniche Walk — Sport, Policy & Society in Qatar
**Repository:** `Sport-Policy-Society-Qatar`  
**URL:** `https://mahfoudm33.github.io/Sport-Policy-Society-Qatar/`  
**Coverage:** 9 publications · 2005–2024  
**Metaphor:** Publications are placed as markers along the Doha Corniche waterfront

**Visual features:**
- Illustrated Doha skyline with animated sea and waves
- Maroon-and-gold colour palette (Qatari national colours)
- Animated location markers (year + type) along the promenade
- Five thematic filter pills: Sport Policy & Governance, Mega-events & FIFA World Cup, Physical Activity & Urban Space, Identity & Nation-building, Media & Discourse
- Side panel with full abstract, theoretical contribution, and DOI link
- CSV export of full bibliography

**Publications covered (2005–2024):**
- Amara (2005) — Asian Games, *Sport in Society*
- Amara & Theodoraki (2010) — Transnational networks, *IJSP*
- Amara (2018) — Physical activity, *Routledge Handbook*
- Amara (2021) — Place and space, Springer
- McManus & Amara (2021) — Sport strategy from above and below, Springer
- Amara & Ishac (2021) — Sport and development, Routledge
- Amara & Bouandel (2022) — Culture and the World Cup, Routledge
- Kozhanov, Amara & Zweiri, eds. (2024) — *The 2022 FIFA World Cup in Qatar*, Routledge
- Amara & Bouandel (2024) — Why Qatar matters, Edward Elgar

---

### 3.3 Sport & Algerian Studies
**Repository:** `Sport-and-Algerian-Studies`  
**URL:** `https://mahfoudm33.github.io/Sport-and-Algerian-Studies/`  
**Metaphor:** Publications accessed through an interactive stadium seating plan

**Visual features:**
- Green-and-white Algerian national colour palette
- Accessible stadium metaphor with sections mapped to thematic clusters
- Full accessibility suite: skip links, ARIA roles, keyboard navigation, reduced-motion support
- JavaScript syntax corrected for special characters in publication titles (including works on the Black Decade and the Hirak movement)

---

### 3.4 Arab World Publications
**Repository:** `Dr-Mahfoud-Amara-Publications-Arab-World`  
**URL:** `https://mahfoudm33.github.io/Dr-Mahfoud-Amara-Publications-Arab-World/`  
**Coverage:** Regional and comparative scholarship across the Arab world

Spans governance, mega-events, gender, postcolonial narratives, and sport development across North Africa and the Gulf. Situates micro-level case studies within macro-level structural analysis.

---

### 3.5 Sport in Islam & Muslim Communities
**Repository:** `Sport-in-Islam-and-Muslim-Communities-Project`  
**URL:** `https://mahfoudm33.github.io/Sport-in-Islam-and-Muslim-Communities-Project/`  
**Coverage:** Global perspectives on sport and Muslim identity

Examines how Islamic values shape physical culture and how sport becomes a site of identity negotiation beyond the Arab world — including diaspora communities in Europe and North America.

---

### 3.6 The Peninsula Archive
**Repository:** `Dr-Mahfoud-Amara-in-the-Peninsula-`  
**URL:** `https://mahfoudm33.github.io/Dr-Mahfoud-Amara-in-the-Peninsula-/`  
**Coverage:** Sport, society, and politics in Qatar through *The Peninsula* newspaper

A media archive and discourse analysis resource using *The Peninsula* — one of Qatar's foremost English-language dailies — as primary source material.

---

## 4. Design Philosophy

Each platform is designed around a **place-based metaphor** that is conceptually appropriate to the research area:

| Platform | Metaphor | Rationale |
|---|---|---|
| Qatar | Corniche Walk | The Corniche is the symbolic civic and cultural spine of Doha |
| Algeria | Stadium | Football stadiums are the primary public sphere in Algerian political culture |
| Arab World | Regional panorama | Cartographic — evoking the breadth of regional coverage |
| Islam/Muslim Communities | — | Global and transnational — no single geographic anchor |
| Peninsula Archive | Newsroom/Archive | Discourse and media analysis framing |
| Central Hub | The Scholar's Atlas | Editorial, cartographic — mapping a body of knowledge |

**Aesthetic principles across all platforms:**

- **Typography:** Cormorant Garamond (display/serif) + DM Sans (body) + Share Tech Mono (data/labels). No generic system fonts.
- **Colour:** Each platform has a distinct palette anchored in culturally resonant colours. The ecosystem shares maroon and gold as connective tissue.
- **Motion:** CSS-only animations. Scroll-triggered reveals, wave animations, count-up statistics. All animations respect `prefers-reduced-motion`.
- **Accessibility:** WCAG 2.1 AA target throughout. Skip links, ARIA roles and labels, keyboard navigation, screen-reader-only publication lists, focus-visible outlines.
- **Self-contained:** Each file is a single `.html` with no external JavaScript dependencies beyond Google Fonts. No frameworks, no build tools, no npm.

---

## 5. Technical Structure

### 5.1 Technology Stack

```
Language:     HTML5, CSS3, Vanilla JavaScript (ES6+)
Hosting:      GitHub Pages (free, static)
Fonts:        Google Fonts CDN
Dependencies: None (no frameworks, no npm, no build step)
Browser support: All modern browsers (Chrome, Firefox, Safari, Edge)
```

### 5.2 Data Structure

All publication data is stored as a JavaScript array (`const DATA = [...]`) directly inside each `index.html`. Each publication object follows this schema:

```javascript
{
    year:         "2024",               // Publication year (string)
    type:         "Article",            // Article | Chapter | Edited Volume | Book
    title:        "...",                // Full publication title
    authors:      "...",                // Author(s) as they appear in citation
    ref:          "...",                // Full bibliographic reference
    url:          "https://doi.org/...",// DOI or publisher URL
    summary:      "...",                // 150–250 word descriptive abstract
    contribution: "...",                // Theoretical/scholarly contribution statement
    tags:         ["Theme A", "Theme B"]// Thematic filter tags (array of strings)
}
```

### 5.3 Theming

All colours are defined as CSS custom properties at `:root` level:

```css
:root {
    --maroon:   #8A1538;    /* Qatar University / primary */
    --gold:     #D4AF37;    /* Accent throughout */
    --sand:     #f9f6f0;    /* Background */
    --sea-dark: #0c3352;    /* Corniche sea */
    /* ... platform-specific variables */
}
```

Overriding for a new platform: copy the root block and replace values.

### 5.4 Export Functionality

The Corniche Walk platform includes a `downloadCSV()` function that exports all publication data as a formatted `.csv` file (`Amara_Qatar_Publications.csv`). This can be replicated across all platforms by copying the function and updating the filename.

---

## 6. Research Themes

The ecosystem is organised around five interlocking research themes, each cross-cutting multiple platforms:

| # | Theme | Key Concepts | Primary Platforms |
|---|---|---|---|
| 1 | **Sport, Power & Geopolitics** | Soft power (Nye), sport diplomacy, mega-events, state agency, sportswashing critique | Qatar, Arab World |
| 2 | **Sport, Identity & Nation-building** | National identity, Bourdieu (symbolic capital), postcolonial theory, biographical method | Algeria, Arab World, Islam |
| 3 | **Media, Discourse & Counter-narratives** | CDA, Said's Orientalism, framing theory, counter-narratives | Peninsula Archive, Arab World |
| 4 | **Sport Development, Ethics & Governance** | WADA, anti-doping policy, sport-for-development, political economy of sport | Qatar, Arab World |
| 5 | **Gender & Local Voices in MENA Sport** | Feminist sport sociology, Sehlikoglu, de Certeau, local epistemologies | Arab World, Algeria, Islam |

---

## 7. Deployment Guide

### 7.1 Deploying the Central Hub

1. Ensure you have a GitHub repository named exactly `mahfoudm33.github.io` (your GitHub username + `.github.io`)
2. Place `index.html` at the root of this repository
3. Go to **Settings → Pages** and confirm the source is set to the `main` branch, root (`/`) directory
4. The site will be live at `https://mahfoudm33.github.io/` within a few minutes

### 7.2 Deploying a Platform

1. Create a new GitHub repository (e.g., `Sport-Policy-Society-Qatar`)
2. Upload the platform's `index.html` as the only file (or in a `/docs` folder if preferred)
3. Enable GitHub Pages from **Settings → Pages**
4. The platform will be live at `https://mahfoudm33.github.io/Sport-Policy-Society-Qatar/`

### 7.3 Linking Between Platforms

All inter-platform links use absolute URLs. To update a link in the central hub, locate the `href` attribute in the relevant `<a>` tag in `index.html` and replace with the correct GitHub Pages URL.

The ecosystem nav bar (present on all platforms) uses the same link set:

```html
<a href="https://mahfoudm33.github.io/Sport-Policy-Society-Qatar/">The Corniche Walk</a>
<a href="https://mahfoudm33.github.io/Sport-and-Algerian-Studies/">Sport & Algerian Studies</a>
<!-- etc. -->
```

---

## 8. Adding or Updating Publications

### 8.1 Adding a New Publication to an Existing Platform

Open the relevant `index.html` and locate the `const DATA = [...]` array. Add a new object following the schema in §5.2. Example:

```javascript
{
    year: "2025",
    type: "Article",
    title: "Sport Diplomacy and the Gulf: Rethinking Soft Power",
    authors: "Mahfoud Amara",
    ref: "International Journal of Sport Policy, forthcoming.",
    url: "https://doi.org/10.xxxx/xxxxx",
    summary: "This article examines...",
    contribution: "Advances the argument that...",
    tags: ["Sport policy & governance", "Media & discourse"]
},
```

> **Important:** If the title contains apostrophes or special characters, use Unicode escape sequences to avoid JavaScript syntax errors. For example: `"Black Decade"` → `"Black Decade"` (no issue), but `"Algeria's Sport"` → use `"Algeria\u2019s Sport"` or double-check escaping.

### 8.2 Adding a New Platform

1. Duplicate the closest existing platform file as a template
2. Update the `DATA` array with the new publication set
3. Update the CSS colour palette variables for the new platform's identity
4. Update the metaphor/visual elements (skyline, stadium, etc.) or replace with a new concept
5. Add the new platform to the ecosystem nav bar in **all** existing platform files and in `index.html`
6. Add a new platform card to the `#platforms` section of `index.html`

### 8.3 Updating the Ecosystem Nav Bar

The nav bar appears in the `<nav class="eco-nav">` element at the top of every platform file. When adding a new platform, append a new `<a>` tag to the `.eco-links` div in all files:

```html
<a href="https://mahfoudm33.github.io/NEW-REPO-NAME/" 
   target="_blank" rel="noopener noreferrer">
    New Platform Name
</a>
```

---

## 9. Accessibility

All platforms are built to **WCAG 2.1 Level AA** as a target. Implemented features across the ecosystem:

| Feature | Implementation |
|---|---|
| Skip navigation | `<a class="skip-link" href="#panel">Skip to main content</a>` |
| ARIA landmarks | `role="region"`, `role="navigation"`, `role="toolbar"`, `aria-label` throughout |
| Keyboard navigation | All interactive elements (markers, pills, links, buttons) are focusable with `tabindex="0"` where needed |
| Focus indicators | `focus-visible` outlines in gold (`3px solid var(--gold)`) on all interactive elements |
| Screen-reader publication list | Hidden `<ul id="sr-pub-list">` with full publication data for assistive technology users |
| Reduced motion | `@media (prefers-reduced-motion: reduce)` disables all animations ecosystem-wide |
| Decorative aria-hidden | All purely decorative SVGs, waves, and visual elements carry `aria-hidden="true"` |
| Colour contrast | All text/background combinations meet 4.5:1 minimum ratio |
| `lang` attribute | `<html lang="en">` on all pages |

---

## 10. Academic Context

This project is part of a broader knowledge dissemination strategy shaped by two scholarly commitments:

**Open access equity.** Academic publishing paywalls disproportionately disadvantage researchers in the Global South. This ecosystem makes the *substance* of peer-reviewed scholarship — abstracts, theoretical contributions, bibliographic details, and direct DOI links — freely available to any reader worldwide, independent of institutional access.

**Decolonising academic knowledge representation.** The visual and conceptual design of each platform is intentionally grounded in locally meaningful metaphors (the Corniche, the stadium, Islamic geometric patterns) rather than generic Western academic aesthetics. The ecosystem itself enacts the argument that non-Western knowledge production deserves non-Western representational forms.

The project is framed as **paused, not concluded** — an ongoing, open archive that will grow as new publications are produced and new platforms are developed.

### Relationship to Promotion and Impact

The ecosystem serves simultaneously as:
- A public-facing dissemination tool (for students, journalists, policy professionals)
- A structured evidence base for the Full Professor promotion dossier (demonstrating research output, international reach, and knowledge impact)
- A model for innovative academic communication in the field of sport social sciences

---

## 11. Roadmap

Planned features and platforms under consideration:

| Priority | Feature | Status |
|---|---|---|
| High | **Sport Diplomacy & Geopolitics Platform** — a comparative, theory-focused platform for work on soft power, sport diplomacy, and mega-events beyond any single region | Planned |
| High | **Citation & impact layer** — Crossref/Google Scholar citation counts and journal quartile badges on each publication card | Planned |
| Medium | **Unified cross-platform search** — a single search box on the hub that queries all DATA arrays simultaneously | Planned |
| Medium | **Co-author network visualisation** — D3.js force-directed graph mapping all collaborative relationships across the corpus | Planned |
| Medium | **Shareable publication cards** — one-click generation of a formatted image card (abstract + citation) for LinkedIn/social sharing | Planned |
| Medium | **Multilingual interface layer** — Arabic and French translations of titles, abstracts, and UI labels | Under consideration |
| Lower | **Anti-Doping & Sport Governance Platform** — dedicated platform for WADA-related and sport integrity scholarship | Under consideration |
| Lower | **Gender & Social Change in Arab Sport Platform** — dedicated platform for feminist and gender-focused publications | Under consideration |
| Lower | **Works in Progress / Research Agenda page** — transparent, datestamped listing of current and forthcoming projects | Under consideration |

---

## 12. Citation

If you reference or use this digital ecosystem in academic work, please cite as follows:

**Chicago (17th ed.):**
> Amara, Mahfoud. *Digital Research Ecosystem: Sport, Policy and Society in the MENA Region*. GitHub Pages, Qatar University, 2025. https://mahfoudm33.github.io/.

**APA (7th ed.):**
> Amara, M. (2025). *Digital Research Ecosystem: Sport, policy and society in the MENA region* [Interactive web platform]. Qatar University. https://mahfoudm33.github.io/

---

## 13. License

**Content** (publication abstracts, theoretical contribution statements, descriptive text):  
© Mahfoud Amara. All rights reserved. Not for reproduction without permission.

**Code** (HTML, CSS, JavaScript):  
Released under the [MIT License](https://opensource.org/licenses/MIT). You are free to adapt the platform structure and visual design for your own academic dissemination purposes with attribution.

**Linked publications:**  
All DOI links point to publisher pages. Copyright in the underlying publications rests with the respective publishers (Routledge, Springer, Taylor & Francis, Edward Elgar) and/or the author under open-access agreements where applicable.

---

<div align="center">

**Prof. Mahfoud Amara**  
*Qatar University · College of Sport Sciences*  
[orcid.org/0000-0002-1418-6710](https://orcid.org/0000-0002-1418-6710)

*"Sport is not merely a physical activity — it is a site where power is reproduced, identities are contested, and geopolitical strategies are enacted."*

</div>
