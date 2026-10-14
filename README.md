# Howell Gameworks Studio & Omnichannel Platform

Welcome to the **Howell Gameworks** technical portfolio and public roadmap workspace.

Howell Gameworks designs and engineers physical & digital tabletop gaming experiences, creative tooling, live broadcast game engines, and full-stack print-on-demand fulfillment systems.

---

## 🎲 About Howell Gameworks

Founded by **Andy Howell**, Howell Gameworks bridges the gap between digital creative workflows and physical tabletop merchandise. From real-time card framing and digital printing automation to interactive community e-commerce bots, our software ecosystem powers high-throughput manufacturing, live interactive stream breaks, and multi-channel drop orchestration.

---

## 🏛️ Ecosystem Architecture Overview

The core architecture consists of four interconnected systems:

```
┌────────────────────────────────────────────────────────────────────────┐
│                        HOWELL GAMEWORKS ECOSYSTEM                      │
├─────────────────────┬───────────────────────────┬──────────────────────┤
│ 1. CREATIVE STUDIO  │ 2. FULFILLMENT & PRINT    │ 3. OMNICHANNEL & BOT │
│ Canvas UI, Dynamic  │ Persistent Manifest Hub,  │ Discord API v10 Bot, │
│ Framing, Multi-Crop │ Imposition Sheet Packer,  │ Multi-Format Cache,  │
│ & Parametric Styles │ Duplex Print Alignment    │ Unified Commerce     │
└─────────────────────┴───────────────────────────┴──────────────────────┘
                                  │
                                  ▼
                 4. CONTENT SAFETY & MODERATION
             Tiered Channels, Fail-Closed Security,
             Dynamic Shaders & Safe Preview Windows
```

1. **Card Studio & Zen Canvas**:
   - High-density visual card design workstation handling thousands of assets with real-time CSS/DOM filtering (`Ctrl+F`).
   - Side-by-side parametric drawer for real-time border, typography, and drop-shadow styling.
   - Multi-target visual framing engine supporting cards (2.5×3.5), mini art (5×7), fine art (8×10), and die-cut vinyl stickers (3×5) from a single master asset.

2. **Persistent Print Hub & Automated Sheet Packer**:
   - Production print manifest persisting queued physical print jobs across sessions.
   - Dynamic 3×3 and 2-slot landscape card packing with automatic sheet imposition.
   - Automated paired duplex sheet generation with mirrored backs for precision double-sided physical printing.

3. **Discord Commerce Engine & Interactive Bots**:
   - Discord API v10 bot powered by `discord.js` v14 with sub-50ms indexed autocomplete choices.
   - Ephemeral interactive kiosks (`/shop`, `/cart`, `/characters`, `/card`) for frictionless customer discovery.
   - Format-aware dynamic asset swapping: customers can toggle between trading cards, matte vinyl stickers, clear tech decals, and archival matted art prints directly inside Discord embeds.

4. **Visual Safety & Content Moderation Engine**:
   - Multi-tiered audience protection (SFW, ECCHI, and age-verified NSFW).
   - Automated server-side preview generator producing reverse-blur face highlighting, mosaic pixelation, and privacy filters.
   - Fail-closed access control preventing unauthorized media distribution across public channels.

---

## 📂 Public Documentation Directory

- [**Public Ecosystem Roadmap**](./PUBLIC_STUDIO_ECOSYSTEM_ROADMAP.md): High-level multi-phase engineering status, completed milestones, and upcoming capabilities.
- [**Portfolio Demo Reel & Showcase Guide**](../showcase_demo_reel_and_teaser_shot_list.md): Detailed shot list, timings, and technical brag points for engineering hiring managers.

---

## 📬 Contact & Portfolio

- **Creator / Lead Engineer**: Andy Howell
- **Organization**: Howell Gameworks
- **GitHub**: [github.com/andyrewfx](https://github.com/andyrewfx)
- **Status**: Active Development & Engineering Showcase

---

*© Howell Gameworks. All rights reserved.*
