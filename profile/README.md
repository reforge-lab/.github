# Reforge (`reforge-lab`)

<div align="center">

# ⚡ Reforge
### MEV-Aware Batch Auction Protocol for DeFi Liquidations

*An open-source research and engineering lab building fairer, gas-efficient liquidation mechanisms for decentralized finance.*

[![Official App](https://img.shields.io/badge/Live%20Platform-reforge--lab.vercel.app-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://reforge-lab.vercel.app)
[![Documentation Hub](https://img.shields.io/badge/Documentation-Fumadocs-7c3aed?style=for-the-badge&logo=bookstack&logoColor=white)](https://reforge-lab.vercel.app/docs)
[![Research Paper](https://img.shields.io/badge/Research%20Paper-PDF-dc2626?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://reforge-lab.vercel.app/documents/MEV_Aware_DeFi_Liquidation_System.pdf)

</div>

---

## 🧭 About Reforge

**Reforge** is an open-source protocol and research project that redesigns DeFi liquidations. 

Conventional lending protocols rely on first-come, first-served races—triggering destructive Priority Gas Auctions (PGAs) where liquidator searchers burn up to 90% of their profits in gas bribes to block proposers. Reforge replaces these latency races with discrete, time-windowed batch auctions that score liquidations on true economic efficiency.

---

## 🗺️ Organization Map & Repositories

| Repository | Purpose | What's Inside |
| :--- | :--- | :--- |
| [**`frontend`**](https://github.com/reforge-lab/frontend) | Web Platform & Docs | Next.js 16 app hosting the Protocol Dashboard, Liquidation Marketplace, Searcher Console, Simulation Lab, and interactive Fumadocs documentation. |
| [**`paper`**](https://github.com/reforge-lab/paper) | Academic Research | LaTeX thesis synopsis, research paper drafts, and mathematical modeling artifacts. |
| [**`contracts`**](https://github.com/reforge-lab) | Smart Contracts *(WIP)* | Core EVM protocol written in Solidity (`LendingPool`, `LiquidationAuction`, `PriceOracle`) managed with Foundry. |
| [**`backend`**](https://github.com/reforge-lab) | Real-time Services *(WIP)* | Fastify, Redis BullMQ, and viem block listener for tracking underwater positions and managing auction state. |
| [**`.github`**](https://github.com/reforge-lab/.github) | Community & Org Profile | Organization profile, issue templates, and shared configurations. |

---

## 📚 Documentation & Key Links

All comprehensive technical and architecture documentation lives on the [Reforge Docs Site](https://reforge-lab.vercel.app/docs):

- 🚀 **Live Platform**: [reforge-lab.vercel.app](https://reforge-lab.vercel.app)
- 📚 **Documentation Hub**: [reforge-lab.vercel.app/docs](https://reforge-lab.vercel.app/docs)
  - 🔰 [**Getting Started**](https://reforge-lab.vercel.app/docs/getting-started): Problem statement, DeFi fundamentals, and literature review.
  - 🏗️ [**Architecture**](https://reforge-lab.vercel.app/docs/architecture): End-to-end system design across contracts, backend, and frontend.
  - 📋 [**Specifications**](https://reforge-lab.vercel.app/docs/specs): Living technical specs for contracts and backend services.
  - 🔬 [**Research**](https://reforge-lab.vercel.app/docs/research): Methodology, simulation design, and benchmark findings.
  - 🛠️ [**Guides**](https://reforge-lab.vercel.app/docs/guides): Local development environment setup and deployment guides.
- 📑 **Research Paper**: [MEV-Aware DeFi Liquidation System (PDF)](https://reforge-lab.vercel.app/documents/MEV_Aware_DeFi_Liquidation_System.pdf)
- 🤖 **AI Assistant Feeds**: [`llms.txt`](https://reforge-lab.vercel.app/llms.txt) · [`llms-full.txt`](https://reforge-lab.vercel.app/llms-full.txt)

---

<div align="center">
  <sub>Reforge Lab · Licensed under <a href="https://opensource.org/licenses/MIT">MIT</a></sub>
</div>


