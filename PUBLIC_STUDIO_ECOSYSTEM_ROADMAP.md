# Howell Gameworks Studio & Ecosystem Public Roadmap

Public tracker for the Card Creation Studio, Persistent Print Hub, Multi-Target Crop Engine, Content Safety Framework, and Omnichannel Commerce Integrations.

---

## 📊 High-Level Status Dashboard

| Phase | Initiative | Status | Key Deliverables |
| :--- | :--- | :--- | :--- |
| **Phase 1** | **Studio Cockpit & Instant Search** | **DONE** | In-Set search (`Ctrl+F`), 5-menu docked command bar, canvas cleanup |
| **Phase 2** | **Persistent Print Hub & Sheet Packer** | **CORE COMPLETE** | Persistent print manifest, auto-sync, live dock counter, stream engine bridge, watermark-safe output |
| **Phase 3** | **Creative Triad & Multi-Target Crop** | **DONE** | Slide-out Design Drawer & Multi-Target Crop Engine (Cards, 5×7, 8×10, Stickers) |
| **Phase 4** | **Studio "Zen Canvas" & Adaptive Interface** | **DONE** | Pure cards canvas, slide-out off-canvas panels, thumbnail zoom slider, IP mode switching |
| **Phase 5** | **Unified Commerce & Discovery Engine** | **COMPLETED** | Direct catalog SKUs, multi-line bulk ordering (`!add`), alphabetical character directory (`!characters`) |
| **Phase 6** | **Unified Stream Print Fulfillment & Duplex Imposition** | **DONE** | Stream print provenance, duplex back mirroring, paired batch sheets, ordered print run exports |
| **Phase 7** | **Content Safety & Moderation Framework** | **DONE** | Channel-aware SFW/ECCHI/NSFW exposure, thread policy inheritance, audience-filtered discovery, checkout guards |
| **Phase 8** | **Discord Slash Commands & Live Autocomplete** | **COMPLETE** | Discord REST API v10 slash commands, unified `/shop` and `/cart`, sub-50ms autocomplete, order status notifications |
| **Phase 9** | **Card Studio Visual Moderation & Safe Previews** | **COMPLETE** | Two-column censorship studio, reverse-blur face window, mosaic shaders, fail-closed public preview rendering |
| **Phase 10** | **Format-Aware Dynamic Previews & Merchandise Showcase** | **COMPLETE** | Server-side sticker generator with 28-angle radial dilation, archival matted fine art previews, format preview swapping |
| **Phase 11** | **Omnichannel Marketing & Drop Manager** | **COMPLETED** | Unified drop manager, channel switcher, landscape/portrait rarity-ordered promotional sheets |
| **Phase 12** | **Marketplace POD Channel Integrations** | **IN PROGRESS** | Channel-neutral commerce data contracts, idempotent event sourcing, marketplace listing & order sync |
| **Phase 13** | **Cross-Channel Sales & Production Analytics** | **PLANNED** | Multi-channel sales metrics, print count audits, format performance breakdowns, production heat maps |

---

## 🏗️ Detailed Phase Overview

### 🎨 Phase 1: Studio Cockpit & Instant Search
- **In-Set Real-Time Filter Engine**: Instant character search (`Ctrl+F`) with zero-latency CSS matching (`.card-filtered-out`).
- **Dynamic Selection Multiplier**: Bulk filter actions and Esc key reset.
- **Persistent Docked Bottom Bar**: Fixed glassmorphism command bar with fly-up menus for Set management, Design controls, Batch tools, Print Hub, and Diagnostics.
- **Canvas Cleanup**: Collapsed auxiliary toolbars into expandable drawers, optimizing workspace headroom.

### 🖨️ Phase 2: Persistent Print Hub & Sheet Packer
- **Persistent Print Manifest**: Server-backed print manifest surviving browser reloads and service restarts.
- **Universal Ingestion & Auto-Sync**: Bidirectional synchronization between web client and server print queues.
- **Live Print Dock Badge**: Real-time counter badge on the Studio bottom bar showing queued print volume.
- **Watermark-Safe Physical Printing**: Enforcement preventing promotional watermarks from rendering on physical production sheets.

### ✂️ Phase 3: Creative Triad & Multi-Target Crop
- **Slide-Out Design Drawer**: Off-canvas side-by-side editing for borders, fonts, and drop shadows with zero scrolling.
- **Multi-Target Visual Framing Engine**: Non-destructive framing modal with independent coordinates for 2.5×3.5 cards, 5×7 mini art, 8×10 fine art, and 3×5 stickers.
- **Interactive Crop Controls**: Drag-to-pan, mouse-wheel zoom, Rule of Thirds grid, and orientation toggle.
- **Rapid Navigation**: Keyboard shortcuts (`[` and `]`) and auto-committing batch framing controls.

### 🖼️ Phase 4: Studio "Zen Canvas" & Adaptive Interface
- **Pure Cards Canvas Layout**: Migrated static controls into off-canvas drawers (`Set`, `Batch`, `Data`, `Design`), elevating card gallery to primary focus.
- **Dynamic Viewport & Thumbnail Zoom**: Responsive CSS Grid auto-scaling with real-time slider (140px to 440px) and preset persistence.
- **IP-Centric Interface Modes**: Context-aware controls tailored for Trading Cards, Fine Art Prints, and Die-Cut Stickers.
- **Minimal Header**: Floating top bar with set name badge, card counts, instant search filter, and drawer launchers.

