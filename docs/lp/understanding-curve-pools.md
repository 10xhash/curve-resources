As you should know, providing liquidity has its fair share of risks so in this article, we review the different Curve pools to help you find one that matches your risk tolerance while explaining the risks involved with being a liquidity provider on Curve.

There are currently several Curve pools with new pools added all the time.

![](https://2254922201-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-MFA0rQI3SzfbVFgp3Ic%2Fuploads%2FnVpxEmHcEWUxva1180pc%2FScreen%20Shot%202022-11-14%20at%203.21.19%20AM.png?alt=media&token=a50cc7f6-de6a-41f5-88da-ca9f90316a2c)

It’s important to understand that when you provide liquidity to a pool, no matter what coin you deposit, you essentially gain exposure to all the coins in the pool which means you want to find a pool with coins you are comfortable holding.

Before we continue, we assume you have familiarized yourself with the basics of Curve:

[Understanding Curve v1](../base-features/understanding-curve.md)

All Curve liquidity gauges receive CRV based on how much the DAO allocates to it.

## **What are liquidity pools?**

If you are new to Ethereum or DeFi, liquidity pools are a seemingly complicated concept to understand.

Liquidity pools are pools of tokens that sit in smart contracts. If you were to create a pool of DAI and USDC where 1 DAI = 1 USDC. You would have the same amount of tokens, let’s say 1,000 tokens (1,000 DAI and 1,000 USDC) in the pool.

If trader 1 comes and exchange 100 DAI for 100 USDC, you would then have 1,100 DAI and 900 USDC in the pool so the price would tilt slightly lower for USDC to encourage another trader to exchange USDC for DAI and average the pool back.

You can see those details for each pool and it is something you can take advantage of when depositing.

![](https://2254922201-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-MFA0rQI3SzfbVFgp3Ic%2Fuploads%2Fd7dTKDeNENM7MoLMpmpC%2FScreen%20Shot%202022-11-14%20at%203.26.45%20AM.png?alt=media&token=ed5838c7-e4a9-408c-bccb-fc99af8d43e5)

On the screenshot above for the [TriCrypto v2 Pool](https://curve.fi/#/ethereum/pools/tricrypto2/deposit), the three volatilely priced tokens are held in proportions similar to their price. If the coins are out of proportion traders are incentivized to take advantage of the arbitrage, which will push the balances in the pool back towards proportion

![](https://2254922201-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-MFA0rQI3SzfbVFgp3Ic%2Fuploads%2FdvMCRy7o4YBh8gBfkreP%2FScreen%20Shot%202022-11-14%20at%203.33.31%20AM.png?alt=media&token=a8a373dc-4c9e-4345-80f0-0679aee69415)

## **Base vAPY**

To understand what the different pools do, it’s also important to understand how Curve makes money for liquidity providers. Curve interests come from trading fees. Every time someone uses Curve to exchange tokens, through the Curve website, 1inch, Paraswap or another dex aggregator, a small fee is distributed to liquidity providers. This is why base vAPY increases with volume on Curve.

Some pools (Compound, PAX, Y, BUSD) also earn interest from lending protocols. Behind the scenes, those four pools also use lending protocols (like Compound or AAVE) to help generate more interest for liquidity providers. Whilst it means those pools can be better performers when lending rates are high, it’s also worth noting it also adds more layers of risks.

All pools earn interest from trading fees. Some pools also earn interest from lending and there are also some pools with incentives. You can also receive CRV when you provide liquidity on Curve Finance. Each liquidity gauge receives a different amount of CRV based on how much the DAO allocates to it.

Every time someone makes a trade on Curve.fi, liquidity providers (people who have deposited funds onto Curve) get a [small fee](../lp/understanding-curve-pools.md#what-are-curve-fees) split evenly between all providers, this is why you will see high vAPYs on days with high volume and high volatility. It’s important to note that because fees are dependent on volume, daily vAPYs can often be quite low just like they can be very high.

## **What are Curve fees?**

Swap fees are typically around 0.04% which is thought to be the most efficient when exchange stable coins on Ethereum.

Deposit and withdrawals have fees between 0% and 0.02% depending if depositing and withdrawing in imbalance or not. If fees were 0%, users could, for example, deposit in USDC and withdraw in USDT for free. Balanced deposits or withdrawals are free.
