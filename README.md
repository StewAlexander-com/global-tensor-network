# Global Systems Tensor Network

An interactive model of **15 interconnected global systems** visualized as a tensor network — showing how energy, climate, AI, water, geopolitics, critical minerals, and more affect each other through **verifiable causal couplings**.

![License](https://img.shields.io/badge/license-MIT-blue.svg)

## Live Demo

**[→ View the Interactive Model](https://stewalexander-com.github.io/global-tensor-network/)**

## The Thesis

> The world's biggest risk isn't any single crisis — it's how they're coupled.

This model maps 15 global systems with push/pull couplings between them. Each edge represents a documented causal relationship with cited sources (EIA, IEA, Carnegie Endowment, ACS Energy Letters, Nature, Belfer Center, and more).

### Key Findings

- **Energy Density** is the #1 systemic lever — it touches 22 connections, more than any other node
- **Ammonia (NH₃)** is the most underexploited structural fix — the only node that simultaneously improves energy density, climate, agriculture, AND reduces resource concentration
- The **Hormuz Crisis** is a live stress test showing how 20M bbl/day blocked → 1/3 global fertilizer trade halted → cascade through agriculture, political stability, resource nationalism

## The 15 Systems

| System | Category | Key Coupling |
|--------|----------|-------------|
| Energy Density | Infrastructure | 22 connections — most connected node |
| Oil & Gas | Energy | 20M bbl/day through Hormuz |
| Maritime Chokepoints | Infrastructure | Hormuz, Malacca, Suez, Panama |
| Agriculture & Food | Human | 1/3 fertilizer trade via Hormuz |
| Water Systems | Environment | 70% freshwater → agriculture |
| Climate System | Environment | 17% agricultural decline by 2050 |
| AI & Compute | Technology | 176 → 580 TWh data centers by 2028 |
| Critical Minerals | Resources | 86% top-3 refining concentration |
| Geopolitics | Governance | 55% minerals under export controls |
| Political Stability | Governance | Food shocks → instability cascade |
| Resource Nationalism | Governance | Russia/China fertilizer export bans |
| Renewable Energy | Energy | Land-use conflicts with agriculture |
| Ammonia (NH₃) | Solution | 12.7 MJ/L vs 8.5 MJ/L liquid H₂ |
| Global Supply Chains | Infrastructure | Just-in-time vulnerability |
| Financial Markets | Economic | Oil price → global commodity cascade |

## Interactive Features

- **3D tensor network** — rotate, zoom, and pan across a full 3D visualization with logarithmic-scaled node spacing
- **Click any node** — focused zoom brings the selected node forward; infographic-style detail panel with stats, key facts, and all couplings with source citations
- **Click any edge** — see the coupling mechanism and source
- **5 stress-test scenarios:**
  - Baseline
  - Hormuz Crisis (cascade visualization)
  - Ammonia Fix (structural solution pathway)
  - AI Surge (compute demand stress)
  - Climate +2°C (agricultural/water cascade)
- **NH₃ button** — highlight the ammonia structural fix pathway
- **Dark/light mode**
- **Responsive** — mobile-optimized bottom-sheet panel, desktop sidebar, iOS touch handling
- **PWA** — installable as a standalone app on mobile and desktop

## Data Sources

All coupling weights are directional and sourced from:

- **U.S. Energy Information Administration (EIA)** — Hormuz flow data, oil transit chokepoints
- **International Energy Agency (IEA)** — Critical minerals outlook, energy projections
- **Carnegie Endowment for International Peace** — Fertilizer supply chain analysis
- **ACS Energy Letters** — Ammonia as hydrogen carrier energy density
- **Nature** — Water-Energy-Food-Ecosystems nexus cascading effects
- **Lawrence Berkeley National Laboratory** — US data center energy usage
- **Belfer Center, Harvard** — AI and US electric grid analysis
- **Fortune, The Conversation** — Hormuz crisis impact analysis
- **UN World Food Programme** — Food insecurity projections

## Technology

Single HTML file. No build step. No bundler.

- **Three.js r170** — 3D WebGL rendering with OrbitControls
- **Vanilla CSS** — Custom properties, fluid type scale, dark/light mode, backdrop-filter blur
- **General Sans** (Fontshare) + JetBrains Mono — Typography
- **Progressive Web App** — manifest.json, app icons (192/512/maskable), apple-touch-icon, favicons
- **SEO** — Open Graph, Twitter Card, JSON-LD structured data, canonical URL

## Local Development

```bash
# Clone
git clone https://github.com/StewAlexander-com/global-tensor-network.git
cd global-tensor-network

# Serve (any static file server works)
npx serve .
# or
python3 -m http.server 8000
```

Open `http://localhost:3000` (or `:8000`).

## Deployment

Static site — deploy `index.html`, `manifest.json`, and the `icons/` directory to any static host:

- **GitHub Pages** — Push to `main`, enable Pages in repo settings
- **Netlify/Vercel** — Point at the repo root
- **S3/CloudFront** — Upload all files

## Contributing

Contributions welcome. Especially:

1. **New coupling data** — add verified edges with sources
2. **New scenario stress tests** — model additional cascade pathways
3. **Improved coupling weights** — refine based on quantitative data
4. **Additional nodes** — expand the model (cybersecurity, demographics, etc.)

## License

MIT — see [LICENSE](LICENSE)

## Author

**Stewart Alexander** — [stewalexander.com](https://stewalexander.com)