### 🛒 Phase 5: Unified Commerce & Discovery Engine
- **Direct Catalog SKU Multi-Search**: Flexible search engine matching direct SKUs, set codes, and character names.
- **Bulk List Quick-Adder**: Multi-line paste parser supporting SKU ranges and quantity multipliers.
- **Alphabetical Character Directory**: Paginated character directory with 25-item pages, search modal, and private kiosk browsing.
- **Universal Asset Localizer**: Automatic asset consolidation into structured local storage on save.

### 🖨️ Phase 6: Unified Stream Print Fulfillment & Duplex Imposition
- **Stream Provenance Retention**: Persistent metadata linking queued print items to their original live stream session and sequence.
- **Renderer Parity**: Front-end and server-side renderer alignment guaranteeing identical visual output across queues.
- **Paired Card-Back Sheets**: Mirrored back sheet generation designed for long-edge duplex printing alignment.
- **Ordered Run Fulfillment**: Sequential packing preserving custom order runs with slot-level manifest auditing.

### 🛡️ Phase 7: Content Safety & Moderation Framework
- **Multi-Tiered Rating Architecture**: SFW, ECCHI, and age-verified NSFW rating classification.
- **Channel Policy & Audience Verification**: Content gatekeeping verifying Discord age-restriction flags and channel-specific tiers.
- **Thread Policy Inheritance**: Dynamic audience policy propagation across active threads and sub-channels.
- **Fail-Closed Public Previews**: Automatic image obscuring in public channels; unobscured adult content is strictly restricted to verified channels.
- **Channel Safety Configuration Hub**: Visual dashboard for managing channel audience limits.

### ⚡ Phase 8: Discord Slash Commands & Live Autocomplete
- **Discord API v10 Commands**: Integrated application commands (`/shop`, `/card`, `/characters`, `/add`, `/cart`, `/help`).
- **High-Speed Autocomplete**: Indexed in-memory search delivering sub-50ms choices within Discord's 3-second latency limit.
- **Unified `/shop` Kiosk**: Streamlined single-flow browsing with card carousel, instant cart adder, and ephemeral cart review.
- **Multi-Format CDN Preview Vault**: Intelligent content-hashed caching preventing redundant rendering and duplicate asset uploads.
- **Automated Customer DMs**: Real-time notifications for order confirmation, payment status, and shipping updates.

### 🛡️ Phase 9: Card Studio Visual Moderation & Safe Previews
- **Unified Censorship Studio**: Ergonomic two-column layout separating the canvas viewport from modular control panels.
- **Reverse-Blur Face Window**: Interactive circular window preserving character face clarity while body elements receive heavy Gaussian blur.
- **Artistic Obscurity Styles**: Selectable shader filters including Stained Glass Mosaic, Retro 8-Bit Pixelate, Fluted Reeded Glass, and Iridescent Foil.
- **Movable Rating Badges**: Precision canvas drag controls for 18+ and advisory rating badges.

### ✨ Phase 10: Format-Aware Dynamic Previews & Merchandise Showcase
- **Headless Sticker Preview Engine**: High-fidelity die-cut preview generation using Sharp and `@napi-rs/canvas` with 28-angle radial dilation and vinyl drop shadow.
- **Dynamic Format Swapping in Discord**: Live button controls inside Discord carts allowing collectors to swap previews between cards, stickers, and art prints.
- **Archival Fine Art Print Showcase**: Headless renderer generating 5×7 and 8×10 matted window previews without card game frames.
- **Performance & Supervisor Hardening**: Database expression indexing, automated process recovery, and paced cache generation.

### 📣 Phase 11: Omnichannel Marketing & Drop Manager
- **Omnichannel Drop Workspace**: Centralized command center managing multi-channel releases across Discord, Etsy, and eBay.
- **Channel Switcher & Tagging**: Multi-tag categorizations and channel filtering.
- **Polished Promotional Sheets**: Orientation-aware promotional sheets organizing cards by rarity with 2-slot landscape card formatting.

### 🛍️ Phase 12: Marketplace POD Channel Integrations (In Progress)
- **Universal Commerce Contracts**: Channel-neutral SQLite data models for orders, line items, and lifecycle events.
- **Idempotent Event Sourcing**: Reliable state updates preventing duplicate order processing across platforms.
- **Etsy Marketplace Adapter**: Automated product listing synchronization and POD order ingestion.
- **eBay Collectibles Adapter**: Integration for automated collectible drops and fulfillment tracking.
- **Cross-Channel Tracking Sync**: Automated carrier tracking and dispatch notifications returned to marketplace APIs.

### 📊 Phase 13: Cross-Channel Sales & Production Analytics (Planned)
- **Multi-Source Event Ledger**: Normalized sales, giveaway, and print event auditing across all platforms.
- **Card-Level Performance Metrics**: Per-card sales velocity, popularity heat maps, and format breakdowns.
- **Physical Production Auditing**: Verified actual print run counts versus customer sales orders.

---

*Howell Gameworks Studio Ecosystem — Engineered by Andy Howell.*
