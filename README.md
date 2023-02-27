# aWASoMe [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
![wasm-7d7f59e77aa402099ee74b8771d1134f](https://user-images.githubusercontent.com/34627453/221525327-1a3bad79-3093-4b2b-9e18-4ae87743e09b.png)

An aWASoMe list of all things related to WASM contract development.


## Contract language
### ink!
- `ink!` [Github](https://github.com/paritytech/ink)
- `ink!` [Intro](https://paritytech.github.io/ink/)
- `ink!` [Official Documentation](https://use.ink/)
- `ink!` [Rust doc](https://docs.rs/ink/4.0.0/ink/)
- `awesome ink!` [Github](https://github.com/paritytech/awesome-ink) - A curated list of awesome projects for Parity's ink!
- `ink! examples`
  - Parity [examples](https://github.com/paritytech/ink-examples)
  - Openbrush [examples](https://github.com/727-Ventures/openbrush-contracts/tree/main/examples)
  - Astar dapps [examples](https://github.com/AstarNetwork/wasm-showcase-dapps)
  - Swanky-dapps [examples](https://github.com/orgs/swanky-dapps/repositories)
- `Astar ink!` [Docs](https://docs.astar.network/docs/build/wasm/)
### ask!
- `AssemblyScript` [Github](https://github.com/LimeChain/as-scale-codec) [Example](https://docs.astar.network/docs/build/wasm/ask_contracts)

## Smart Contract compilers
- `cargo-contract` [Github](https://github.com/paritytech/cargo-contract/) - ink! compiler, uses Rustc compiler
- `solang` [Github](https://github.com/hyperledger-labs/solang) - compiles Solidity smart contracts to WASM

## Contract Development
- `Dev Container` [Docs](https://github.com/AstarNetwork/swanky-dev-container) - develop your project inside a preconfigured container with all prerequisites met and correct dependencies installed
- `Swanky-cli` [npm](https://www.npmjs.com/package/@astar-network/swanky-cli) [Github](https://github.com/AstarNetwork/swanky-cli) [Docs](https://docs.astar.network/docs/build/wasm/swanky) - all-in-one tool for Wasm smart contract developers
- `Openbrush Library` [Github](https://github.com/727-Ventures/openbrush-contracts), [Docs](https://docs.openbrush.io/) - OpenBrush is a library of ink! contracts, like OpenZeppelin
- `PSP` [Github](https://github.com/w3f/PSPs) - Polkadot Standards Proposals for ink! contracts by W3F

## dApps
- `Swanky-dapps` [examples](https://github.com/orgs/swanky-dapps/repositories)
- `use.ink dapp examples` [Docs](https://use.ink/examples/dapps)

## Contract Interaction
- `polkadot{.js}` [website](https://polkadot.js.org/apps/#/explorer), [Docs](https://polkadot.js.org/docs/api/) - an App to interact with Substrate node and pallet-contracts
- `Contracts-UI` [Github](https://github.com/paritytech/contracts-ui), [App](https://contracts-ui.substrate.io/) - simple interaction with Substrate contracts
- `@polkadot/api-contract` [Github](https://github.com/polkadot-js/api) [Docs](https://polkadot.js.org/docs/api-contract) - thin layer on-top of the available API transactions to manage Substrate contracts 
- `Typechain` [Github](https://github.com/727-Ventures/typechain-polkadot) - Interact with contracts using TS or JS
- `Sidecar` [Github](https://github.com/paritytech/substrate-api-sidecar) - REST service that runs alongside Substrate nodes
- `SubXt` [Github](https://github.com/paritytech/subxt) - A Rust library to **SUB**mit e**XT**rinsics to a substrate node via RPC.

### Wallets
- `polkadot{.js}` [website](https://polkadot.js.org/extension/) - a browser extension
- `Subwallet` - [Docs](https://docs.subwallet.app/) - a browser extension with the viewer for PSP34 NFTs 
- `Talisman` [website](https://talisman.xyz/#) - a browser extension

## Test nodes
- `swanky-node` [Github](https://github.com/AstarNetwork/swanky-node) - standalone node supporting pallet-contracts, instant seal and manual seal
- `substrate-contracts-node` [Github](https://github.com/paritytech/substrate-contracts-node) - standalone node supporting pallet-contracts
- `Shibuya parachain` [Network Details](https://docs.astar.network/docs/build/environment/endpoints), [Faucet](https://portal.astar.network/#/assets) - testnet (Parachain on test Relay chain) maintained by Astar
- `Contracts on Rococo` [Polkadot.js](https://polkadot.js.org/apps/?rpc=wss%3A%2F%2Frococo-contracts-rpc.polkadot.io#/explorer), [Faucet](https://wiki.polkadot.network/docs/learn-DOT#getting-rococo-tokens) - testnet (Parachain on test Rococo Relay chain) maintained by Parity

## Support
- [Substrate StackExchange](https://substrate.stackexchange.com/) - ask any smart-contract related question (use tags: ink, contract, smart-contract)
- [Astar Discord](https://discord.gg/Z3nC9U4) - connect with Astar WASM team (Use **Developer Support** channel) 
- [Brushfam Element](https://matrix.to/#/!utTuYglskDvqRRMQta:matrix.org?via=matrix.org&via=t2bot.io&via=matrix.parity.io) - Matrix/Element room, support for developing in ink! and OpenBrush
- [Astar WASM Docs](https://docs.astar.network/docs/build/wasm/) - WASM dev related Docs by Astar


## Learning
- [From Zero to ink! Hero](https://docs.astar.network/docs/build/wasm/from-zero-to-ink-hero/) - ink! tutorials: Flipper, NFT, Uniswap v2
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
- NFT minting dApp, [Github](https://github.com/Maar-io/ink-mint-dapp), [Youtube](https://www.youtube.com/watch?v=YnmBotet6_M)

## Templates
- [Substrate-Front-End](https://github.com/substrate-developer-hub/substrate-front-end-template) - Polkadot-JS API and [React](https://reactjs.org/) app to build front-ends for Substrate-based chains.
