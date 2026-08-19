# FullCircleMUD

> *A living world that remembers everything.*

FullCircleMUD is an old-school text-based multiplayer
game — a MUD in the tradition of the 1990s classics —
rebuilt from the ground up with a modern twist:
true ownership on the blockchain.

Gold and resources are issued currencies on the XRP
Ledger. Crafted items are NFTs. Trade with other
players, export to your own wallet, or keep
adventuring. When you log off, your items don't
disappear into a company database. They persist
on the ledger. Yours.

## Repositories

### The game

| Repository | Description |
|---|---|
| [game](https://github.com/fullcirclemud/game) | Game server — Evennia/Django, combat, economy, quests, AI NPCs |
| [fcm-umbrella](https://github.com/fullcirclemud/fcm-umbrella) | Development workspace — system design docs and the shared tooling that spans every FCM repo |
| [temp-website](https://github.com/fullcirclemud/temp-website) | Holding site for fcmud.world during pre-alpha — Astro, static output |

### Evennia libraries

Reusable extensions to [Evennia](https://www.evennia.com/), written for
FullCircleMUD but not tied to it. Each library ships with its own test data.

| Repository | Description |
|---|---|
| [evennia-shards](https://github.com/fullcirclemud/evennia-shards) | Split deployment and horizontal sharding for Evennia, selected by config alone |
| [evennia-world-builder](https://github.com/fullcirclemud/evennia-world-builder) | YAML-driven world building for Evennia |
| [evennia-world-builder-test-yaml](https://github.com/fullcirclemud/evennia-world-builder-test-yaml) | Test YAML for the world-builder library |
| [evennia-mob-spawner](https://github.com/fullcirclemud/evennia-mob-spawner) | Declarative YAML mob spawn system for Evennia |
| [evennia-mob-spawner-test-yaml](https://github.com/fullcirclemud/evennia-mob-spawner-test-yaml) | Test spawn YAML for the mob-spawner library |
| [evennia-mob-spawner-test-world](https://github.com/fullcirclemud/evennia-mob-spawner-test-world) | Test world for the mob-spawner library |
| [evennia-yaml-reader](https://github.com/fullcirclemud/evennia-yaml-reader) | YAML reader with GitHub and local implementations, used by the libraries above |

### Blockchain services

| Repository | Description |
|---|---|
| [nft_api](https://github.com/fullcirclemud/nft_api) | NFT metadata API — XLS-24d compliant metadata service for XRPL marketplaces |
| [cosigner](https://github.com/fullcirclemud/cosigner) | XRPL co-signing service — multisig transaction validation and co-signing |

### World and reports

| Repository | Description |
|---|---|
| [lore](https://github.com/fullcirclemud/lore) | World lore — YAML knowledge base for NPC intelligence |
| [design](https://github.com/fullcirclemud/design) | Design documents — economy models, combat architecture, world structure |
| [transparency](https://github.com/fullcirclemud/transparency) | Game economy reports and compliance framework |

## Play

**https://fcmud.world**

FullCircleMUD is in pre-alpha development.
Join the community to follow progress and get
early access when alpha opens.

## Source Available

FullCircleMUD source code is publicly available under
the [Business Source License 1.1](https://github.com/fullcirclemud/game/blob/main/LICENSE).
On 2030-03-31, the licence converts to AGPL-3.0.

## Transparency

FullCircleMUD publishes periodic game economy reports
covering gold circulation, player activity, and
operating expenses. We think players deserve to know
how the game economy is managed.

Reports are published at
[github.com/fullcirclemud/transparency](https://github.com/fullcirclemud/transparency)

## Discord

**https://discord.gg/j8b5GkysM3**

---

*Built with [XRP Ledger](https://xrpl.org) —
fast, low-cost, and decentralised.*
