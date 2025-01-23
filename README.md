<div align="center">
    <img src="./.images/ink-logo-glow.svg" alt="ink!" height="136" />
<h1 align="center">
    A curated list of awesome projects for Polkadot's ink!.
</h1>

> <img src="./.images/ink-squid.svg" alt="Squink, the ink! mascot" align="left" height="60" />
> ink! is a domain-specific language for Rust to write smart contracts for blockchains in the Substrate, Polkadot, and Kusama ecosystem. ink! smart contracts are compiled to WebAssembly.

<br/>

[ink! Repository](https://github.com/use-ink/ink)&nbsp;&nbsp;•&nbsp;&nbsp;
[Guided Tutorial for Beginners](https://use.ink/getting-started/setup)&nbsp;&nbsp;•&nbsp;&nbsp;
[ink! Documentation Portal](https://use.ink)

</div>

<br/>

## 😍 Networks where you can deploy ink! contracts

### Production

- [Shiden](https://shiden.astar.network): Kusama parachain by the Astar team, contains the `pallet-contracts` and thus supports ink! contracts.

### Testnets

- [Rococo Smart Contracts Parachain](https://ink.substrate.io/testnet/): Operated by the developers behind ink! and Substrate's [`pallet-contracts`](https://github.com/use-ink/substrate/tree/master/frame/contracts).
- [Shibuya](https://docs.astar.network/docs/build/builder-guides/xvm_wasm/manage_psp22_asset): Testnet parachain by [Astar](https://astar.network/), connected to a custom relaychain also maintained by Astar.
- [Phala](https://polkadot.js.org/apps/?rpc=wss%3A%2F%2Fpoc5.phala.network%2Fws#/explorer): Further documentation can be found [here](https://wiki.phala.network/en-us/build/developer/fat-contract-tutorial/).
- [Aleph Zero](https://alephzero.org/blog/aleph-zero-smart-contracts-testnet/): Support for ink! smart contracts on their testnet.
- [peaq network](https://www.peaq.network/agung-testnet): ink! smart contracts are live on their testnet.
- [t3rn](https://www.t3rn.io/): Their testnet is called t0rn, the faucet can be found [here](https://faucet.t0rn.io).
- [Pendulum](https://polkadot.js.org/apps/?rpc=wss%3A%2F%2Frpc-foucoco.pendulumchain.tech#/extrinsics): The testnet is called Foucoco, there is no faucet currently.

## :trophy: DApps

- [Prosopo](https://www.prosopo.io/): Human verification on the blockchain, has a dapp example which is written in ink!: https://github.com/prosopo-io/dapp-example
- [Showcase dApps](https://github.com/AstarNetwork/wasm-showcase-dapps): Collection of production ready dApps (contracts + UI) ‒ Uniswap v2, Farming, NFT, …
- [INK!athon](https://inkathon.xyz/) - Full-stack dApp boilerplate with ink! smart contracts and a React frontend using the [useInkathon](https://github.com/scio-labs/use-inkathon) hooks library maintained by [Scio Labs](https://scio.xyz).

## 🛠️ Libraries & Standards

- [OpenBrush](https://openbrush.io/): OpenBrush is a library for smart contract development with ink!.
- [PSP-22](https://github.com/w3f/PSPs/blob/master/PSPs/psp-22.md): Fungible Token Standard for Substrate's `contracts` pallet.
- [py-substrate-interface](https://github.com/polkascan/py-substrate-interface/#ink-contract-interfacing): Library by Polkascan to interact with ink! contracts from Python.
- [hashes](https://github.com/RustCrypto/hashes): Collection of cryptographic hash functions written in pure Rust. (`no_std` needs to be enabled).
- [data-encoding](https://github.com/ia0/data-encoding): Efficient and customizable data-encoding functions in Rust. (`no_std` needs to be enabled).
- [`useInkathon`](https://github.com/scio-labs/use-inkathon) - Typesafe React Hooks library abstracting functionality by polkadot.js for working with Substrate-based networks and ink! smart contracts maintained by [Scio Labs](https://scio.xyz).
- [DRink!](https://github.com/Cardinal-Cryptography/drink/) - Library for light, chainless local ink! development. Equipped with a friendly TUI.
- [ink-wrapper](https://github.com/Cardinal-Cryptography/ink-wrapper/) - Tool generating typed wrappers for calling contracts through node's API.
- [ink! Analyzer](https://github.com/ink-analyzer) - A collection of modular and reusable libraries and tools for semantic analysis of ink! smart contract code.

## 🏦 DeFi

- [Panorama Swap](https://github.com/RottenKiwi/Panorama-Swap-INK-SC)
- [Build an AMM on Polkadot using ink!](https://learn.figment.io/tutorials/build-polkadot-amm-using-ink)

## 👾 Gaming

- [Open Emoji Battler](https://github.com/OpenEmojiBattler/open-emoji-battler/tree/main/front/src): Open Emoji Battler is a decentralized blockchain game, owned by the community, running on-chain. Deployed on Astar tesnet.

## 🧭 Block Explorers

- [Sirato Substrate](https://github.com/web3labs/epirus-substrate): Blockchain explorer for Substrate chains with a focus on the contracts pallet and ink!. There's a [public development instance](https://substrate.sirato.xyz/) connected to Rococo Contracts.

## 💰 Grant Initiatives

- [ink!ubator](https://use.ink/ubator/) - a Polkadot Treasury funded initiative for builders, businesses, and auditors working with ink!.

## Privacy

## Migration Guides

- [CosmWasm to ink! — Beyond the Cosmos 🌌](https://medium.com/@RoloiMoney/cosmwasm-to-ink-beyond-the-cosmos-e4920604f9cb)

## 🙌 Community Badges

### Normal Design

[![Built with ink!](.images/badge.svg)](https://github.com/use-ink/ink)

```markdown
[![Built with ink!](https://raw.githubusercontent.com/use-ink/ink/master/.images/badge.svg)](https://github.com/use-ink/ink)
```

### Flat Design

[![Built with ink!](.images/badge_flat.svg)](https://github.com/use-ink/ink)

```markdown
[![Built with ink!](https://raw.githubusercontent.com/use-ink/ink/master/.images/badge_flat.svg)](https://github.com/use-ink/ink)
```
