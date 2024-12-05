- Current popular projects

  - goat $300m in a week -- Agents with wallets yapping on X,

    - Other examples of ai agents on twitter/farcaster :AIxbt, Virtuals, Zerebro, and Base vs. Solana
    - [truth terminal](https://x.com/truth_terminal) is a tweeter agent

      - How Truth Terminal Was Created? https://www.ccn.com/education/crypto/what-is-truth-terminal/
        Truth Terminal was developed through training on the unpredictable outputs of two Claude 3 Opus AI models, which had previously consumed content from the more obscure sectors of the internet, including platforms like 4chan and Reddit. This foundation inevitably led to the establishment of a new “faith” centered around goatse, a persistent internet meme.

        As the Gospel of Goatse gained prominence, the tailored cryptocurrency Goatseus Maximus (GOAT) emerged as a significant contender in the memecoin arena.

        The cryptocurrency community responded promptly, launching GOAT via pump.fun and facilitating the creation of a Solana wallet address for the chatbot, which subsequently received nearly two million tokens in exchange.

      - being popular is the main goal of goat
      - creator adds functionality
      - sources
        - Truth Terminal Creator Andy Ayrey on $GOAT AI Agents & Meme Coins
          https://www.youtube.com/watch?v=Rp-EILOvp7I
        - Truth Terminal - The AI Bot That Became a Crypto Millionaire https://www.youtube.com/watch?v=EKspo1FLj-4&t=1s
        -

    - truth terminal negotiates a $50k grant from a16z co-founder Marc Andreessen to it's bitcoin wallet
    - truth terminal pumps its token, $goat
    - Luna and others twitter/farcaster bots with wallets on sol/base appear

  - Bittensor: A Decentralized AI Network -- $5b market cap
    - Decentralized AI Marketplace: Bittensor establishes a peer-to-peer platform where AI models, known as "neurons," are evaluated and rewarded by their peers, fostering a collaborative environment for machine learning development.
    - Incentivized Contributions: Participants are rewarded with TAO tokens for contributing valuable data or computational resources, promoting active engagement and innovation within the network.
    - Scalable AI Computations: By integrating deep learning with blockchain consensus algorithms, Bittensor enables efficient and scalable AI computations across its decentralized network.
    - Nous research is one of the users
  - DisTrO (Distributed Training Over-The-Internet) is an innovative optimizer developed by Nous Research that significantly reduces inter-GPU communication requirements, enabling efficient training of large AI models over standard internet connections.
    - **Drastic Reduction in Communication Overhead**: Achieves up to a 10,000x decrease in data transfer between GPUs during training, facilitating decentralized AI development.
    - **Enhanced Accessibility**: Allows individuals and institutions to train powerful AI models without reliance on centralized data centers, democratizing AI research.
    - **Open-Source Collaboration**: Encourages community-driven innovation by providing open access to its training optimizer, fostering a more inclusive AI ecosystem.
    - **Real-World Validation**: Successfully pre-trained a 15-billion parameter language model using distributed machines across the internet, demonstrating practical applicability.
    - **Environmental Impact**: Optimizes existing infrastructure usage, potentially reducing the environmental footprint associated with large-scale AI training.
    - **Scalability Potential**: Initial tests indicate significant bandwidth reduction, with potential scalability to larger models, paving the way for extensive decentralized AI training.
    - **Industry Recognition**: Highlighted by AI experts and media as a groundbreaking advancement in AI training methodologies.
    - more https://github.com/NousResearch/DisTrO?utm_source=chatgpt.com
      - https://dailyai.com/2024/08/the-future-of-ai-training-distros-game-changing-approach/?utm_source=chatgpt.com
      - https://a16z.com/podcast/distro-and-the-quest-for-community-trained-ai-models/
  - Ora / cartesi -- on-chain inference optimistic rollup by converting cpu instructions into evm
    - https://www.ora.io/app/opml/models

- ecosystem overview
  - The ai web3 space remains underfunded compared to centralized AI - $2B is almost nothing (openai raised $18B, anthropic -- $7B, scale ai -- $1.4B)
  - image of 100s of companies separated in categories
    - https://x.com/dimakhanarin/status/1839319560228311104
    - https://x.com/dimakhanarin/status/1861350279431459076
  - table of examples of web3 ai companies with market caps https://x.com/dimakhanarin/status/1864265617395593307
- missing for ideal AI web3
  - peer review data -- high quality data
  - efficient gpu rollup -- on-chain ai is very expensive (ora, cartesi)
  - it will allow
    - ai voting (dao) delegates -- you can write what issues you want to vote one and ai can filter those issues and vote for you
    - attestation -- pay authors for the data. artists can get paid if their image was used to generate an image
- value of modern AI
  - abilities
    - access to knowledge and analysis
    - planning
    - judging and evaluating
    - using tools
    - creativity
    - mixing and substituting concepts
    - text and multimodal
  - impact
    - replacing junior workers
    - writing checking smart contracts
    - summarizing information on Twitter
    - chat
    - content generation
    - explaining web3 and devrel support
  - resources
    - data
    - training compute
    - inference
    - tools
- value of blockchain
  - think of the blockchain as an ideal centralized overseer
    - cloning a ledger - copy of transaction records. reduces cost of operating a currency. improves usability by keeping it digital. improves security through transparency and trace
    - cloning a contract -- replacing escrow -- marketplace, loans
  - tokanization of projects
    - communal ownership
    - lower regulations
  - technology
    - scalable infrastructure -- stripe clone is by default -- easy to build trusted without a brand
    - privacy tech helps ai privacy -- zkml -- proof that someone ran a model on the data without seeing the data
- ai x web3
  - all benefit from
    - transparency with optional privacy (compute - fhe, data - zkml)
    - micro and international payments
    - ownership, control, dividends -- DAOs
  - data
    - high quality data needs a peer review system similar to the academic one
      - scientific publishing is already a decentralized ledger -- libraries have a copy of publications with a date and there is no centralized journal
      - authors and reviewers own their reputation (not twitter)
      - international payments and collaboration
    - low quality data can mostly be done by AI but there are still tasks that AI can't do (image labeling, simple multi-step reasoning)
      - international payments and operation
      - micropayments < $.30
    - attestation
      - pay creators
      - deep fake protection -- can have proof of all of the photographs. if there is no proof, it's fake.
    - licensing allows authors to get paid even if the data is on-chain
  - training
    - pooling resources
    - trusted training - a hydro-electric plant in a developing country is as reliable as AWS (at cost) to create a model that can be used for sensitive applications
    - transparency and repeatability -- can trace the data
  - inference
    - attestation -- creators get paid
    - micropayments for using models.
    - crowd knowledge
    - ora , cartesi, oracles, tee
  - tools
    - oracles
    - verified RAG
    - zk-rag is adopting a zk-oracle
  - prompts
    - marketplace to sell prompts / agents (zk for optional privacy )
    - ai dao delegate
- difficulties
  - no tech to do a competitive inference on-chain
    - GPU rollup doesn't exist yet. straightforward to build. gensys was trying. new technology asics, photonics are much faster than gpu and can be on-chain.
    - zkml, fhe -- too expensive
    - TEE -- secure computation on-chip but vulnerable to foreshadow and downfall attacks
    - oracles is not on-chain inference -- you have to trust the oracle host
  - for web3 ai to progress, the data needs to be created by experts not low-cost labor
  - attracting ai researchers is difficult. they prefer being in a good team rather than getting paid more
  - attracting ai investments but a16z likes AI and web3. most of AI investors and experts don't want to be involved in web3. My personal experience is that AI was a lot easier to raise than web3. AI is more traditional -- start with established angel network. For web3, need to go through an incubator and aim for a token listing
