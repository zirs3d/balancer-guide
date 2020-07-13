# Balancer - IHF Pool

_A short introduction guide to Balancer_
[![hackmd-github-sync-badge](https://hackmd.io/A3KJrYOeSxqTRN9Qk_AwNg/badge)](https://hackmd.io/A3KJrYOeSxqTRN9Qk_AwNg)

- [x] First steps  
       _-- prelim draft --_

## Introduction

IHF now trading on Balancer.Finance, allows you to swap the IHF token directly with Ether using WETH or USDC

Balancer Finance - https://balancer.finance  
Balancer Exchange - https://balancer.exchange

> This is a community effort, to experiment with incentivised liquidity pooling on Balancer using 1inch.exchange aggregation and purchase/redeem via multi-hop smart-order routing with other stablecoins/tokens.

## Liquidity Pooling on Balancer

To strike a fine balance between slippage and APR, having WETH/USDC pairings with Invictus Hyperion Fund (IHF) token, eligible LPs participate in trading volume (which earns liquidity pool token swap fees) with Balancer Pool-liquidity Tokens (BPT), while receiving weekly BAL Governance tokens.  
-- Using Liquidity Pools - https://pools.balancer.exchange

Following are eligible pools for tracking price discovery between market price and the underlying Invictus Hyperion Fund (IHF) AUM -- current NAV

### Pool A: IHF Balancer

IHF Balancer Pool address:  
**75% IHF -- 25% WETH**  
IHF Balancer liquidity pool earned swap fees is @ 1.19%

Providing USD\$ 10,000 worth of IHF liquidity,  
For illustration:

- Staking 70,423 IHF tokens
  (quoted price at \$0.142)
- Staking \$ 3,333 worth of WETH tokens

### Pool B: IHF -- C20 Balancer

IHF -- C20 Balancer Pool address:  
**66% IHF -- 12% USDC -- 22% C20**  
IHF Balancer liquidity pool earned swap fee is @ 0.95%

Providing USD\$ 10,000 worth of IHF -- C20 liquidity,  
For illustration:

- Staking 70,423 IHF tokens
  (quoted price at \$0.142)
- Staking \$ 3,333 worth of C20 tokens
- Staking \$ 1,818 worth of USDC tokens

### BAL governance tokens

BAL token imparts governance/voting rights, which incentivize liquidity providers aiming to achieve yield on IHF holdings, along with future improvements reaping gas savings over time.  
There are shared token pools of varying degrees of liquidity, and pool fees. IHF Balancer Pools are  whitelisted, and approved for the BAL Governance distribution rewards.  

-- About BAL governance tokens:  
https://docs.balancer.finance/protocol/bal-balancer-governance-token

-- Annual BAL rewards:   
https://www.prediction.exchange/balancer  

![Balancer ripples touchpoints](https://i.imgur.com/vNiw3Ee.png "balancer-ripples-touchpoints" =351x251)

-- Discussion on multi-assets pools compared to ETH<>Token 50/50:  
https://twitter.com/mikeraymcdonald/status/1250099292200742915

### Liquidity ripples across Balancer Pools

> Now accepting seeding of liquidity directly on Balancer.Finance, help us to grow the targeted capture of \$125K across DeFi markets currently for IHF Balancer Pool. 

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

## \$BAL Annual Rewards / IL protection

The yield generated on IHF token Balancer pools derives from swap fees of between 95-119 basis points (per trade), in addition to annual BAL distribution rewards of ~24% APY.  
The following example explains how the pool pairs IHF tokens within the pool as protection against impermanence loss (IL):

### Pool A  
***IHF -- WETH*** (_0.75_)  
75% : 25%  
Pairs with _WETH_, ratio factor of 0.75

### Pool B 
***IHF -- C20*** (_0.75_)  
66% : 22%  
Pairs with _C20_, ratio factor of 0.75

*IHF* -- USDC (_0.85_)  
66% : 12%

*C20* -- USDC (0.65)  
22% : 12%

## Usage

### Trade / Swap individual tokens

Navigate to https://balancer.exchange  
(or use https://1inch.exchange aggregator)  
Click Connect Wallet to connect your prefered Ethereum-compatible wallet.  
Enables trading across pools with smart-order routing (SOR)

### To add liquidity to IHF Balancer Pool

Navigate to https://pools.balancer.exchange  
(or use https://1inch.exchange/#/earn aggregator)  
Click Connect Wallet to connect your prefered Ethereum-compatible wallet.  
Click Add Liquidity to add individual tokens into IHF tokens Balancer Pool.

#### Pro Tip: Adding Single Asset to Liquidity Pool

Using the Add Single Asset feature on Balancer; allows you to swap using the choice of one asset into the entire pool, good for smaller amounts.

> If this is the first time your wallet connects with this smart-exchange contract you will need to click Setup Proxy, which will create and utilize a DSProxy contract to manage your liquidity pools.  
> You will also need to click Unlock for each token, which gives the smart-exchange contract permission to receive your digital assets.

### Tools for further exploration:  
-- https://pools.vision (ability to filter views of selected pools in the header)  
-- https://bal-reports.herokuapp.com (weekly BAL rewards)  
-- https://pools.fyi/#/?platform=balancer (Pool trackers)  

_Thank you for reading!_


{%hackmd theme-dark %}
