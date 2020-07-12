
Balancer - IHF Pool
===

*A short introduction guide to Balancer*
[![hackmd-github-sync-badge](https://hackmd.io/A3KJrYOeSxqTRN9Qk_AwNg/badge)](https://hackmd.io/A3KJrYOeSxqTRN9Qk_AwNg)  
- [x] First steps  
*-- prelim draft --*


## Introduction
IHF now trading on Balancer.Finance, allows you to swap the IHF token directly with Ether using WETH or USDC

Balancer Finance -  https://balancer.finance  
Balancer Exchange - https://balancer.exchange

> This is a community effort, to experiment with incentivised liquidity pooling on Balancer using https://1inch.exchange aggregation and purchase/redeem via multi-hop smart-order routing with other stablecoins/tokens. 

## Liquidity Pooling on Balancer

To strike a fine balance between slippage and APR, having WETH/USDC pairings with Invictus Hyperion Fund (IHF) token, eligible LPs participate in trading volume (earns liquidity pool token swap fees) with Balancer Pool-liquidity Tokens (BPT), while receiving weekly BAL Governance tokens.  
-- Using Liquidity Pools - https://pools.balancer.exchange  

Following are  options for tracking price discovery between market price and the underlying Invictus Hyperion Fund (IHF) AUM -- current NAV  

### Option A: IHF Maximalist
IHF Balancer Pool address:  
**75% IHF -- 25% WETH**  
IHF Balancer liquidity pool earned swap fees is @ 1.19% 

Providing USD$ 10,000 worth of IHF liquidity -  
For illustration:    
- Staking 70,423 IHF tokens 
(quoted price at $0.142)
- Staking $ 3,333 worth of WETH tokens  


### Option B: IHF -- C20 Believer
IHF -- C20 Balancer Pool address:  
**66% IHF -- 17% USDC -- 17% C20**  
IHF Balancer liquidity pool earned swap fee is @ 0.95% 

Providing USD$ 10,000 worth of IHF -- C20 liquidity -   
For illustration:  
- Staking 70,423 IHF tokens 
(quoted price at $0.142)  
- Staking $ 2,576 worth of C20 tokens  
- Staking $ 2,576 worth of WETH tokens  

### BAL governance tokens
BAL token imparts governance/voting rights, which incentivize liquidity providers aiming to achieve yield on IHF holdings, along with future improvements reaping gas savings over time.  
There are shared token pools of varying degrees of liquidity and pool fees. IHF Balancer Pool whitelisted, and approved for the $BAL Governance distribution rewards.   
-- Annual BAL rewards - https://www.prediction.exchange/balancer
-- About BAL token - https://docs.balancer.finance/protocol/bal-balancer-governance-token

> Currently accepting seeding of liquidity directly on Balancer.Finance for BAL Pool incentives, help us grow the community of IHF investors to reach a target capture of $125K across DeFi markets  

```
Total liquidity, on Liquid Exchange - 
BTC pairs | Range $0.06-$0.16 | $ 2K : $ 125K

Total liquidity, on Liquid Exchange - 
ETH pairs | Range $0.06-$0.16 | $ 20K : $ 30K

Total liquidity, on IDEX Exchange - 
ETH Pairs | Range $0.06-$0.16 | $ 3K : $ 25K 

Current market amounts, buy:sell sides- totaling ~$223K  

```


#### $BAL Annual Rewards / IL protection
The yield generated on IHF token Balancer pools derives from swap fees of between 95-119 basis points (per trade), in addition to annual BAL distribution rewards of ~24% APY.  
The following example explains how the pool pairs IHF tokens with USDC, ratio factor of 0.742 (see example) within the pool as protection against impermanence loss (IL).

**Option A**  
IHF -- WETH  (*0.750*)   
75% : 25% 

**Option B**  
IHF -- USDC (*0.742*)  
66% : 17%    
IHF -- C20 (*0.742*)   
66% : 17%  

## Usage
### Trading /  Swap individual tokens
Navigate to https://balancer.exchange  
(or use https://1inch.exchange aggregator)  
Click Connect Wallet to connect your prefered Ethereum-compatible wallet.  
Enables trading across pools with smart-order routing (SOR)

### To add liquidity to IHF Balancer Pool
Navigate to https://pools.balancer.exchange  
(or use https://1inch.exchange/#/earn aggregator)  
Click Connect Wallet to connect your prefered Ethereum-compatible wallet.  
Click Add Liquidity to add individual tokens into IHF tokens Balancer Pool.  

Tip: Using the Add Single Asset feature on Balancer, allows you to swap using the choice of one asset into the entire pool, good for smaller amounts.
> If this is your first time your wallet connects with this smart-exchange contract you will need to click Setup Proxy, which creates a proxy contract to manage your liquidity.  
You will also need to click Unlock for each token, which gives the smart-exchange contract permission to receive your digital assets.

*Thank you for reading!*

{%hackmd theme-dark %}