# OpenSea (opensea)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

OpenSea is the world's largest NFT marketplace, offering a REST API for querying NFT collections, listings, offers, orders, and events, and for managing programmatic NFT trading across 27+ blockchain chains including Ethereum, Polygon, Base, Solana, Arbitrum, Optimism, and more.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/opensea/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/opensea/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- NFT
- Marketplace
- Web3
- Blockchain
- Trading
- Digital Assets

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### OpenSea NFT API

Retrieve individual NFT metadata, ownership, rarity, analytics, and owners across supported blockchain chains. Supports batch NFT retrieval, metadata refresh, validation, and collection-based listing.

### OpenSea Collection API

Query NFT collection details, traits, floor prices, holders, offer aggregates, trending and top collections. Supports batch retrieval by slugs and discovery of new and popular collections.

### OpenSea Listing API

Create, fulfill, and query NFT listings on OpenSea. Supports best listing retrieval per collection or NFT, cross-chain fulfillment, and collection sweep purchases with automatic substitution for unavailable items.

### OpenSea Offer API

Build, create, fulfill, and query NFT offers and bids on OpenSea. Supports collection-wide offers, trait-based offers, item-specific bids, and best-offer retrieval per NFT.

### OpenSea Order API

Look up and cancel individual orders by chain, protocol address, and order hash. Supports both Seaport listing and offer orders.

### OpenSea Events API

Retrieve historical NFT marketplace events including sales, transfers, mints, and cancellations by account, collection, or individual NFT. Also supports real-time event streaming via the Stream API WebSocket.

### OpenSea Token API

Retrieve fungible token details, balances, holders, liquidity pools, price history, OHLCV candlestick data, trending tokens, and swap quotes for token trading across supported chains.

### OpenSea Account API

Retrieve OpenSea account profiles, resolve ENS/usernames, and access portfolio analytics including net worth history, P&L tracking, owned collections, favorites, listings, and offers.

### OpenSea Drops API

Discover NFT drops, check mint eligibility, build mint transactions, deploy NFT contracts, and track transaction receipts for minting operations.

### OpenSea Search API

Search across OpenSea collections, NFTs, tokens, and accounts by keyword. Powers discovery of assets and creators across the OpenSea marketplace.

### OpenSea Stream API

Real-time WebSocket event streaming for NFT marketplace activity per collection, including item listed, item sold, item transferred, item metadata updates, item cancelled, item received offer, and item received bid events.

### OpenSea Swap API

Get swap quotes and execute token trading with executable transaction data across supported blockchain chains.

## Common Properties

- [Authentication](https://docs.opensea.io/reference/api-keys)
- [Plans](plans/opensea-plans.yml)
- [Rate Limits](rate-limits/opensea-rate-limits.yml)
- [FinOps](finops/opensea-finops.yml)
- [SDKs](https://github.com/ProjectOpenSea/opensea-sdk)
- [CLI](https://github.com/ProjectOpenSea/opensea-cli)
- [OpenAPI](https://raw.githubusercontent.com/ProjectOpenSea/api-types/main/opensea-api.json)
- [Terms of Service](https://opensea.io/tos)
- [Privacy Policy](https://opensea.io/privacy)
- [Status Page](https://status.opensea.io)
- [Support](https://support.opensea.io)
- [Blog](https://opensea.io/blog)
