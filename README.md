<p align="center">
  <img src="https://readme-typing-svg.demolab.com/?lines=Hey+there!+I'm+Sameer+%F0%9F%91%8B;Blockchain+Engineer+%7C+Protocol+Development+%7C+Smart+Contracts;Building+Decentralized+Systems+Since+2020&font=Fira+Code&color=36BCF7&center=true&width=600&height=50&duration=4000&pause=1000" alt="Typing SVG" />
</p>

# Hi, I'm Sameer! 👋

Blockchain engineer with 5+ years of experience across Ethereum infrastructure, protocol design, smart contracts, distributed systems, and verifiable compute. I have worked on oracle aggregation, staking and validator incentives, cross-chain attestation, decentralized AI training, and Rust-based execution-layer learning projects. My work sits between Solidity protocol implementation and lower-level protocol engineering: building production EVM systems while moving deeper into client architecture, state execution, testing, and protocol correctness.


## 🚀 Professional Experience (5+ years)

**[Razor Network](https://razor.network)** · Blockchain Developer · July 2020 – Present

Worked across smart contracts, oracle infrastructure, decentralized AI compute, distributed systems, and verification protocol design. Key projects:

**[Razor Network Oracle](https://razor.network)** (Open Source: [oracle-contracts](https://github.com/razor-network/oracle-contracts) · [bridge-proxy](https://github.com/razor-network/bridge-proxy))
- Architected decentralized oracle contracts for data aggregation.
- Optimized oracle computations by transitioning from weighted mean → weighted median.
- Built **staking + rewards mechanisms** to ensure validator incentives.
- Directed **cross-chain oracle communication** to transmit data across EVM chains.
- Worked on protocol-level questions around aggregation security, validator behavior, economic fault assumptions, and cross-chain data validity.

**[Metalayer](https://metalayer.xyz)**
- Sole smart contract engineer for modular compute and verification protocol.
- Designed **validator registration, staking, attestation lifecycle, and dispute resolution** in a Proof-of-Stake framework.
- Developed contracts with Solidity & Foundry; implemented unit, fuzz, and integration tests for reliability.
- Co-authored the **protocol whitepaper**, defining validator responsibilities, ZKP verification, and interoperability.
- Collaborated to define and prototype protocol use cases, including **bridge and oracle attestation**, **zero-knowledge proof verification**, and **AI inference result validation**.
- Focused on validator lifecycle design, finality assumptions, slashing conditions, and how off-chain computation can be verified by an on-chain protocol.

**[Syntience](https://syntience.com)**
- Built **distributed GPT-2 training** pipelines on PyTorch + GCP.
- Designed modular decision-making frameworks using mixture-of-experts models.
- Prototyped **verifiable training validation** pipelines for decentralized AI compute.
- Conducted performance optimization and resource scaling for inference reliability.
- Worked on distributed execution, checkpointing, reproducibility, and verification of compute performed by remote nodes.


## 🏗️ Personal Projects

- **[CuratedLP](https://github.com/SakshiShah29/CuratedLP)** – AI agent-managed liquidity vaults on Uniswap V4. Curator rebalances concentrated liquidity via Venice AI private inference inside an EigenCompute TEE, scoped permissions via MetaMask Delegation Framework, execution logs stored on Filecoin with PDP proofs, and on-chain reputation via ERC-8004. Orchestrated by OpenClaw on Base. (March 2026)
- **[Reckon](https://github.com/SakshiShah29/Reckon)** – Cryptoeconomic validation layer for DeFi solvers on UniswapX. Solvers register as ENS-resolvable identities, post reputation-scaled bonds, and face automatic slashing when 0G iNFT challenger agents prove objective EBBO violations. Agents coordinate over Gensyn AXL, execute via KeeperHub, and archive fill/challenge logs to 0G Storage. (May 2026)
- **[LienFi](https://github.com/SamAg19/LienFi)** – On-chain mortgage system with private credit scoring in Chainlink confidential enclaves and sealed-bid Vickrey auctions for liquidations. (Feb 2026 - March 2026)
- **[ENSRouter](https://github.com/SamAg19/ENSRouter)** – Cross-chain payment routing via ENS text records. Configure your preferred chains and tokens in ENS, and payments auto-route to where you want them. (Feb 2026)
- **[BlocPaie](https://github.com/BlocPaie)** – Confidential on-chain payroll. FHE-encrypted salaries via ZAMA, Porto smart accounts with WebAuthn passkeys, gasless transactions via Ithaca Relay. 88 tests. (Feb 2026 – March 2026)
- **[Mini ETH Node](https://github.com/SamAg19/mini-eth-node)** – Compact Ethereum-like execution node built from first principles in Rust. Accepts signed value-transfer blocks over TCP, validates parent/head relationships, executes transactions against in-memory state, updates chain head, and exposes account/head queries. (May 2026 - Present)
- **[StableGate](https://github.com/SamAg19/StableGate)** – KYC-gated institutional stablecoin swaps on Uniswap V4. Credential NFTs on Base automate permissioning cross-chain via Reactive Network to a CSMM hook on Unichain with tiered fees, daily caps, and LP whitelist. 151 tests. Graduating project for Uniswap Hook Incubator Cohort 8. (March 2026)


## 🏆 Achievements

- **[Uniswap Hook Incubator](https://ipfs.io/ipfs/QmXyacpT8RfZhh81w271QXzo4i1FPHisiggJZ62Ymmryqq)** – 🎓 Cohort 8 Graduate (Graduating project: StableGate)
- **[CuratedLP](https://github.com/SakshiShah29/CuratedLP)** – 🥇 [1st Place — Filecoin Partner Track at Synthesis Hackathon 2026](https://x.com/FILBuilders/status/2039946056499360215)
- **[LienFi](https://github.com/SamAg19/LienFi)** – 🏅 [Top 12 Projects at Chainlink Convergence Hackathon](https://chain.link/hackathon/winners/lienfi)
- **[ENSRouter](https://github.com/SamAg19/ENSRouter)** – 🥇 Best LI.FI-Powered DeFi Integration: 1st Place at HackMoney 2026
- **[MaticDEX](https://github.com/SamAg19/MaticDex)** – 🏅 ETHIndia Chainrunner Hackathon Winner
- **[EtherWills](https://github.com/SamAg19/EtherWills)** – 🏅 ETHIndia 2020 Online Hackathon Winner


## 🌱 What I'm Learning

I'm currently diving deeper into:
- **Ethereum Execution Layer** – State transitions, RLP, ECDSA recovery, trie commitments, block validation, and client architecture.
- **Protocol Testing & Client Correctness** – Fixtures, differential behavior, devnet tooling, and reproducible failure analysis.
- **ZK Proof Systems & FHE** – Privacy-preserving protocols, verifiable compute, and on-chain/off-chain verification boundaries.
- **Advanced DeFi Mechanism Design** – AMM invariants, auctions, solver incentives, and market-structure design.
- **Rust for Protocol Engineering** – Building performant blockchain infrastructure and lower-level protocol components.


## 💻 Tech Stack

**Protocol Engineering**

![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=for-the-badge&logo=ethereum&logoColor=white)
![RLP](https://img.shields.io/badge/RLP-111111?style=for-the-badge&logo=ethereum&logoColor=white)
![TCP](https://img.shields.io/badge/TCP_Networking-0A0A0A?style=for-the-badge&logo=gnometerminal&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

**Smart Contracts & EVM**

![Solidity](https://img.shields.io/badge/Solidity-363636?style=for-the-badge&logo=solidity&logoColor=white)
![Foundry](https://img.shields.io/badge/Foundry-3C3C3D?style=for-the-badge&logo=ethereum&logoColor=white)
![Hardhat](https://img.shields.io/badge/Hardhat-FFF100?style=for-the-badge&logo=hardhat&logoColor=black)
![Ethers.js](https://img.shields.io/badge/Ethers.js-2535A0?style=for-the-badge&logo=ethereum&logoColor=white)
![OpenZeppelin](https://img.shields.io/badge/OpenZeppelin-4E5EE4?style=for-the-badge&logo=openzeppelin&logoColor=white)
![Chainlink](https://img.shields.io/badge/Chainlink_CRE-375BD2?style=for-the-badge&logo=chainlink&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)

**Backend**

![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**AI / ML**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)

**Infrastructure**

![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)


## 📊 GitHub Stats

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=SamAg19&theme=tokyonight" alt="Sameer's GitHub Stats" height="170" />

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=SamAg19&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</p>


## 📫 Let's Connect!

Feel free to reach out for collaborations, hackathons, or just to say hi!

[![GitHub](https://img.shields.io/badge/GitHub-SamAg19-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/SamAg19)
[![Twitter](https://img.shields.io/badge/Twitter-@0xSamAg19-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/0xSamAg19)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sameer_Agarwal-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sameer-agarwal-75392818b/)
[![Email](https://img.shields.io/badge/Email-sameeragarwal1910-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sameeragarwal1910@gmail.com)
[![Telegram](https://img.shields.io/badge/Telegram-@sameerag19-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/sameerag19)

Thanks for stopping by! 🚀
