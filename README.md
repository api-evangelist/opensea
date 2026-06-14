# OpenSea (opensea)

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
