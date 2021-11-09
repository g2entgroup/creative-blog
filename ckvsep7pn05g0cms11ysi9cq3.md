## Creative Platform is Integrating Chainlink VRF to Fairly Distribute  Collaborative NFTs to Voters

[Creative](https://showcase.ethglobal.co/scaling/creative)  is excited to announce that we are integrating [Chainlink VRF](https://docs.chain.link/docs/chainlink-vrf/)  to distribute collaborative NFTs to fans who have voted for winning brand campaigns. By integrating the industry-leading decentralized oracle network, we are setting the digital stage for creators, fans, and brands by enabling the fair distribution of collaborative NFTs to fans who participate in selecting the winning creator for a brand campaign in the form of a raffle.  Ultimately, this creates a more rewarding and fraud-proof experience for fans, as they can be sure the selection process for correctly voting for winners is provably fair.
 
Creative Platform is a gamified blockchain-based crowdfunding platform that connects brands, content creators, and fans to enable content creators to overcome financial hurdles.  Here’s how it works.

Brands that desire campaign content, such as video advertisements, can create a submission pool where content creators can submit metadata directly to the campaign pool.  After the deadline for campaign submission, a fan vote determines the top ten creators for the campaign.   From these top ten creators, the brand will select one creator that fits their requirements and mint a final collaborative NFT, which the brand will give away to one fan from a pool of those who chose the winner from the shortlisted creators.

To give all fans an equal chance of winning collaborative NFTs, we needed access to a secure random number generator (RNG) that any user could independently audit.  However, RNG solutions for smart contracts require several security considerations to prevent manipulation and ensure system integrity.  For instance, RNG solutions derived from blockchain data like block hashes can be exploited by miners/validators.  At the same time, off-chain APIs are opaque and don’t provide users with definitive proof about the integrity of the process.

After reviewing various solutions, we selected Chainlink VRF because of cutting-edge academic research. Furthermore, it is supported by time-tested oracle infrastructure and secured through the generation and on-chain verification of cryptographic proofs that prove the integrity of each random number supplied to [smart contracts](https://chain.link/education/smart-contracts).

Chainlink VRF works by combining block data that is unknown when the request is made with the oracle node’s pre-committed private key; to generate a random number and cryptographic proof.  The Creative smart contract will only accept the random number input if it has valid cryptographic proof, and the cryptographic proof can only be generated if the VRF process is tamper-proof.  This provides our users with automated and verifiable assurances directly on-chain that the fan eligibility process for collaborative NFTs is provably fair and not tampered with by the oracle, outside entities, or the Creative team.

In addition to Chainlink VRF, Creative plans to use Chainlink oracles to access off-chain Twitter data that will help to verify platform users and brands on-chain, linking on-chain wallet addresses to off-chain Twitter accounts.


> Chainlink offers a wide range of time-tested off-chain data and computations that are helping us build a complicated crowdfunding system that is secure and reliable.  Chainlink gives us a seamless way to integrate critical infrastructure that we would have otherwise had to build from scratch. **- the Creative Team**

### About Chainlink
Chainlink is the industry standard for building, accessing, and selling oracle services needed to power hybrid smart contracts on any blockchain. Chainlink oracle networks provide smart contracts with a way to reliably connect to any external API and leverage secure off-chain computations for enabling feature-rich applications. Chainlink currently secures tens of billions of dollars across DeFi, insurance, gaming, and other major industries, and offers global enterprises and leading data providers a universal gateway to all blockchains.

Learn more about Chainlink by visiting [chain.link](https://chain.link/) or read the documentation at [docs.chain.link](http://docs.chain.link/). To discuss an integration,  [reach out to an expert](https://chainlinkcommunity.typeform.com/to/OYQO67EF?page=announcement).

### About Creative
Creative Platform is a gamified blockchain platform for independent creators, fans, and brands to collaborate directly and earn rewards using P2E DeFi incentives. To [join the community](https://discord.gg/bRPKxTgvfk) and learn more, visit [CreativePlatform.io](https://blog.creativeplatform.io). 
