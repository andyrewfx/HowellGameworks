# Channel Status and Analytics

This page separates active sales and operating workflows from integrations that are still being built or validated. A channel can be selling today without every order and fulfillment step being automated through an API.

## Channel status

| Channel | What is in use | What is not yet established |
| :--- | :--- | :--- |
| **Custom Discord commerce** | Product discovery, cart, checkout, and connected print-on-demand order workflows are live. Discord is the most integrated direct-sales path in TCG Battleship. | Broader attribution from audience exposure and engagement through conversion is future work. |
| **Whatnot** | Stream games and operator workflows are in use. Post-show Show Report imports match purchases to saved stream activity where possible and support fulfillment and analytics. | The planned live-auction browser companion is not implemented. Report imports are not the same as live auction capture. |
| **Etsy** | Etsy sales are live. Seller-side listing creation and management tooling has been built and is being validated. | Real Etsy receipt/order reconciliation and a verified handoff into print-on-demand fulfillment are still outstanding. Do not interpret live sales as a complete Etsy API-to-production integration. |
| **eBay** | Early integration groundwork has been completed. | A live seller/listing connection and eBay sales workflow are not in operation. |

Other channels may be considered later, but no additional marketplace launch is promised by this roadmap.

## Analytics available today

The current analytics foundation combines Whatnot Show Report purchases and paid Discord/VOD POD card orders. Where the source records support it, the system can show channel-attributed sales activity, buyer and product summaries, popular cards or characters, recorded revenue and units, and observed purchase timing. Giveaways and incomplete or unmatched source data are treated separately rather than silently counted as confirmed sales.

These are insights about recorded activity. They are not yet a complete cross-channel ledger or an exposure-adjusted marketing measurement system.

## Important measurement boundaries

- **A sale is not a giveaway.** Whatnot report data may need operator review when a line does not identify its type.
- **A fulfillment status is not a print event.** The system does not infer a physically printed quantity from an order or queue state.
- **A purchase-time pattern is not a conversion rate.** Complete audience exposure, viewer engagement, and time-live denominators are not available across all channels.
- **Missing attribution stays missing.** A card, set, buyer, timestamp, or price is not guessed when source data is ambiguous or incomplete.
- **Marketplace activity is channel-specific.** Current Discord, Whatnot, Etsy, and eBay states are not interchangeable, and an external sale does not imply a verified API sync.

## Planned analytics direction

The roadmap is to extend verified order capture to more channels, improve cross-channel attribution, record actual print events separately from sales and fulfillment, and add richer reporting by product, set, time period, and channel. Relating customer engagement and marketing exposure to sales is a longer-term goal that depends on collecting reliable engagement data.

For product milestones and the broader sequence of work, see the [public progress report](./PUBLIC_PRODUCT_PROGRESS.md) and [omnichannel roadmap](./PUBLIC_OMNICHANNEL_MARKETING_ROADMAP.md).
