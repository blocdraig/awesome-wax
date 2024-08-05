# Awesome WAX [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

👑 A curated list of awesome resources related to the <a href='https://wax.io/'>WAX</a> Blockchain.

## Contents

- [Awesome WAX ](#awesome-wax-)
  - [Contents](#contents)
  - [Official Resources](#official-resources)
  - [Wallets](#wallets)
  - [Blockchain Explorers](#blockchain-explorers)
  - [Learning Resources](#learning-resources)
  - [Developer Resources](#developer-resources)
    - [Docs](#docs)
    - [Guides](#guides)
    - [Tutorials](#tutorials)
    - [CLI](#cli)
    - [Languages](#languages)
      - [JavaScript](#javascript)
      - [C#](#c)
      - [Go](#go)
      - [Python](#python)
      - [Rust](#rust)
      - [Java](#java)
      - [PHP](#php)
      - [Swift](#swift)
      - [Dart](#dart)
    - [IDEs](#ides)
      - [VSCode](#vscode)
    - [Other Development Tools](#other-development-tools)
      - [Smart Contracts](#smart-contracts)
      - [Testing](#testing)
  - [Security Auditing Services](#security-auditing-services)
  - [Nodes \& API Operation](#nodes--api-operation)
    - [Commercial Services](#commercial-services)
  - [DeFi Platforms](#defi-platforms)
  - [Blockchain Bridges](#blockchain-bridges)
  - [Oracles](#oracles)
  - [Name Services](#name-services)
  - [Metrics and Analytics Services](#metrics-and-analytics-services)
  - [NFT Marketplaces](#nft-marketplaces)
  - [Community Resources](#community-resources)
    - [Creator Tools](#creator-tools)
    - [Directories](#directories)

## Official Resources

> Official resources for WAX.

- [WAX](https://wax.io/) - Official website.
- [WAX Developer Portal](https://developer.wax.io/) - Official WAX developer portal.
- [WAX Discord](https://discord.com/invite/dJtPetMdfb) - Official WAX Discord server.
- [WAX Telegram](https://t.me/wax_io) - Official WAX Telegram channel.
- [WAX Labs](https://labs.wax.io/) - WAX Labs funds projects that have a clear and measurable impact on the WAX ecosystem.
- [WAX Office of Inspector General](https://oig.wax.io/) - A neutral third-party role designed to evaluate WAX Guild Candidates contributions to the ecosystem and providing ongoing transparency for the community.

## Wallets

> List of wallet providers for WAX. Please note that this list is not exhaustive and is not an endorsement of any wallet provider.

- [Cloud Wallet](https://www.mycloudwallet.com) - The easiest way to create, use, and manage an account on WAX.
- [Anchor Wallet](https://www.greymass.com/anchor) - Security and privacy focused open-source digital wallet for all Antelope-based networks.
- [Wombat](https://www.wombat.app/the-app) - Multi-chain wallet that supports WAX.

## Blockchain Explorers

> List of blockchain explorers for WAX. Used to view transactions, accounts, assets, etc.

- [waxblock.io](https://waxblock.io/) - The Official WAX Blockchain Explorer.
- [wax.eosauthority.com](https://wax.eosauthority.com/) - WAX Block Explorer by EOS Authority.
- [wax.eosq.eosnation.io](https://wax.eosq.eosnation.io/) - eosq: High-Precision Block Explorer.
- [bdata.one](https://bdata.one/) - Blockchain data about accounts and tokens for several Antelope chains.

## Learning Resources

> List of learning resources for WAX. Includes courses, tutorials, and other resources.

- [WAX Academy](https://academy.anyo.io/courses/introduction-to-wax/) - A free course covering many aspect of the WAX Blockchain.

## Developer Resources

### Docs

- [Chain API Documentation](https://docs.eosnetwork.com/apis/leap/latest/chain.api)
- [AtomicAssets API Documentation](https://wax.api.atomicassets.io/docs/)
- [Hyperion History API Documentation](https://hyperion.docs.eosrio.io/#for-developers)
- [WAX Unity SDK Documentation](https://liquiidio.gitbook.io/unity-plugin-suite)
- [WAX Testnet Information](https://waxsweden.org/testnet/)
- [WAX Testnet Public Endpoints](https://validate.eosnation.io/waxtest/reports/endpoints.html)
- [WAX Mainnet Public Endpoints](https://validate.eosnation.io/wax/reports/endpoints.html)

### Guides

- [Antelope Smart Contract Developer's Handbook](https://cc32d9.gitbook.io/antelope-smart-contract-developers-handbook/)
- [Wax Smart Contract Development Guide](https://waxdao.gitbook.io/wax-smart-contract-development-guide)

### Tutorials

- [Accepting NFT Deposits in a WAX Smart Contract](https://onblock.dev/accepting-nft-deposits-in-a-smart-contract)

### CLI

- [cleos](https://docs.eosnetwork.com/manuals/leap/latest/cleos/) - cleos is a command line tool that interfaces with the WAX RPC API. Developers can also use cleos to deploy and test EOSIO smart contracts.

### Languages

> Awesome client libraries, tools, and community utilities sorted by the language of implementation.

#### JavaScript

- [WharfKit](https://github.com/wharfkit) ([website](https://wharfkit.com/)) - Modular SDK for Antelope Web Apps. Wharf provides a fast and flexible way to build web3 projects on WAX.
- [eosio-statereceiver](https://github.com/worldwide-asset-exchange/eosio-statereceiver) - Antelope state-history websocket client.
- [antelope-ship-reader](https://github.com/blockmatic/antelope-ship-reader) - Reactive Antelope state-history websocket client.

#### C#

- [WAX Unity SDK](http://go.wax.io/Unity) - A collection of C# packages designed for Unity, most will also work standalone.

#### Go

- [go-eosio](https://github.com/greymass/go-eosio) - Fast Antelope primitives for Go.
- [antelope-ship-client](https://github.com/eosswedenorg-go/antelope-ship-client) - Client Implementation of Antelope state-history websocket in go.

#### Python

- [pyntelope](https://github.com/FACINGS/pyntelope) - Antelope API library for Python 3.
- [antelopy](https://github.com/stuckatsixpm/antelopy) - Python helper for Antelope transaction serialization.
- [py-leap](https://github.com/guilledk/py-leap) - Python Antelope SDK.

#### Rust

- [eosio-rust](https://github.com/sagan-software/eosio-rust) - Antelope API library for Rust.

#### Java

- [mandel-java](https://github.com/eosnetworkfoundation/mandel-java) - Antelope API library for Java.
- [antelope-java-sdk](https://github.com/mcicu/antelope-java-sdk) - Updated Antelope API library for Java.

#### PHP

- [php-eos-rpc-sdk](https://github.com/alienzin/php-eos-rpc-sdk) - Antelope API library for PHP.

#### Swift

- [mandel-swift](https://github.com/eosnetworkfoundation/mandel-swift) - Antelope API library for Swift.
- [swift-eosio](https://github.com/greymass/swift-eosio) - Alternative Antelope API library for Swift.

#### Dart

- [eosdart](https://github.com/primes-network/eosdart) - Antelope API library for Dart.

### IDEs

> Awesome client libraries, tools, community plugins and integrations for IDEs.

#### VSCode

- [Ultra.io Smart Contract Toolkit](https://marketplace.visualstudio.com/items?itemName=ultraio.ultra-cpp) - Build smart contracts, and get rid of those annoying squigglies while working with smart contracts on Antelope based chains. This is your all in one toolkit to do everything Antelope in the blink of an eye.

### Other Development Tools

> Awesome testing, debugging, deployment, monitoring and other tools for WAX.

#### Smart Contracts

- [eosio.token](https://github.com/worldwide-asset-exchange/wax-system-contracts/tree/develop/contracts/eosio.token) - The standard token contract used on WAX.

#### Testing

- [Zeus](https://docs.liquidapps.io/liquidapps-documentation/working-with-zeus-sdk/overview) - Zeus makes Antelope smart contract unit testing easy with the NodeJS mocha-chai framework.
- [VeRT](https://github.com/eosnetworkfoundation/vert) - VeRT is a blockchain virtual machine emulator for WASM-based contracts like WAX.
- [Fuckyea](https://github.com/nsjames/fuckyea?tab=readme-ov-file) - Smart contract testing framework built by Nathan James from EOS

## Security Auditing Services

> Companies offering smart contract audits for the WAX ecosystem.

- [Sentnl](https://sentnl.io/) - Leading blockchain security auditor who are also a WAX block producer.
- [CryptoLions](https://cryptolions.io/) - WAX block producer that offers smart contract security audit services.
- [Hacken](https://hacken.io/services/blockchain-security/smart-contract-security-audit/) - Smart Contract Audit Services.
- [BlockSec](https://blocksec.com/) - Full-Stack Blockchain Security Service Provider.

## Nodes & API Operation

> Resources and guides for running Blockchain, History, or Atomic Assets APIs

- [WAX Technical How To Series](https://medium.com/eosphere/wax-technical-how-to/home) - Guides for running blockchain nodes and APIs by EOSphere
- [Chronicle](https://github.com/EOSChronicleProject/eos-chronicle) - Antelope state history processor.
- [Thalos](https://thalos.waxsweden.org/) - Stream blockchain data from an Antelope SHIP node via Redis.

### Commercial Services

- [WAXGalaxy](https://pro.waxgalaxy.io/) - Metered WAX API access
- [Connect3](https://www.connect3.io/pricing) - Metered WAX API access
- [binfra.one](https://binfra.one/) - WAX Blockchain, History, and Atomic API services.

## DeFi Platforms

> Awesome DeFi platforms and protocols on WAX.

- [Alcor Exchange](https://wax.alcor.exchange/) - All in one DEX. Alcor is a lego of decentralized finance built on multi-chain, and a provider of solutions in one tap.
- [WaxOnEdge](https://waxonedge.app/) - WAX DEX aggregator - the ultimate tool to simplify and optimize your token swaps. Access all the top decentralized exchanges in one place and unlock the best trading paths for maximum returns.
- [Taco Swap](https://swap.tacocrypto.io) - The first community exchange on WAX which allows users to trade and earn in a safe and fun space.
- [A-DEX](https://wax.a-dex.io/) - The A-DEX is a peer-to-peer system designed for exchanging cryptocurrencies on the Antelope(EOSIO) blockchains.

## Blockchain Bridges

> This provides a list of bridges that allow for cross-chain transfers of assets between WAX and other blockchains.

- [Cloud Wallet Bridge](https://bridge.mycloudwallet.com/) - The WAX NFT & Token Bridge

## Oracles

> A list of oracle solutions that allow smart contracts to interact with the real world.

- [DelphiOracle](https://github.com/eostitan/delphioracle) ([contract](https://waxblock.io/account/delphioracle)) - Token pair price oracle, e.g. WAX/USD, WAX/USDT, WAX/BTC, WAX/ETH etc
- [WAX RNG Oracle](https://github.com/worldwide-asset-exchange/wax-orng) - The WAX RNG Native Blockchain Service
- [Alcor TWAP Oracle](https://github.com/alcorexchange/alcor-oracle-price/tree/master) - On chain TWAP (Time Weighted Average Price) oracle built using the same logic as Uniswap V3. Reference: [Uniswap Whitepaper](https://uniswap.org/whitepaper-v3.pdf)

## Name Services

> On WAX addresses are human-readable by default. However, names must be 12 characters unless you go through the Name Bid process. 

- [WAX Name Bids](https://waxblock.io/namebids) - The native service for Premium Name bids.
- [WAX Name Service](https://www.waxnameservice.io/) - Discover Valuable Premium Names on WAX.
- [WaxDAO Name Service](https://names.waxdao.io) - Buy/sell subdomains for Premium Names on WAX.

## Metrics and Analytics Services

> Metrics and analytics services for WAX.

- [WAXMarketCap](https://www.waxmarketcap.com/) - NFT Analytics on the WAX Blockchain.
- [WaxDAO Token Tracker](https://waxdao.io/tokens) - Track price, volume, liquidity and more for various WAX tokens.
- [Validationcore](https://wax.validationcore.io) - Monitoring and stats for WAX Guild infrastructure.

## NFT Marketplaces

- [AtomicHub](https://wax.atomichub.io/) - A one stop solution for creating, trading, buying and selling NFTs on the WAX Blockchain.
- [NFTHive](https://nfthive.io/) - Browse NFT Market offers, Bundles & Auctions. Check your inventory and sell NFTs easily.
- [NeftyBlocks](https://neftyblocks.com/) - A Trade to Earn marketplace for buying, selling and creating digital collectibles.
- [Chain Champs](https://market.chainchamps.com/) - Chain Champs is WAX's first real-time NFT marketplace. See new sales the second they're listed, hunt for the best NFT deals.
- [vIRL Market](https://virl.com/) - A marketplace for gamers and collectors to buy, sell and trade utility-based NFTs and vIRLs™.
- [Droppp](https://droppp.io/) - Funko collectibles on the WAX Blockchain.

## Community Resources

### Creator Tools

- [bountyblok](https://www.bountyblok.io/) - The easiest way to power your Web3 projects for engagement. Launch contests & giveaways, distribute NFTs in a few clicks, gift NFTs with personalized email templates, and access enterprise Web3 APIs for secure blockchain integration.
- [WaxDAO](https://waxdao.io/) - A suite of accessible tools on WAX blockchain. WaxDAO allows creators on WAX to transform their ideas into reality, without needing to learn how to code.
- [Pepper Stake](https://pepperstake.online/) - Create your own staking system. Stake assets & collect reward.
- [LaunchBagz](https://wax.launchbagz.com/) - The first launchpad for the WAX ecosystem.
- [Cerberus](https://cerberus.ledgerwise.io/) - Discord bot that integrates with the WAX Blockchain, features such as NFT ownership verification.

### Directories

- [illusive.gg](https://www.illusive.gg/) - Discover & Play the best Blockchain Games.
- [WaxDapps](https://waxdapps.io/) - WAX Dapps Directory.
- [Waxzilla](https://waxzilla.io/) - Community Builder and Management Tool built on WAX Blockchain!
- [WAX Collection Verification Tool](https://verify.hivebp.io/)
- [A-DEX Assets](https://github.com/A-DEX/assets) - A comprehensive, up-to-date collection of information about Antelope(EOSIO) chains.
