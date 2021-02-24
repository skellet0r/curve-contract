# curve-contract/contracts/pools/tusd

[Curve TUSD metapool](https://www.curve.fi/tusd), allowing swaps via the Curve [tri-pool](../3pool).

## Contracts

* [`DepositTUSD`](DepositTUSD.vy): Depositor contract, used to wrap underlying tokens prior to depositing them into the pool
* [`StableSwapTUSD`](StableSwapTUSD.vy): Curve stablecoin AMM contract

## Deployments

* [`CurveContractV2`](../../tokens/CurveTokenV2.vy): []()
* [`DepositTUSD`](DepositTUSD.vy): []()
* [`LiquidityGauge`](../../gauges/LiquidityGauge.vy): []()
* [`StableSwapTUSD`](StableSwapTUSD.vy): []()

## Stablecoins

Curve TUSD metapool utilizes the supports swaps between the following assets:

## Direct swaps

Direct swaps are possible between TUSD and the Curve tri-pool LP token.

* `TUSD`: [0x0000000000085d4780B73119b644AE5ecd22b376](https://etherscan.io/address/0x0000000000085d4780B73119b644AE5ecd22b376)
* `3CRV`: [0x6c3F90f043a72FA612cbac8115EE7e52BDe6E490](https://etherscan.io/address/0x6c3F90f043a72FA612cbac8115EE7e52BDe6E490)

## Base Pool coins

The tri-pool LP token may be wrapped or unwrapped to provide swaps between TUSD and the following stablecoins:

* `DAI`: [0x6b175474e89094c44da98b954eedeac495271d0f](https://etherscan.io/address/0x6b175474e89094c44da98b954eedeac495271d0f)
* `USDC`: [0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48](https://etherscan.io/address/0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48)
* `USDT`: [0xdac17f958d2ee523a2206206994597c13d831ec7](https://etherscan.io/address/0xdac17f958d2ee523a2206206994597c13d831ec7)
