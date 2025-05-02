<!-- [中文](https://github.com/ArweaveOasis/Arweave-AO-Dev-Learning/blob/main/README_CN.md) / English -->


# Awesome Arweave & AO [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
<div>
  <p>
    All-in-One dev resources and tutorials.
  </p>
  <p>
    <a href="https://x.com/ArweaveEco"><img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/ArweaveEco?label=ArweaveEco%20Follow"></a>
    <a href="https://x.com/aoTheComputer"><img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/aoTheComputer?label=AO%20Follow"></a>
    <a href="https://x.com/ArweaveOasis"><img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/ArweaveOasis?label=ArweaveOasis%20Follow"></a>
  </p>
  <img src="Doc/Image/Dev learning.jpg" style="margin: 0 auto 40px;" />
</div>

[![protocol.land](https://arweave.net/eZp8gOeR8Yl_cyH9jJToaCrt2He1PHr0pR4o-mHbEcY)](https://protocol.land/#/repository/35c3e55a-711d-4b51-a972-b336a6b11814)

## Overview

Welcome to the all-in-one hub for developers in the Arweave and AO ecosystem. This platform provides the tools, resources, and knowledge to help you build dApps, exploring data permanence, or leveraging Actor-Oriented design. It can be your gateway to Arweave and AO. Dive in and start building!   

[Arweave](https://arweave.org/) - A decentralized permanent storage network. 

[AO](https://ao.arweave.dev/) - A decentralized computing platform enabling hyper-parallel processes to interact with Arweave as the data layer.

[HyperBEAM](https://github.com/permaweb/HyperBEAM) - A client implementation of the AO-Core protocol, written in Erlang.

We will classify development technical documentation resources in the following index by treating Arweave and AO as a unified infrastructure.


## 🧑🏻‍💻 Development Resources
### Arweave core resources
- [✨ Arweave JS](https://github.com/ArweaveTeam/arweave-js) - Official SDK for interacting with Arweave 
- [🌟 Arweave Docs](https://docs.arweave.org/developers/arweave-node-server/http-api) - Official resources for building, **mining**, and exploring data permanence on Arweave.

### AO core resources
- [AO Cookbook](https://cookbook_ao.g8way.io/) - Getting started guide and tutorials for AO
- [AOS CLI](https://github.com/permaweb/ao/blob/main/dev-cli/README.md) -  Command line utility for interacting with applications on AO 
- [ao Connect](https://github.com/permaweb/ao/tree/main/connect) - Official SDK for interacting with AO from the Web/JS

### Data uploading
- [✨ Arweave JS](https://github.com/ArweaveTeam/arweave-js) - Official SDK for uploading directly to Arweave with native AR token
- [Turbo SDK](https://github.com/ardriveapp/turbo-sdk) - Instant upload to Arweave with crypto/fiat options
- [ArFleet JS](https://github.com/aoacc/arfleet-js) - Temporary file storage SDK, built on top of AO

### dApp Templates/Starter Kits
- [create-ao-dapp](https://github.com/Autonomous-Finance/ao-starter-kit) - Starter kit for developing an AO-powered dApp
- [teal-ao-starter](https://github.com/Autonomous-Finance/teal-ao-starter) - AO contract development with teal for strong typing.
- [create-ao-contract](https://github.com/pawanpaudel93/create-ao-contract) - CLI tool for scaffolding AO contracts with testing and deployment setup.

### dApp deployment
- [Permaweb deploy](https://github.com/permaweb/permaweb-deploy) - Command line script to upload a web frontend to Arweave with support for updating ArNS[1] domain name
- [Arlink](https://arlink.ar-io.dev/) - DApp deployment with visual graphical interface
- [AOForm](https://github.com/Autonomous-Finance/aoform) - Automated deployment of AO contracts in a declarative style
- [ao-deploy](https://github.com/pawanpaudel93/ao-deploy) - CLI tool and JavaScript library for deploying AO contracts
- [Ewigkeit](https://github.com/kay-is/ewigkeit) - DApp deployment and management with ArNS and GUI
- [DragonDeploy](https://dragondeploy.xyz/) - Upload website or app to the Permaweb

### Database

- [AOS Sqlite module](https://github.com/permaweb/aos-sqlite) - SQLite database embedded in AO contracts
- [WeaveDB](https://weavedb.dev/) - Cross-chain database backed by Arweave

### Financial

- [Token contract](https://github.com/permaweb/aos/blob/main/blueprints/token.lua) - Standard contract for tokens on AO
- [FusionFi](https://ffp.gitbook.io/fusionfi) - FusionFi is a unified financial protocol on permaweb(ao)

### Network inspection tools

- [AO Link](https://www.ao.link/) - Live AO explorer and inspection tool
- [ViewBlock](https://viewblock.io/) - Arweave block explorer
- [DataOS](https://stats.dataos.so/arweave?) - A protocol leveraging it for computing power and Arweave for data storage
- [Arweave Fees](https://ar-fees.arweave.dev/) - The calculator provides the approximate real-time cost to store data on Arweave
- [SmartWeaver](https://smartweaver.land) - An Arweave and AO transaction explorer platform.
    
### Gaming 

- [Reality Protocol](https://github.com/elliotsayes/Reality/blob/main/docs/AgentGuide.md#static-agents) - Toolkit for user created interconnected metaverse

### Coding tools

- [VS Code AO](https://cookbook_ao.g8way.io/references/editor-setup.html) - Plugins and configurations for AO development in VS Code
- [BetterIDEa](https://ide.betteridea.dev/) - Web-based Code editor with native AO integrations
- [Protocol.Land](https://github.com/labscommunity/protocol-land) - Git hosting and Github mirroring on Arweave
- [WAO](https://github.com/weavedb/wao) - In-memory AO testing framework

### Oracles/Bridges

- [0rbit](https://docs.0rbit.co/) - Oracle for retrieving Web2 data into AO
    

### AO backend technologies

- [aos](https://github.com/permaweb/aos) - Standard module for developing on AO
- [ao module loader](https://github.com/permaweb/ao/blob/main/loader/README.md) - Package for running an ao contracts

### Infrastructure 

- [Arweave Server](https://github.com/ArweaveTeam/arweave) - Official implementation of an Arweave node
- [AO Servers](https://github.com/permaweb/ao/tree/main/servers) - Official implementation of the various AO nodes (CU, MU, SU, UR)

### Protocols

- [ArFS](https://github.com/ardriveapp/ardrive-web/blob/dev/docs/ArweaveFS.md) - ArweaveFS is a data model designed to emulate file systems on Arweave
- [ArNS](https://docs.ar.io/arns/#overview) - ArNS is a censorship-resistant naming system stored on Arweave

### Arweave Protocols

- [Arweave Network Standard - ANS](https://github.com/ArweaveTeam/arweave-standards/tree/master/ans) - Standards for anything that is built on top the Arweave Network.
- [SmartWeave](https://github.com/ArweaveTeam/SmartWeave) - Defunct contract standard, the predecessor to AO

### Builder communities

- [Weavers](https://www.weaversofficial.com/) - A community of devs + creatives which focus on hackathone 
- [Arweave Hub](https://arweavehub.com/) - The place to find events happening within the Arweave ecosystem
- [Arweave Oasis](https://arweaveoasis.com) - A community for Asian devs
- [PermaDAO](https://permadao.com/permadao/PermaDAO-76e627a9044548498d02b8fe4e962720) - A collaborative DAO within the Arweave ecosystem
- [ao Builders](https://twitter.com/ao_builders) - Community by Warp.cc


## 📙 Tutorials
- Arweave 101 (Produced by [Kay](https://x.com/K4y1s))
  - [Intro to Arweave](https://academy.developerdao.com/tracks/arweave-101/1)
  - [Accessing Data on Arweave](https://academy.developerdao.com/tracks/arweave-101/2)
  - [Storing Data on Arweave](https://academy.developerdao.com/tracks/arweave-101/3)
  - [Building a Static Website on Arweave](https://academy.developerdao.com/tracks/arweave-101/4)
  - [Building a App on Arweave](https://academy.developerdao.com/tracks/arweave-101/5)
- [Connecting to the Permaweb](https://dev.to/fllstck/connecting-to-the-permaweb-ek5)
- [ao Begin: an interactive tutorial](https://cookbook_ao.g8way.io/tutorials/begin/index.html)
- [Adding a CU to Your Arweave Gateway](https://dev.to/fllstck/adding-a-cu-to-your-arweave-gateway-3aj1)

## 📱 Products (The usecase you can follow)
### Wallet
- [ArConnect](https://docs.arconnect.io/) - Chrome extension and native mobile Arweave & AO wallet
- [AOWebWallet](https://aoww.net/) - Web based AO wallet and AO contract interface
- [Arweave.app](https://arweave.app/) -  Web based Arweave wallet
        
### Financial
- [Botega](https://botega.arweave.dev/#/swap) - Agent-powered token exchange platform
- [CoinMaker](https://coin.ar.io/) - AO Token Launchpad
- [Permaswap](https://github.com/permadao/permaswap) - Decentralised exchange for Arweave and AO and Ethereum bridge
    - Uses: [FusionFi](https://ffp.gitbook.io/fusionfi)
- [AOX](https://aox.xyz/#/) - Bridge for AR tokens to the AO network
        
### Data Storage
- [ArDrive](https://ardrive.io/) - Web and mobile-native interface for Arweave as a Filesystem
   - Uses: ArFS

### Gaming
- [Llama land](https://llamaland.g8way.io/#/) - AI powered metaverse themed to Llamas
    - Uses: Reality Protocol
- [Permadumdum](https://x.com/permadumdum) - Pet game using the Dumdum mascot
- [Permaverse](https://dumdum.arweave.dev/) - Full web3 metaverse, gaming hub and launchpad
- [Hangout](https://hangout.aogames.org/) - AI powered life simulator

## Contributors
Contributions welcome and wanted! Read the [contribution guidelines](https://github.com/ArweaveOasis/Arweave-AO-Dev-Learning/blob/main/Doc/Rules.md) first.
Thanks to all the people who have contributed to this project!

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- ALL-CONTRIBUTORS-LIST:END -->
