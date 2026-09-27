![Conduit Logo](https://cdn.prod.website-files.com/67a08c4f7b1c5f99aa6e9201/67a1f51d61edb50c3ea0c182_conduit%20LOGO.png)

# Conduit

Open-source commerce clients built on Nostr and Bitcoin Lightning. Merchants publish signed listings, shoppers send encrypted orders, and payments go directly through the wallets and providers people choose. Conduit does not custody funds or durable Nostr account keys.

## Explore the apps

| App | What you can do | Live |
| --- | --- | --- |
| **Conduit Shop** | Discover independent merchants, browse signed listings, place orders, and manage a device-local wallet | [shop.conduit.market](https://shop.conduit.market) |
| **Conduit Sell** | Publish listings, manage orders and fulfillment, and message shoppers | [sell.conduit.market](https://sell.conduit.market) |

## Built on open protocols

- **Listings:** [NIP-99](https://github.com/nostr-protocol/nips/blob/master/99.md) plus the [Open Markets working specification](https://github.com/OpenMarketsFoundation/specification) for `kind:30402` commerce events.
- **Identity:** external [NIP-07](https://github.com/nostr-protocol/nips/blob/master/07.md) browser or [NIP-46](https://github.com/nostr-protocol/nips/blob/master/46.md) remote signers.
- **Private orders and messages:** [NIP-17](https://github.com/nostr-protocol/nips/blob/master/17.md) with NIP-44 encryption and NIP-59 gift wraps.
- **Payments:** non-custodial Lightning, including optional [NIP-47](https://github.com/nostr-protocol/nips/blob/master/47.md) connected-wallet and [NIP-57](https://github.com/nostr-protocol/nips/blob/master/57.md) zap paths when supported.

See the [client protocol inventory](https://github.com/Conduit-BTC/conduit-mono/blob/main/docs/PROTOCOLS.md) for app-by-app use, implementation links, and current limits. Open Markets is a working specification, distinct from an accepted NIP; the earlier GammaMarkets work is part of its history.

## Contribute

Browse the [client source and contributor guide](https://github.com/Conduit-BTC/conduit-mono), or [report a client issue](https://github.com/Conduit-BTC/conduit-mono/issues). The client code is MIT-licensed; Conduit names and marks remain reserved.

[conduit.market](https://conduit.market) · [Nostr profile](https://njump.me/nprofile1qqsfmys8030rttmk77cumprnsqqt0whmg0fqkz3xcx8798ag8rf8z3sad6jak)
