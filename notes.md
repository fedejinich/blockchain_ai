# blockchainai

## notes

- llm lacks of provable truth, while blockchain is a plattaform to provide cryptographic truth -> synergy

## resources

- papers:
  - Standford ai report [link](https://hai.stanford.edu/assets/files/hai_ai_index_report_2025.pdf)
    - 2025 general and hiper extense report
  - SoK: decentralized AI, DeAI [link](https://arxiv.org/pdf/2411.17461)
    - early 2025 SoK
  - awesome ai
    - [link1](https://github.com/shadowy-forest/awesome-decentralized-ai)
      - looks very good but it has been archived recently, it has tons of topics
    - [link2](https://github.com/edwardtay/awesome-web3-ai)
      - focused on products that integrate ai
    - [link3](https://github.com/royyannick/awesome-blockchain-mcps)
      - MCP and blockchain
    - [link4](https://github.com/steven2358/awesome-blockchain-ai)
      - curated list of Blockchain projects for Artificial Intelligence and Machine Learning
  - Blockchain and Artificial Intelligence: Synergies and Conflicts [link](https://arxiv.org/abs/2405.13462v1)
    - explores synergies and challenges between these two technologies.
  - The Convergence of Artificial Intelligence and Blockchain: The State of Play and the Road Ahead [link](https://www.mdpi.com/2078-2489/15/5/268)
    - Analiza 16 artículos recientes y extrae 14 características clave de integración: privacidad, escalabilidad, sistemas inteligentes descentralizados, automatización, entre otros. También define eras (emergencia, convergencia, aplicación) .
  - AI Agents Meet Blockchain: A Survey on Secure and Scalable Collaboration for Multi-Agents [link](https://www.mdpi.com/1999-5903/17/2/57?utm_source=chatgpt.com)
  - AI-Driven Optimization of Blockchain Scalability, Security, and Privacy Protection [link](https://www.mdpi.com/1999-4893/18/5/263)
  - AIArena: A Blockchain-Based Decentralized AI Training Platform [link](https://arxiv.org/abs/2412.14566)

- forums:
  - what-makes-ai-on-blockchain-hard [link](https://forum.dfinity.org/t/what-makes-ai-on-blockchain-hard-request-for-feedback-on-post/32686?utm_source=chatgpt.com)
  - AIPG AI POWER GRID Empowering Blockchain with AI: Proof of Useful Work [link](https://bitcointalk.org/index.php?topic=5478986.0&utm_source=chatgpt.com)

- videos:
  - The transformative potential of integrating bitcoin with AI [link](https://btcprague.com/the-transformative-potential-of-integrating-bitcoin-with-ai/#)
  - The Intersection of Blockchain and AI [link](https://www.youtube.com/watch?v=PaWhirzusEs)

- off-topic:
  - John Carmack (the creator of Doom) reveals the future of AI: robots, video games, and AI agents [link](https://www.youtube.com/watch?v=4epAfU1FCuQ)

## brainstorming

- que esta pasando en
  - product side
    - blochchain ai friendly (como base)
      - tienen un AgentKit [link](https://github.com/coinbase/agentkit)
      - todos los proyectos tienen como criterio ser "entendibles por IA"
        - lee agregan a los proyectos un LLMs.txt
          - blockchain ai friendly
    - agentes
      - agentes que de seguridad
      - agentes que ayudan a interactuar con crypto
        - base
          - tienen un AgentKit [link](https://github.com/coinbase/agentkit)
            - Built on the Coinbase Developer Platform (CDP) SDK,
              - provides everything needed to create autonomous agents that can perform sophisticated blockchain operations.
            - building-onchain-ai [link](https://docs.base.org/learn/onchain-concepts/building-onchain-ai#ai-onchain)
            - agentes en la wallet
            - usan XMTP para mesajear a Base wallet de forma segura y asi poder controlar la wallet a traves de un agent
            - dejan que los usuarios creen agentes y los submiteen para potencialmente integrarlos a la wallet
              - why agents?[link](https://docs.base.org/wallet-app/guides/chat-agents#why-agents)
      - agentes que tradean
        - quien los controla?
        - donde se hostean?
        - pueden ser controlados por alguien indesesado?
        - casos de uso
          - arbitrage bot
          - portfolio manager
          - nft trader
          - yield optimizer
  - que esta pasando en cientific side
    - decentralizar IA (DeAI)
      - la ejecucion
        - comparar los requerimientos de correr un nodo de rskj vs
          - top modelos open-source
          - top modelos closed-source
      - la gobernanza
      - los datos con los que los modelos son entrenados
  - como roostock puede contribuir a esas lineas de investigacion

- QUE NECESITAMOS PARA SER BLOCKCHAIN AI FRIENDLY
  -  que es?

## questions

General Landscape and Theoretical Foundations
- What types of intelligent agents are currently being studied or implemented in public blockchains (e.g., LLM-based agents, reinforcement learning agents, multi-agent systems), and what roles do they play?
- What technical characteristics of a blockchain make it more suitable for integrating intelligent agents, and how does Rootstock compare?
- What are the most commonly used theoretical frameworks in the literature to model autonomous agents in distributed blockchain environments?
Platforms, Architectures, and Comparisons
- Which blockchain platforms have already implemented AI agents in experimental or commercial contexts, and what lessons can be drawn for Rootstock?
- What hybrid (on-chain/off-chain) architectures are being used to deploy intelligent agents on blockchain systems, and how could they be adapted to Rootstock's infrastructure?
- How are other platforms (e.g., Base, Bittensor, Gensyn) addressing the challenges of incentives and verifiability in agent-based blockchain systems?
Use Cases and Applications
- What use cases involving intelligent agents have been most explored in other blockchain ecosystems that could be replicated or enhanced on Rootstock?
- Are there existing proposals or implementations of AI agents acting as decentralized oracles or mediators of external events for smart contracts? How could this improve Rootstock’s connectivity?
- What has been the impact of intelligent agents on end-user experience in blockchain platforms, and what can the Rootstock ecosystem (including RIF) learn from those cases?
Security, Governance, and Risks
- What security risks have been identified in the literature regarding the use of autonomous agents on public blockchains?
- How could intelligent agents influence consensus mechanisms, governance models, or incentive structures in Rootstock—positively or negatively?
- What mechanisms currently exist to ensure traceability, auditability, or verifiability of decisions made by AI agents operating in blockchain environments?
Gaps, Limitations, and Research Opportunities
- What technical or scientific limitations still hinder the integration of intelligent agents with blockchain virtual machines such as Rootstock's EVM?
- What are the major gaps in the current literature regarding EVM-compatible blockchains aiming to integrate intelligent agents?
- What opportunities exist for Rootstock to position itself as a platform for research and experimentation with decentralized AI agents that have not yet been explored by other chains?

### curated questions

General
- What types of intelligent agents are currently being studied or implemented in public blockchains (e.g., LLM-based agents, reinforcement learning agents, multi-agent systems), and what roles do they play?
- What technical characteristics of a blockchain make it more suitable for integrating intelligent agents, and how does Rootstock compare?
Use Cases and Applications
- What use cases involving intelligent agents have been most explored in other blockchain ecosystems that could be replicated or enhanced on Rootstock?
- What mechanisms currently exist to ensure traceability, auditability, or verifiability of decisions made by AI agents operating in blockchain environments?
  - How are other platforms (e.g., Base, Bittensor, Gensyn) addressing the challenges of incentives and verifiability in agent-based blockchain systems?
  Gaps, Limitations, and Research Opportunities
Risks
- What security risks have been identified in the literature regarding the use of autonomous agents on public blockchains?
Litations, and Research Opportunities
- What are the major gaps in the current literature regarding EVM-compatible blockchains aiming to integrate intelligent agents?
- What are the opportunities for rootstock?


## categories

took data from coingeecko defi llama categories

- Coingecko AI
  1. bittensor
    - $3,619,861,264
    - [link](https://github.com/bittensor/bittensor)
    - chains: own
    - An open-source protocol that utilizes blockchain technology to create a decentralized machine learning network. This network enables machine learning models to train collaboratively and be rewarded in TAO according to the informational value they offer the collective.
    - The ultimate vision of Bittensor is to create a market for artificial intelligence
  2. NEAR
    - $3,339,852,411
    - [link](https://near.org/)
    - chains: own
    - NEAR Protocol is the blockchain for AI
    - provides the infrastructure AI needs to transact, operate, and interact across Web2 and Web3.
    - NEAR combines three core elements: User-Owned AI, which ensures agents act in users’ best interests; Intents and Chain Abstraction, which eliminate blockchain complexity for seamless, goal-driven transactions across chains; and a sharded blockchain architecture that delivers the scalability, speed, and low-cost execution needed for real-world AI and Web3 use. 
  3. ICP (SMOKEY)
    - $2,908,750,208
    - [link](https://internetcomputer.org/)
    - chains: own
    - intends to support: social media, games, DeFi, multichain apps, secure front-ends, ledgers, enterprise apps, and AI models. 
  4. Render
    - $2,026,235,943
    - [link](https://renderfoundation.com/)
    - chains: eth, solana, polygon
    - The Render Network is a leading decentralized GPU compute platform for applications ranging from 3D rendering to machine learning and generative AI.
  5. IP (SMOKEY)
    - chains: own
    - Story is a purpose-built layer 1 blockchain designed specifically to onramp intellectual property (IP) to the blockchain and make it programmable.
  6. Artificial Superintelligence Alliance (Fetch.ai)
    - chains: eht, bnb, osmosis, cardano
    - The Fetch.ai network is an interchain protocol, based on the Cosmos-SDK, and uses a high-performance WASM-based smart contract language (Cosmwasm) to allow advanced cryptography and machine learning logic to be implemented on chain.
      - This technology enables creation of personalized oracles that maintain user’s DeFi positions using decentralized and non-custodial protocols to increase the security and convenience of crypto asset management.
  7. The graph
    - [link](https://thegraph.com/es/)
    - $997,743,220
    - chains: eth, bnb, polygon, avalanche, harmony, arbitrum, energi, near, sora
    - It is an indexing protocol and a global API aimed at organizing blockchain data, while making it easily accessible via GraphQL.
  8. Virtuals Protocol
    - [link](https://app.virtuals.io/)
    - $905,730,595
    - chains: eth, solana, base
    - Virtuals Protocol is a society of productive AI agents, each designed to generate services or products and autonomously engage in commerce—either with humans or other agents—onchain. 
  9. Thetha (SMOKEY)
    - [link](https://www.thetatoken.org/)
    - chains: thetha
    - On coingecko, Theta network is a decentralized video streaming network that is powered by blockchain technology. 
      - while on its mainpage... The Decentralized Cloud for AI, Media & Entertainment
- Coingeeko AI Agents
  1. Artificial Superintelligence Alliance (Fetch.ai)
  2. Virtuals Protocol
  3. REI
    - [link](https://reisearch.box/)
    - $183,510,087
    - chains: base
    - 0xReisearch is a dynamic collective of AI and crypto enthusiasts committed to revolutionizing the intersection of artificial intelligence and blockchain. Our mission is to pioneer innovative methods for integrating neural architectures into blockchain ecosystems, with a primary focus on the Ethereum Virtual Machine (EVM).
  4. AWE Network (501)
    - [link](https://www.awenetwork.ai/)
    - $105,231,179
    - chains: base
    - AWE Network is opening the portal to Autonomous Worlds where AI Agents collaborate, adapt and evolve. The Autonomous Worlds Engine (AWE) is a modular framework enabling the creation of self-sustaining worlds for scalable agent-agent and human-agent collaboration.
  5. PAAL (532)
    - [link](https://www.paal.ai/)
    - $96,912,336
    - chains: eth, bnb, base
    - Paal isn’t just a platform; it’s a dynamic ecosystem where cutting-edge AI meets the transformative power of decentralization. Our mission is to provide tools, resources, and innovations that simplify the complex, spark creativity, and foster collaboration in an ever-evolving digital world.
      - Agents and Bots: Explore intelligent tools that simplify workflows, provide insights, and interact seamlessly across platforms.
      - Automation at Scale: Harness the power of AI to automate tasks, make smarter decisions, and amplify efficiency.
      - Trust through Transparency: From audits to secure transactions, we prioritize openness and fairness in every layer of our ecosystem.
  6. Treasure (582)
    - [link](https://treasure.lol/)
    - $84,696,736
    - chains: eth, arbitrum
    - Treasure is creating the world’s greatest collectible.
      - AI-native collectibles that come to life, stretching across digital and physical spaces, designed to grow, learn, and evolve alongside you.
  7. IQ (593)
    - [link]()
    - $81,370,236
    - chians: eth, bnb, polygon
    - powers the Agent Tokenization Platform (ATP). ATP was built for developers to launch the next generation of tokenized agents that are verifiably autonomous and sovereign. These agents are capable of owning and managing digital and physical assets, from cryptocurrencies to DeFi transactions to robots.
  8. Humans AI (771)
    - [link](https://humans.ai/)
    - $54,913,538
    - chains: eth, osmosis
    - Humans.ai is a next-generation blockchain platform that brings together an ecosystem of stakeholders around the use of AI to create at scale. It combines a library of AI tools into a creative studio suite where users can pick and choose as they bring their ideas to life.
  9. Myshell (842)
    - [link](https://myshell.ai/)
    - $46,135,023
    - chains: eth, bnb
    - MyShell is an AI consumer layer for building, sharing, and owning AI agents, bridging AI and Blockchain through Agentic Frameworks, open-source models, and an AI creator community, while providing AI-powered entertainment and utility with shared ownership.
  10. Autonolas (856)
    - [link](https://olas.network/)
    - $44,524,052
    - chians: eth, solana, base, polygon, arbitrum , optimism, gnosis, celo, mode
    - Autonolas’ mission is to provide a foundation on which new types of autonomous applications can be built
      - In the context of blockchain, we call these applications off-chain services, as they run primarily off-chain but are secured on-chain






