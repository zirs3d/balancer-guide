# Balancer - IHF Pool

_A short introduction guide to Balancer_

- [x] First steps  
       _-- prelim draft --_  
       _-- awaiting Quarterly Report - Hyperion Q2 Report --_
- [ ] Listing on Balancer Finance  
       _-- The IHF token now has a NAV of $0.1765 --_

[![hackmd-github-sync-badge](https://hackmd.io/A3KJrYOeSxqTRN9Qk_AwNg/badge)](https://hackmd.io/A3KJrYOeSxqTRN9Qk_AwNg)

> …by implementing the token buy-and-burn protocol. Much like a share repurchase in
traditional markets, the Hyperion fund will place buy orders on exchange below, and up to, the
prevailing NAV price per token  
-- Hyperion Fund (IHF) 2020 Q2 Quarterly Report


![Invictus Hyperion Fund - IHF 2020 Q2 Report]( https://i.imgur.com/ZNVOWUYm.png "IHF 2020 Q2 Report")

https://invictuscapital.com/article/hyperion-q2-2020-report

## Introduction to IHF Balancer Pool

IHF now trading on Balancer.Finance, the user can swap IHF tokens directly with Ether using WETH or USDC  
Balancer Finance - https://balancer.finance  


> This is a guide to providing liquidity to IHF tokens by utilizing Balancer liquidity pools, using the [1inch.exchange aggregation](https://1inch.exchange/#/r/0x4881afc1d2a8ed216484cd4757f84eeb4831e2b2)  (on the 'Earn' tab), also enabling users to purchase/redeem IHF via multi-hop smart-order routing pairs with other stablecoins/tokens

## Liquidity Pooling on Balancer

To strike a fine balance between slippage and APR, much like arbing on the usual exchanges with WETH/USDC pairings with Hyperion Fund (IHF) token, a Liquidity Provider (LP) participates in trading volume (earns liquidity pool token swap-fees) with Balancer Pool-liquidity tokens (BPT). By supplying to a Balancer Pool, LPs also receive weekly BAL Governance tokens.  
-- Using Liquidity Pools - https://pools.balancer.exchange  
-- Liquidity Pools tracker - https://pools.fyi/#/?platform=balancer  


The following are eligible pools for tracking price discovery between market price and the underlying  Hyperion Fund (IHF) AUM -- current NAV

### Pool A: IHF Balancer

IHF Balancer Pool address:  
**80% IHF -- 20% WETH**  
IHF Balancer liquidity pool earned swap fees is @ 1.19% (per trade)

Providing USD\$ 10,000 worth of IHF liquidity,  
For illustration:

- Staking 56,657 IHF tokens
  (quoted price @ NAV \$0.1765)
- Staking \$ 2,500 worth of WETH tokens

### Pool B: IHF -- C20 Balancer

IHF -- C20 Balancer Pool address:  
**66% IHF -- 12% USDC -- 22% C20**  
IHF Balancer liquidity pool earned swap fee is @ 1.19% (per trade)

Providing USD\$ 10,000 worth of IHF -- C20 liquidity,  
For illustration:

- Staking 56,657 IHF tokens
  (quoted price @ NAV \$0.1765)
- Staking \$ 3,333 worth of C20 tokens
- Staking \$ 1,818 worth of USDC tokens

### BAL governance tokens

BAL token imparts governance/voting rights, which incentivize liquidity providers aiming to achieve yield on IHF holdings, along with future improvements reaping gas savings over time.  
There are shared token pools of varying degrees of liquidity, and pool fees. IHF Balancer Pools are whitelisted, and approved for the BAL Governance distribution rewards.  

-- About BAL governance tokens:  
https://docs.balancer.finance/protocol/bal-balancer-governance-token

![Balancer ripples touchpoints](https://i.imgur.com/vNiw3Eem.png "Balancer ripples touchpoints" )

-- Discussion on multi-hop pools compared to ETH <> Token 50/50:  
https://twitter.com/mikeraymcdonald/status/1250099292200742915

### Liquidity ripples across Balancer Pools

> Now accepting seeding of liquidity directly on Balancer.Finance, help us to grow the current targeted capture of \$125K across DeFi markets for the IHF Balancer Pool, aiming to achieve ~$20K in daily volume on both legs

###### Balancer Pool A - 
##### 130 WETH equivalent : $90K IHF equivalent

###### Balancer Pool B - 
##### 45K USDC+C20 equivalent : $90K IHF equivalent

###### Total Liquidity | Buy side : Sell side

```
Total liquidity, on Liquid Exchange -
BTC pairs | Range $0.06-$0.16 | $ 2K : $ 125K

Total liquidity, on Liquid Exchange -
ETH pairs | Range $0.06-$0.16 | $ 20K : $ 30K

Total liquidity, on IDEX Exchange -
ETH Pairs | Range $0.06-$0.16 | $ 3K : $ 25K

Current market amounts, buy:sell sides- totaling ~$223K
```

## \$BAL Annual rewards / IL protection

The yield generated on the IHF token Balancer pools derives from swap fees of 119 basis points (per trade), in addition to annual BAL distribution rewards.  
To show how pairing IHF tokens within the pool; by using a higher ratio than 50/50 serves as protection against impermanence loss (IL), as seen in the following examples:

### Pool A  
Pairs with _WETH_, ratio factor of 0.80

***IHF -- WETH*** (_0.80_)  
80% : 20%  
(Liquidity pool with 2-assets)

### Pool B 
Pairs with _C20_, ratio factor of 0.75


***IHF -- C20*** (_0.75_)  
66% : 22%  

*IHF* -- USDC (_0.85_)  
66% : 12%

*C20* -- USDC (0.65)  
22% : 12%  
(Liquidity pool with 3-assets)


## Usage

### Trade / Swap individual tokens

- Navigate to https://balancer.exchange  
(or use  https://1inch.exchange aggregator)  
- Click Connect Wallet to connect your prefered Ethereum-compatible wallet.  Enabling trading across pools with smart-order routing (SOR)
- Search for 'IHF' keyword / use the IHF contract address in the token search field, 
IHF token on Etherscan.io -
https://etherscan.io/token/0xaf1250fa68d7decd34fd75de8742bc03b29bd58e  

### To add liquidity to IHF Balancer Pool

- Navigate to https://pools.balancer.exchange  
or use the [1inch.exchange aggregation](https://1inch.exchange/#/r/0x4881afc1d2a8ed216484cd4757f84eeb4831e2b2) (on the 'Earn' tab)  
- Click Connect Wallet to connect your prefered Ethereum-compatible wallet.  
- Using the Filter token(s) button, and search for 'IHF' keyword / use the IHF contract address in the token search field (Shared Pools)
- Click Add Liquidity to add individual tokens into the IHF Balancer Pool.

#### Pro Tip: Adding Choice of Single Asset to the IHF Liquidity Pool

Using the Add Single Asset feature on Balancer; allows you to assign and swap using the choice of one asset into the entire pool, good for smaller amounts.

> Note: If this is the first time your wallet connects with this smart-exchange contract you will need to click Setup Proxy, which will create and use a DSProxy contract to manage your liquidity pools  

> You will also need to click Unlock for each token, which gives the smart-exchange contract permission to receive your digital assets

## Further reading and tools: 

### Swap Aggregators
1inch Exchange via [1inch.exchange aggregation](https://1inch.exchange/#/r/0x4881afc1d2a8ed216484cd4757f84eeb4831e2b2)  
Totle Swap exchange via swap.totle.com  

### Exchanges
Balancer Exchange - https://balancer.exchange  
Liquid - https://liquid.com  
IDEX - https://idex.exchange  
OVEX - https://www.ovex.io/products/c20


### Information on Liquidity Pools  
#### Liquidity Pool management
-- https://pools.balancer.exchange (Balancer pools management)  
-- https://docs.balancer.finance/protocol/bal-liquidity-mining 
(BAL Distribution)  
-- https://bal-reports.herokuapp.com (weekly BAL distribution reports)  

#### Statistics
-- https://pools.fyi/#/?platform=balancer (Liquidity Pools tracker)  
-- https://pools.vision (ability to filter views of selected pools in the header)  
-- https://www.prediction.exchange/balancer (Annual BAL rewards)


### Upcoming liquidity pools
Now you can swap directly between IHF and C20 tokens with Pool B - still gathering feedback, whether there is a need for such a smart pool or shared/private pool

When there is keen interest in Balancer pools with DZAR pairings, might be up for consideration to have a IHF and/or C20 pool linking to the stablecoin.

### Remarks
Before writing this guide, was perusing this article on [80/20 Balancer Pools](https://medium.com/balancer-protocol/80-20-balancer-pools-ad7fed816c8d). So, a fellow DeFi enthusiast later shared a concise reading about Swing trading with [High-fee Balancer Pools](https://medium.com/balancer-protocol/high-fee-balancer-pools-for-swing-trading-8bc1c169a4c2). I was now hooked.

Midst of researching on the equity holdings in the closed-end Hyperion Fund holdings and having read the whitepaper, which states that:  

> Token holders can realize their returns by selling into the purchase order made by the Hyperion Fund. Tokens purchased by the Fund are then destroyed, thereby reducing the supply of tokens. 

https://cdn.invictuscapital.com/whitepapers/hyperion.pdf

This inspires confidence in the longer term, given that the tokenized closed-end VC fund is performing well, allowance of token buy-and-burns are occuring every quarter, sought to propel the price of the token closing towards the NAV.

Well, if you are reading this IHF Balancer Pool introduction guide and find that it piques your interests (so do I); you can start by being active in the #hyperion-ihf channel; be part of the community, this is a side-project of mine and I'm not affiliated with Invictus Capital.  

Thanks to the Hyperion community, especially `prof_k` for the wonderful guidance when creating the IHF Balancer Pool, and the DeFi concepts gleaned from the discussion. 
Join in the discussion on discord - #hyperion-ihf channel:
https://invictuscapital.com/hyperionFund#aboutHyperion

_Thank you for reading!_



{%hackmd theme-dark %}
