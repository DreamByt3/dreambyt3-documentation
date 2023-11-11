---
description: 'Concentrated Liquidity: Meet NFT'
---

# Listing Rewards

### What are Listing Rewards?

Part of the challenges with current listing rewards in NFTs are that it is all or nothing - meaning if your NFT gets sold, you win, and everyone else listing gets nothing. We are improving this substantially as part of the DREAMonomics. Quick recap on DREAMBYT3 marketplace fee distribution: 50% of marketplace fees will be claimable each week by veDREAM holders in $WETH, 25% will be allocated to collections from the [Snapshot ](collection-voting.md)vote for a boost and other incentives, and 25% will be allocated **DIRECTLY** to users who list NFTs of certain collections, and will received a share of the marketplace proceeds from _every single trade_ that occurs on DREAMBYT3, and in real-time. \


### How is this unique?

Non-fungible tokens are - quite literally - not fungible. This makes providing liquidity for them an extremely difficult problem to solve for marketplaces. Blur has used Airdrop incentives to attract liquidity, which will be much like DREAMBYT3's DREAM DROP Seasons, but additionally, we are introducing something completely novel, which is a payment from every NFT sale - directly to users who have listings of the same collection.&#x20;

{% hint style="info" %}
**Some caveats:** This is a completely new concept in NFTs, and so fine-tuning **will** occur as this evolves. The beginning plan is for liquidity providers (or those who list NFTs) to receive their share pro-rata to the amount of the collection listed solely based off the sale price (excluding rarity factors) of the NFT (also assuming it was not _their_ NFT sold) and paid out to each LP.
{% endhint %}

### How will this mechanism be put in practice?

At every sale, a quick query will be made to the blockchain to detect all listings of the collection in question, the user addresses who have listed the NFT at the contract that is sold, and if they fall within +-20% of the floor price. If eligible, they will receive there share of the 25% of all DREAMBYT3 marketplace fees generated sent directly to their wallet.&#x20;

Example:\
\
Sarah has listed her Pudgy Penguin for 10 ETH\
John has listed his Pudgy Penguin for 10.1 ETH\
\
Sarah's actually sells = `.1 ETH to be sent to marketplace contract`&#x20;

Calculation for LPs: `.1 * .25 = .025 ETH to be distributed in Listing Rewards for this particular sale`\
\
Let's assume there are 10 active listings at the time of sale (9 additional users + John, who all are listed for the eligible range of price) - then this means `.025 / 10 = .0025 ETH` will be sent to each address that has listed their NFT at the time of this current sale.\
&#x20;

### Why is this so important?

Listing Rewards are one of the 3 ways DREAMBYT3 completely changes the narrative for how NFT marketplaces should operate for sustainability. With three novel incentive mechanisms for participants, including veDREAM, Collection Voting, and Listing Rewards, the alignment of all stakeholders will be set to build a thriving future for the NFT ecosystem: one that is sustainable for all parties involved.&#x20;

For Listing Rewards, specifically, this means that _anyone_ can come list their NFTs on DREAMBYT3, and start receiving passive income from participating in the marketplace growth, _even_ if their NFT doesn't happen to be the one that sells. Of course, they will likely benefit even more if they participate in veDREAM and Collection Voting, but by offering Listing Rewards as direct incentives, there is no more fair or direct way to give owners of NFTs the ability to earn passive income from their assets.&#x20;

<figure><img src="../../.gitbook/assets/1600 x 900_DreamByt3 (1).png" alt="" width="563"><figcaption></figcaption></figure>
