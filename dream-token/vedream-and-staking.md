# 📈 veDREAM and Staking

veDREAM = Passive Income

***

### How veDREAM Works:

veDREAM (Staked Dream) is a vesting system based on [Curve's veCRV mechanism](https://curve.readthedocs.io/dao-vecrv.html) which locks a  DREAM LP token for a maximum of 1 year. The veDREAM system is designed to promote long-term token-holder alignment and facilitate fair revenue sharing of protocol fees generated.By locking the token, holders are given veDREAM, entitling them to governance rights and protocol fee sharing. A user's veDREAM balance is directly proportional to the amount of DREAM LP locked and the duration of time left in the lock period. In short, if a user locks 1 DREAM LP for 1 year, they will receive the same amount of “vote power” strength as someone who locks 2 DREAM LP for only .5 year. Implications:

* veDREAM is the governance token of DREAMBYT3, used in Snapshot voting to authorize changes to the DAO including the management (adding/removing) of incentive programs, new gauges and funding of service providers.
* veDREAM holders will be entitled to all revenue sharing from DREAMBY3. The handling and amount of protocol fees are subject to change based on DREAMBYT3 Governance Process.

In the same breath, the token supply schedule for DREAM has been defined and is set permanently. A key takeaway for the new tokenomic schedule is the total supply of DREAM being capped at 1,000,000,000. There are never going to be more than 1,000,000,000 DREAM tokens - and so over time, each token will grow more valuable as the protocol continues to create useful and revenue generating products and services.

#### How is veDREAM different from veBAL and veCRV? <a href="#how-is-xnfte-different-from-vebal-and-vecrv" id="how-is-xnfte-different-from-vebal-and-vecrv"></a>

There are a few modifications that set veDREAM apart:

* Instead of locking pure DREAM, users obtain veDREAM by locking DREAM LP Tokens. This ensures that even if a large portion of DREAM tokens are locked, there is a sustainable form of deep liquidity onchain.
* veDREAM maximum locking period is 1 year, a decrease from veCRV's 4 year period (this is the same as veBAL. The minimum locking period is 1 week. What we have observed is that the NFT ecosystem and DeFi moves extremely fast, and in the event governance decides to implement a new voting system, this shorter duration of lock compared to veCRV creates a much shorter, but still sufficiently long, waiting period to transition.

### Motivation and Rationale for veDREAM

Staked DREAM (veDREAM) is the value accrual and governance mechanism developed and deployed for the benefit of the long-term stakeholders in the DREAMBYT3 protocol. The staking solution is the defining characteristic of DREAMBYT3 and the distinctive value proposition that the new NFT marketplace has over competitors such as Blur and OpenSea. Enabling fee sharing means that not just DREAMBYT3 benefits from a flourishing NFT marketplace, but that ALL $DREAM stakers in addition to the protocol benefit, creating the ideal environment for a "flywheel" effect to occur where positive momentum is reinforced continually, allowing for the DREAMBYT3 protocol to steadily win market share from the competition - _and keep it_ - thanks to stakers being committed for the long-term.&#x20;

In tangible form, the revenue sharing component of DREAMBYT3 takes the form of a set of smart contracts that live onchain in the form of a deposit contract (for staking/unstaking/increasing locked time) where veDREAM is issued to users who stake their DREAM LP tokens into the staking contract. The other component is the FeeDistributor contract, AKA the Revenue Sharing Vault. This contract is where users will be able to claim their weekly share of protocol fees generated, and will be able to be claimed, in $WETH, on a weekly basis on Thursday at 00:00 UTC. &#x20;

veDREAM is received by a user a receipt token, much like veCRV and veBAL are received from the Curve and Balancer staking programs when users lock their tokens/LP tokens into those specific contracts.

<figure><img src="../.gitbook/assets/1600 x 900_DreamByt3 (2).png" alt=""><figcaption></figcaption></figure>
