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

- infra
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
  5. 


