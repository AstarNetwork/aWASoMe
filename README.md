# aWASoMe [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
> An aWASoMe list of all things related to WASM contract development in the Dotsama community.

![Awesome](mermaid-diagram.svg)

## Contract language
### ink!
- `ink!` [Github](https://github.com/paritytech/ink)
- `ink!` [Intro](https://paritytech.github.io/ink/)
- `ink!` [Official Documentation](https://use.ink/)
- `ink!` [Rust doc](https://paritytech.github.io/ink/ink_lang/)
- `awesome ink!` [Github](https://github.com/paritytech/awesome-ink) - A curated list of awesome projects for Parity's ink!
- `ink! examples`
  - Parity [examples](https://github.com/paritytech/ink/tree/master/examples)
  - Openbrush [examples](https://github.com/Supercolony-net/openbrush-contracts/tree/main/examples)
  - Astar dapps [examples](https://github.com/AstarNetwork/wasm-showcase-dapps)
  - Astar chain extension [examples](https://github.com/AstarNetwork/chain-extension-contracts)
### ask!
- `AssemblyScript` [Github](https://github.com/LimeChain/as-scale-codec) 

## Smart Contract compilers
- `cargo-contract` [Github](https://github.com/paritytech/cargo-contract/) - ink! compiler, uses Rustc compiler
- `solang` [Github](https://github.com/hyperledger-labs/solang) - compiles Solidity smart contracts to WASM

## Contract Development
- `Swanky` [npm](https://www.npmjs.com/package/@astar-network/swanky-cli) - Swanky nmp repository (Github and docs will be published after Beta release)
- `Openbrush Library` [Github](https://github.com/Supercolony-net/openbrush-contracts), [Docs](https://docs.openbrush.io/) - OpenBrush is a library of ink! contracts, like OpenZeppelin
- `PSP` [Github](https://github.com/w3f/PSPs) - Polkadot Standards Proposals for ink! contracts by W3F

## dApps
- `Showcase dApps` [Github](https://github.com/AstarNetwork/wasm-showcase-dapps): Collection of production ready dApps (contracts + UI) - UniswapV2, Farming, NFT, ..

## Contract Interaction
- `polkadot{.js}` [website](https://polkadot.js.org/apps/#/explorer), [Docs](https://polkadot.js.org/docs/api/) - an App to interact with Substrate node and pallet-contracts
- `ContractsUI` [Github](https://github.com/paritytech/contracts-ui), [App](https://paritytech.github.io/canvas-ui/#/instantiate) - simple interaction with Substrate contracts
- `@polkadot/api-contract` [Github](https://github.com/polkadot-js/api) [Docs](https://polkadot.js.org/docs/api-contract) - thin layer on-top of the available API transactions to manage Substrate contracts 
- `Redspot` [Github](https://github.com/patractlabs/redspot) - A Truffle-like toolkit for Substrate node and pallet-contracts
- `Sidecar` [Github](https://github.com/paritytech/substrate-api-sidecar) - REST service that runs alongside Substrate nodes
- `SubXt` [Github](https://github.com/paritytech/subxt) - A Rust library to **SUB**mit e**XT**rinsics to a substrate node via RPC.

### Wallets
- `polkadot{.js}` [website](https://polkadot.js.org/extension/) - a browser extension
- `Talisman` [website](https://talisman.xyz/#) - a browser extension

## Test nodes
- `swanky-node` [Github](https://github.com/AstarNetwork/swanky-node) - standalone node supporting pallet-contracts, instant seal and manual seal
- `substrate-contracts-node` [Github](https://github.com/paritytech/substrate-contracts-node) - standalone node supporting pallet-contracts
- `Shibuya parachain` [Network Details](https://docs.astar.network/integration/network-details), [Faucet](https://portal.astar.network/#/assets) - testnet (Parachain on test Relay chain) maintained by Astar
- `Contracts on Rococo` [Polkadot.js](https://polkadot.js.org/apps/?rpc=wss%3A%2F%2Frococo-contracts-rpc.polkadot.io#/explorer), [Faucet](https://wiki.polkadot.network/docs/learn-DOT#getting-rococo-tokens) - testnet (Parachain on test Rococo Relay chain) maintained by Parity

## Support
- [Substrate StackExchange](https://substrate.stackexchange.com/) - ask any smart-contract related question (use tags: ink, contract, smart-contract)
- [Astar Discord](https://discord.gg/Z3nC9U4) - connect with Astar WASM team (Use **Developer Support** channel) 
- [Openbrush Element](https://matrix.to/#/!utTuYglskDvqRRMQta:matrix.org?via=matrix.org&via=t2bot.io&via=matrix.parity.io) - Matrix/Element room, support for developing in ink! and OpenBrush
- [Astar WASM Docs](https://docs.astar.network/wasm-smart-contracts/smart-contract-development) - WASM dev related Docs by Astar


## Learning
- [Substrate ink! Tutorial](https://docs.substrate.io/tutorials/v3/ink-workshop/pt1/) - Guided Tutorial for Beginners  
- [Introduction to ink!](https://www.crowdcast.io/e/na-hackathon/13) - ink! workshop by Hernando (Parity)
- [OpenBrush: a library to build ink! smart contracts](https://www.youtube.com/watch?v=I5OFGNVvzOc&list=PLp0_ueXY_enXRfoaW7sTudeQH10yDvFOS&index=10) - Substrate Seminar
- [Building DEX Smart Contract in ink!](https://www.crowdcast.io/e/fundrasing-workshop) - Simple DEX implementation in ink by Pierre Ossun
- [Build an AMM on Polkadot using Ink!](https://learn.figment.io/tutorials/build-polkadot-amm-using-ink#how-to-interact-with-polkadot-js) - Figment tutorial
- [A BTC price bot with Phala's ink!](https://github.com/Phala-Network/fat-contract-workshop) - A Substrate seminar on Phala's Fat (PhaT) Contract [Youtube](https://www.youtube.com/watch?v=aZGj4FhkY6A&t=1566s)
- [Sub0 Developer Conference](https://sub0.parity.io/) - Semiannual, online and in-person for all
  things Substrate.

## dApp development
- [Subscan](https://www.subscan.io/) - Multi-network explorer for Substrate-based chains.
- [Subsquid](https://subsquid.io) - An indexing framework (SDK + infrastructure) for WASM
- [DIA Oracle](https://docs.astar.network/wasm-smart-contracts/smart-contract-development) - Oracle for WASM contracts on Astar Network

## Templates
- [Substrate-Front-End](https://github.com/substrate-developer-hub/substrate-front-end-template) - Polkadot-JS API and [React](https://reactjs.org/) app to build front-ends for Substrate-based chains.
