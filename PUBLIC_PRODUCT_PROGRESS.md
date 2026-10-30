# Howell Gameworks - Product Progress

**Current public snapshot — October 30, 2026**

Howell Gameworks is a founder-led effort to build two complementary products: **TCG Battleship** for creating, marketing, selling, and producing card products, and **Novus TCG** for collectors and communities. The work below reflects the active product roadmap and current channel documentation; it distinguishes delivered workflows from integration work that is not yet complete.

## Progress delivered: TCG Battleship

The active Battleship roadmap marks its initial twelve delivery phases complete or implemented. Together, they establish a working creator-to-commerce-to-production foundation:

| Milestone | What has been delivered |
| :--- | :--- |
| **Phases 1–4: Creative Studio** | A card-focused studio with faster catalog search, a streamlined creative canvas, design tools, and reusable framing across product formats. |
| **Phase 5 → Phase 11: Product previews** | Format-aware card, sticker, and art-print previews were moved into a later phase and delivered there; Phase 5 was not a separate abandoned feature. |
| **Phase 6: Discord shop and cart** | Product discovery, multi-search, bulk add, cart, and checkout workflows. |
| **Phase 7: Stream-to-print fulfillment** | Ordered stream work can be prepared as print packages with paired backs and item-level fulfillment context. |
| **Phase 8: Audience protections** | Channel-aware content tiers, safe discovery and previews, and checks across browsing, checkout, and publishing. |
| **Phase 9: Discord interactions** | A unified slash-command shop and cart with audience-aware autocomplete and search. |
| **Phase 10: Safer previews** | Censorship and obscured-preview workflows for content that should not be shown openly. |
| **Phase 12: Drop management** | Channel-aware drop planning and promotional workflows built around the existing Discord/VOD POD operation. |

This is not only a concept or a set of isolated mockups: the creator workflow, direct Discord sales path, stream tools, and print operations are connected. See the [TCG Battleship overview](./TCG_BATTLESHIP.md) for product capabilities and the [demos](./PUBLIC_DEMOS.md) for selected walkthroughs.

## Current channel and integration work

**Discord/VOD POD — operating.** Direct product discovery, cart, checkout, and print-on-demand order workflows are live and connected to Battleship.

**Whatnot — operating stream and reporting workflows.** Stream games and operator tools are in use. After a show, Show Report imports match purchases to saved stream activity where possible and support fulfillment and sales analysis. A live-auction companion is not part of the current product; it remains a separate proposal.

**Etsy — sales live; API-to-production workflow still being validated.** Seller-side listing creation and management tooling is connected to the platform, and Etsy sales are live. Receipt/order reconciliation and a verified handoff into print fulfillment still need real-order validation. These are separate tracks: live selling does not establish a complete API integration.

**eBay — groundwork only.** Initial integration groundwork exists, but live eBay listings, sales, and order workflows are not in operation.

**Shared commerce foundation — partially delivered.** The roadmap establishes a shared order/event foundation and connects Discord/VOD POD orders and Whatnot Show Report imports. Marketplace-specific adapters and order-to-production flows remain separate pieces of work.

For the detailed channel boundaries and analytics limits, see [Channel Status and Analytics](./PUBLIC_CHANNEL_STATUS_AND_ANALYTICS.md).

## Analytics in use

The first shared analytics slice combines matched Whatnot Show Report purchases with paid Discord/VOD POD card orders. Current reporting can summarize recorded customer and product activity, card/character interest, channel totals, units and revenue where supplied, and observed purchase timing. Giveaways and incomplete or ambiguous data are not treated as confirmed paid card sales.

This is a useful starting point, not yet a complete marketing measurement or production ledger. Full cross-channel attribution, reliable Etsy/eBay order capture, exposure-to-conversion analysis, and durable records of actual physical print events remain future work.

## Novus TCG

Novus TCG is a distinct collector and community product, not another name for TCG Battleship. Its product experience is centered on AI-assisted collection discovery and organization, folders and portfolio views, social/community features, local release alerts, Discord connections, streamer games and leaderboards, and links to live inventory and sales. See the [Novus TCG overview](./NOVUS_TCG.md).

## Stage and next steps

The core TCG Battleship workflow is operational, with live sales in Discord and Etsy and active stream/report workflows around Whatnot. **External customer pilots have not yet started.** The next work prioritizes verifying marketplace order paths, extending trustworthy analytics, and keeping each channel's readiness visible instead of implying that the whole ecosystem is complete.

The [public omnichannel roadmap](./PUBLIC_OMNICHANNEL_MARKETING_ROADMAP.md) describes the next outcomes, longer-term direction, and exploratory ideas. It does not publish private engineering detail or promise launch dates.
