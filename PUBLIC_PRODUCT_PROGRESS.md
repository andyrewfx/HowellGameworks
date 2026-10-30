# Howell Gameworks - Product Progress

**Current public snapshot — October 30, 2026**

Howell Gameworks is building two complementary TCG/CCG products. **TCG Battleship** serves creators and businesses building, marketing, and producing card products. **Novus TCG** serves collectors and communities organizing, discovering, and sharing their collections. This report separates operating capabilities from integrations and analytics that are still in progress.

## TCG Battleship: create, market, sell, and produce

TCG Battleship is an operational end-to-end workflow for managing card products: build and edit a card catalog, prepare creative assets and product formats, promote and sell products, then organize orders for physical print and fulfillment.

### Creation and creative production

- Build and manage card sets and catalogs in a dedicated creative studio.
- Edit artwork and prepare different presentations for trading cards, art prints, and stickers.
- Create previews and promotional materials for products and releases.
- Organize print jobs, prepare print sheets, and support paired card fronts and backs.

### Live streaming and sales

- Operate live stream games, session queues, winner displays, and card-art overlays.
- Send stream wins and other selected items into print and fulfillment workflows.
- Sell through a custom Discord channel connected to the platform, including product discovery, cart, checkout, and print-on-demand order handling.
- Import Whatnot Show Reports, match reported purchases to stream activity where possible, and carry matched items into order and print workflows.
- Sell through Etsy; seller-side listing and management tooling is being connected to the broader workflow.

### Operations and analytics already in use

- Track sales and inventory activity in the Battleship business tools.
- Review Whatnot and Discord/VOD print-on-demand sales in a shared analytics view.
- Examine recorded revenue and units, popular cards or characters, frequent buyers, channel totals, and observed purchase timing.
- Keep sale, giveaway, and fulfillment activity distinct where source data supports it.

These tools provide meaningful business visibility today, but they are not yet a complete measurement system for every marketing channel. In particular, purchase reporting is not the same as measuring audience exposure, conversion, or actual physical print counts.

## Novus TCG: collector and community platform

Novus TCG is a self-contained, AI-driven TCG collection, portfolio, and social platform. It is designed to serve collectors directly while also supporting streamer and community experiences.

- Organize collections into folders and portfolio views.
- Discover cards and collection information with AI-assisted tools.
- Set local alerts for trading-card releases and drops.
- Connect collection and community experiences with Discord.
- Work with live product inventory and sales integrations.
- Support streamer-facing games, tools, and leaderboard experiences.

Novus TCG and TCG Battleship are distinct product tracks within a larger ecosystem vision: one supports the people who create, promote, and produce card products; the other supports the collectors and communities around them.

## Channel status

| Channel | Current status |
| :--- | :--- |
| **Custom Discord commerce** | Sales and print-on-demand order workflows are live and connected to TCG Battleship. |
| **Whatnot** | Live stream workflows and post-show Show Report purchase capture are in use. The report import supports sales and customer analytics; a live auction companion is a separate proposed project, not an existing feature. |
| **Etsy** | Sales are live. Seller-side listing authorization and management tooling are implemented and being validated; automated receipt/order reconciliation into print fulfillment still needs real-order validation. |
| **eBay** | Early integration groundwork is in progress. eBay sales/listing integration is not live. |

“Sales are live” describes current selling activity; it does not mean that every channel has a completed API integration with centralized order and fulfillment synchronization.

## Analytics: delivered and still ahead

**Implemented foundation:** Whatnot Show Report purchases and paid Discord/VOD POD card orders feed an initial shared analytics slice. It includes buyer and product summaries, channel attribution where available, and separate treatment for giveaways and incomplete data.

**Still to build:** extend reliable order capture to Etsy and eBay; strengthen shared attribution across all channels; record actual physical print events; and develop broader business reporting that relates customer engagement and marketing activity to sales across live streams, Discord, and passive marketplace sales.

Today’s observed purchase-time patterns and sales totals describe the records available to the system. They do not yet provide complete exposure-adjusted conversion or prove a complete historical sales/print ledger.

## Stage and working approach

The core TCG Battleship workflow is operational, and some channels are already selling. **External customer pilots have not yet started.** The work is founder-led, with integrations developed incrementally so current sales workflows can remain stable while new channels and analytics are validated.

For priorities and future direction, see the [omnichannel product roadmap](./PUBLIC_OMNICHANNEL_MARKETING_ROADMAP.md).
