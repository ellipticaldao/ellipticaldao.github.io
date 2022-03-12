---
layout: page-fullwidth
title: "Documentation"
subheadline: "Welcome to the Elliptical DAO"
teaser: "The documentation is a work in progress..."
permalink: "/documentation/"
header:
   image_fullwidth: "header_roadmap_2.jpg"
---
<div class="row">
<div class="medium-4 medium-push-8 columns" markdown="1">
<div class="panel radius" markdown="1">
**Table of Contents**
{: #toc }
*  TOC
{:toc}
</div>
</div><!-- /.medium-4.columns -->


<div class="medium-8 medium-pull-4 columns" markdown="1">
{% include _improve_content.html %}

## Getting Started   {#getting-started}

To get started with *Elliptical DAO*, please [join the community]({{ site.url }}{{ site.baseurl }}/contact/), or follow the step-by-step guides to begin your journey with NFTs:

1. Install MetaMask on your device.
1. Connect your wallet.
1. Create your profile.
1. Buy $EPT.
1. Add liquidity to Uniswap V2 as an LP
1. Stake your $EPT to earn rewards and receive $vEPT for governance

## Tokenomics   {#tokenomics}

The Elliptical token ($EPT) is the protocol token from the <em>Elliptical DAO</em> ecosystem. It is an ERC-20 token deployed on the Ethereum blockchain. $EPT supply was pre-minted with 70 million tokens transferred at the deployment and has a supply cap of one billion tokens.

### $EPT allocation

![Token Allocation]({{ site.url }}{{ site.baseurl }}/images/token-allocation.png)

The Elliptical community owns 85% of the total $EPT tokens. Others are reserved for private investors and the team. Details of the allocation are listed in the following table.

|&nbsp;         |Percentage of Supply|     Total $EPT      |Initial Circulation|
|:--------------|-------------------:|--------------------:|------------------:|
|Trading Rewards| 48.5% | 485,000,000 ||
|Strategic Sale | 5.0% |50,000,000||
|Airdrop | 5.0% | 50,000,000 | 50,000,000 |
|Liquidity Management| 2.0% | 20,000,000 |20,000,000|
|Staking Rewards   | 19.5% | 195,000,000 ||
|DAO Treasury   | 10.0% | 100,000,000 ||
|Team Treasury   | 10.0% | 100,000,000 ||

The $EPT token is distributed to the participants of the Elliptical DAO including:
- Stakers: $EPT token holders who deposit their $EPT that are auto-compounded at each user interaction.
- Traders: Buyers and sellers of the Elliptical DAO-curated NFTs receive rewards daily based on their trading volumes.
- Liquidity providers: those who provide liquidity can receive token rewards.  

Some $EPT tokens, part of the pre-minted tokens, are vested by strategic sale participants, the Team Treasury, and the DAO Treasury that also collect WETH based on the prorata of the $EPT tokens held in this contract.

Finally, other preminted tokens are airdropped to those who participate in the presale of the Elliptical DAO Membership NFTs and randomly selected users of the Opensea platform.

### $EPT emission schedule

- Tokens allocated for the DAO and the Team are emitted linearly for staking for about 307 days (or 2,000,000 block time). For every block time, 50 tokens are deposited into the staking pool. Staked tokens are available for withdrawal at the same speed after 180 days (or 1,170,000 block time) of staking.

| Phase | Length (Blocks) | Tokens Per Block | Total Rewards |
| :---: | -----: | --------------: | :-----------: |
| A | 2,000,000 | 50 | 100,000,000 |


- Tokens allocated for the Strategic Sale are emitted linearly for staking for about 307 days at a speed of 25 tokens per block time, and are available for withdrawal at the same speed after 180 days (or 1,170,000 block time) of staking.

| Phase | Length (Blocks) | Tokens Per Block | Total Rewards |
| :---: | -----: | --------------: | :-----------: |
| A | 2,000,000 | 25 | 50,000,000 |

- Tokens allocated for airdrop and liquidity management are premined and free for staking and trading.

- Tokens for staking rewards are emitted based on a pre-defined schedule as explained in the following table.

| Phase | Length (Blocks) | Tokens Per Block | Total Rewards |
| :---: | -----: | --------------: | :-----------: |
| A | 195,000 | 240 | 46,800,000 |
| B | 585,000 | 120 | 42,900,000 |
| C | 1,170,000 | 60 | 35,100,000 |
| D | 2,340,000 | 30 | 35,100,000 |
| E | 3,510,000 | 15 | 17,550,000 |
| F | 4,680,000 | 7.5 | 8,775,000 |
| G | 7,020,000 | 3.75 | 8,775,000 |

- Tokens for trading rewards are emitted based on a pre-defined schedule as follows:

| Phase | Length (Blocks) | Rewards Per Day | Total Rewards |
| :---: | -----: | --------------: | :-----------: |
| A | 195,000 | 1,560,000 | 46,800,000 |
| B | 585,000 | 780,000 | 42,900,000 |
| C | 1,170,000 | 390,000 | 35,100,000 |
| D | 10,077,500 | 260,000 | 356,300,000 |


## Rewards   {#rewards}

$EPT token stakers earn 90% of the service fees including curation fees and growth sharing fees. The Elliptical DAO Membership NFT holders share the remaining 10% of the service fees collected from curation and trading. The reward ratio can be changed through the DAO Improvement Proposals.

The Elliptical DAO collects a basic curation fee of 7.5% (in $WETH) on all community curated NFT drops and a growth sharing fee of 2.5% (in $WETH) on all NFT sales. For example, if the community and an artist agree to curate, mint and drop NFTs, 10% of the trading price is given back to the community. If the NFT is sold on the secondary market, 2.5% of the trading price is given back to the community.

All the $WETH collected from these fees are consolidated at the end of each recurring 6,500 Ethereum block period (roughly 24 hours) and then 25% of the collected $WETH are distributed to $EPT stakers in a linear format per block over the next 6,500 block period, and the remaining are used to buy back $EPT for DAO reserve.

The ratio can be changed at the request of the community through a voting process.

- How often can I claim my WETH rewards?
: Any time you want. There’s no limit on the number of times you can claim your rewards each day, but just be cautious of the gas fees you are paying to claim.

- What happens if I forget to claim my WETH rewards for today?
: No need to worry. As long as your $EPT remain staked it will continue to accumulate even if you don’t claim every day. You can leave it until gas fees are low or you’ve accumulated enough to make it worth claiming.

- Active and Passive Staking
: The rewards for each day are calculated at the end of the previous period, then split between Active and Passive stakers before they're distributed.

> The main difference between Active and Passive stakers is that $EPT in passive staking do NOT earn additional $EPT while staked.

  : Active stakers are the majority of stakers, whose staked $EPT tokens are fully unlocked.

  : Passive stakers are stakers whose $EPT tokens are locked for trading but unlocked for staking: namely Team, Treasury and Strategic sale tokens.


## Owning an Membership NFT

The Elliptical DAO designs and sells 10,000 genesis membership NFTs to participants who are whitelisted in the pre-sale events. The genesis membership NFTs are passports of the Elliptical DAO that give you more privileges over other DAO participants.

1. Membership NFT holders will have the right of the first refusal during an NFT drop event. They have the right to be the first batch of buyers to submit offers on DAO driven NFT drops.
1. Holders of the first 5,000 Membership NFTs will receive free $EPT tokens (TBA).
1. More to come...  

## Governance

The rules of the Elliptical DAO are established and deployed by a core team of community members through the use of smart contracts. These smart contracts formulate the operational framework of the DAO. These on-chain rules are highly visible, verifiable, and publicly auditable so any potential member can fully understand how the protocol is to function at every step.

> Governance requires significant coordination costs, however, arising from the need to have network participants involved in voting on every decision made. These coordination costs can be radically reduced in new types of decentralized networks, in which smart contracts enable participants to govern cooperatively.

Any community members have the ability to participate in the decision making process. For example, stakers may want to increase the rewarding percentage, or artists may want to have their artworks curated and listed on the market with a reduced curation service fee. However, no special authority can modify the rules of the DAO other than a consensus reached through voting. To enable a fair and open DAO governance, a governance token ($vEPT) is proposed and created in the DAO protocol.

A total number of 1 billion $vEPT tokens are issued, however, only stakers of $EPT token will receive corresponding governance tokens at a 1:1 basis. These governance tokens are bridged to the Polygon Chain where on-chain governance can take place without substantial transaction fees.


## Roadmap – What's up next?   {#roadmap}

<em>The Elliptical DAO</em> team is currently responsible for setting up a roadmap and executing the plan, however, the Team is planning to transfer governance authority to the DAO community by the end of 2022.

{% include alert info='Business Roadmap' %}

![Roadmap]({{ site.url }}{{ site.baseurl }}/images/roadmap.png)
