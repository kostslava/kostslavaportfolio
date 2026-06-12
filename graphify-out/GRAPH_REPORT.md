# Graph Report - .  (2026-05-29)

## Corpus Check
- Corpus is ~3,047 words - fits in a single context window. You may not need a graph.

## Summary
- 33 nodes · 44 edges · 7 communities (6 shown, 1 thin omitted)
- Extraction: 91% EXTRACTED · 9% INFERRED · 0% AMBIGUOUS · INFERRED: 4 edges (avg confidence: 0.75)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- [[_COMMUNITY_Social & Micro-interactions|Social & Micro-interactions]]
- [[_COMMUNITY_Design & Dev Tools|Design & Dev Tools]]
- [[_COMMUNITY_3D  WebGL Projects|3D / WebGL Projects]]
- [[_COMMUNITY_Cursor Animation System|Cursor Animation System]]
- [[_COMMUNITY_Scroll & Touch Effects|Scroll & Touch Effects]]
- [[_COMMUNITY_Branding & Motion|Branding & Motion]]
- [[_COMMUNITY_React  Design System|React / Design System]]

## God Nodes (most connected - your core abstractions)
1. `Portfolio Website v2` - 18 edges
2. `Skills Cloud / Capabilities Section` - 13 edges
3. `Slava Kostrubin` - 4 edges
4. `Custom Cursor with Smooth Follow` - 3 edges
5. `Scroll Reveal Animation` - 3 edges
6. `Three.js` - 3 edges
7. `WebGL` - 3 edges
8. `Fourth Project (Branding / Motion, 2023)` - 3 edges
9. `Magnetic Hover Effect` - 2 edges
10. `React` - 2 edges

## Surprising Connections (you probably didn't know these)
- `Portfolio Website v2` --implements--> `Custom Cursor with Smooth Follow`  [EXTRACTED]
  portfolio-v2.html → portfolio-v2.html  _Bridges community 0 → community 3_
- `Portfolio Website v2` --references--> `Project Name (React / Design System, 2026)`  [EXTRACTED]
  portfolio-v2.html → portfolio-v2.html  _Bridges community 0 → community 6_
- `Portfolio Website v2` --references--> `Another Project (Full-Stack / WebGL, 2026)`  [EXTRACTED]
  portfolio-v2.html → portfolio-v2.html  _Bridges community 0 → community 2_
- `Portfolio Website v2` --references--> `Fourth Project (Branding / Motion, 2023)`  [EXTRACTED]
  portfolio-v2.html → portfolio-v2.html  _Bridges community 0 → community 5_
- `Portfolio Website v2` --implements--> `Scroll Reveal Animation`  [EXTRACTED]
  portfolio-v2.html → portfolio-v2.html  _Bridges community 0 → community 4_

## Hyperedges (group relationships)
- **Interactive UX Enhancement System** — portfoliov2_custom_cursor, portfoliov2_magnetic_effect, portfoliov2_glitch_ripple, portfoliov2_project_preview [INFERRED 0.85]
- **Scroll and Animation Reveal System** — portfoliov2_scroll_reveal, portfoliov2_intersection_observer, portfoliov2_hero_parallax [INFERRED 0.85]
- **Mobile Experience Layer** — portfoliov2_mobile_nav, portfoliov2_touch_tilt, portfoliov2_custom_cursor [INFERRED 0.75]

## Communities (7 total, 1 thin omitted)

### Community 0 - "Social & Micro-interactions"
Cohesion: 0.27
Nodes (10): GitHub Profile (kostslava), Glitch Ripple Click Effect, Hero Name Parallax on Scroll, LinkedIn Profile (slava-kostrubin), Marquee Ticker, Mobile Bottom Navigation, Portfolio Website v2, Floating Project Preview on Hover (+2 more)

### Community 1 - "Design & Dev Tools"
Cohesion: 0.29
Nodes (8): Creative Direction, Figma, Next.js, Node.js, Prototyping, Skills Cloud / Capabilities Section, TypeScript, UI/UX Design

### Community 2 - "3D / WebGL Projects"
Cohesion: 0.50
Nodes (4): Another Project (Full-Stack / WebGL, 2026), Third Project (Three.js / UX Research, 2023), Three.js, WebGL

### Community 3 - "Cursor Animation System"
Cohesion: 0.67
Nodes (3): Custom Cursor with Smooth Follow, Magnetic Hover Effect, requestAnimationFrame Animation Loop

### Community 4 - "Scroll & Touch Effects"
Cohesion: 0.67
Nodes (3): IntersectionObserver API, Scroll Reveal Animation, Touch Tilt Card Effect (Mobile)

### Community 5 - "Branding & Motion"
Cohesion: 0.67
Nodes (3): Branding, Motion Design, Fourth Project (Branding / Motion, 2023)

## Knowledge Gaps
- **7 isolated node(s):** `TypeScript`, `Next.js`, `Figma`, `Node.js`, `Creative Direction` (+2 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **1 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `Portfolio Website v2` connect `Social & Micro-interactions` to `Design & Dev Tools`, `3D / WebGL Projects`, `Cursor Animation System`, `Scroll & Touch Effects`, `Branding & Motion`, `React / Design System`?**
  _High betweenness centrality (0.763) - this node is a cross-community bridge._
- **Why does `Skills Cloud / Capabilities Section` connect `Design & Dev Tools` to `Social & Micro-interactions`, `3D / WebGL Projects`, `Branding & Motion`, `React / Design System`?**
  _High betweenness centrality (0.509) - this node is a cross-community bridge._
- **Why does `Custom Cursor with Smooth Follow` connect `Cursor Animation System` to `Social & Micro-interactions`?**
  _High betweenness centrality (0.062) - this node is a cross-community bridge._
- **What connects `Floating Project Preview on Hover`, `Glitch Ripple Click Effect`, `Hero Name Parallax on Scroll` to the rest of the system?**
  _12 weakly-connected nodes found - possible documentation gaps or missing edges._