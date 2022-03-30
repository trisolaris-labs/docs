## Core DEX Contracts

We have deployed the following contracts on the Aurora engine.

[Contract code](https://github.com/trisolaris-labs/trisolaris_core)

* Factory: `0xc66F594268041dB60507F00703b152492fb176E7`
* Router: `0x2CB45Edb4517d5947aFdE3BEAbF95A582506858B`
* WETH: `0xC9BdeEd33CD01541e1eeD10f90519d2C06Fe3feB`
* MasterChef V1 Staking Contract: `0x1f1Ed214bef5E83D8f5d0eB5D7011EB965D0D79B`
* MasterChef V2 Staking Contract: `0x3838956710bcc9D122Dd23863a0549ca8D5675D6`
* TRI ERC20: `0xFa94348467f64D5A457F75F8bc40495D33c65aBB`
* xTRI (Tribar): `0x802119e4e253D5C19aA06A5d567C5a41596D6803`
* Tri Maker: `0xe793455c9728fc91A3E5a33FAfF9eB2F228aE151`


## LP Pool Pair Addresses

* wNEAR-TRI: `0x84b123875F0F36B966d0B6Ca14b31121bd9676AD`
* AURORA-ETH: `0x5eeC60F348cB1D661E4A5122CF4638c7DB7A886e`
* wNEAR-ETH: `0x63da4DB6Ef4e7C62168aB03982399F9588fCd198`
* wNEAR-USDC: `0x20F8AeFB5697B77E0BB835A8518BE70775cdA1b0`
* wNEAR-USDT: `0x03B666f3488a7992b2385B12dF7f35156d7b29cD`
* USDC-USDT: `0x2fe064B6c7D274082aa5d2624709bC9AE7D16C77`
* wNEAR-WBTC: `0xbc8A244e8fb683ec1Fd6f88F3cc6E565082174Eb`
* TRI-AURORA: `0xd1654a7713617d41A8C9530Fb9B948d00e162194`
* wNEAR-LUNA: `0xdF8CbF89ad9b7dAFdd3e37acEc539eEcC8c47914`
* wNEAR-UST: `0xa9eded3E339b9cd92bB6DEF5c5379d678131fF90`
* TRI-USDT: `0x61C9E05d1Cdb1b70856c7a2c53fA9c220830633c`
* wNEAR-AVAX: `0x6443532841a5279cb04420E61Cf855cBEb70dc8C`
* wNEAR-BNB: `0x7be4a49AA41B34db70e539d4Ae43c7fBDf839DfA`
* wNEAR-MATIC: `0x3dC236Ea01459F57EFc737A12BA3Bb5F3BFfD071`
* wNEAR-FLX: `0x48887cEEA1b8AD328d5254BeF774Be91B90FaA09`
* wNEAR-MECHA: `0xd62f9ec4C4d323A0C111d5e78b77eA33A2AA862f`
* wNEAR-SOLACE : `0xdDAdf88b007B95fEb42DDbd110034C9a8e9746F2`
* XTRI-STNEAR : `0x5913f644A10d98c79F2e0b609988640187256373`
* wNEAR-stNEAR : `0x47924Ae4968832984F4091EEC537dfF5c38948a4`


## Rewarder Contracts (for multi rewards)

* AURORA-ETH Rewarder: `0x94669d7a170bfe62FAc297061663e0B48C63B9B5`
* TRI-AURORA Rewarder: `0x78EdEeFdF8c3ad827228d07018578E89Cf159Df1`
* wNEAR-FLX Rewarder: `0x42b950FB4dd822ef04C4388450726EFbF1C3CF63`
* wNEAR-MECHA Rewarder: `0x9847F7e33CCbC0542b05d15c5cf3aE2Ae092C057`
* wNEAR-SOLACE Rewarder: `0xbbE41F699B0fB747cd4bA21067F6b27e0698Bc30`
* XTRI-STNEAR Rewarder: `0x7B9e31BbEdbfdc99e3CC8b879b9a3B1e379Ce530`
* wNEAR-stNEAR Rewarder: `0xf267212F1D8888e0eD20BbB0c7C87A089cDe6E88`

## Stableswap Contracts
* LPToken Base: [0x08800d125088CfCd9b72432383397bAF680f7c3b](https://aurorascan.dev/address/0x08800d125088CfCd9b72432383397bAF680f7c3b)
* AmplificationUtils: [0x4135b66b138f281e0173550C3fb9A706Acc755ED](https://aurorascan.dev/address/0x4135b66b138f281e0173550C3fb9A706Acc755ED)
* SwapUtils: [0x518B8E8338864f229f762aAFFC0A9f0c4722900B](https://aurorascan.dev/address/0x518B8E8338864f229f762aAFFC0A9f0c4722900B)
* LpToken: [0x5EB99863f7eFE88c447Bc9D52AA800421b1de6c9](https://aurorascan.dev/address/0x5EB99863f7eFE88c447Bc9D52AA800421b1de6c9)
* SwapFlashLoan: [0x13e7a001EC72AB30D66E2f386f677e25dCFF5F59](https://aurorascan.dev/address/0x13e7a001EC72AB30D66E2f386f677e25dCFF5F59)

    ### Note
    * LP Token cannot be verified, blocked by internal transactions in aurorascan
    * **SwapFlashLoan variables**:
        - Flash swap loan fee: 8bps
        - Swap fee: 10bps
        - Admin fee: 0bps
        - Amplification coefficient: 400
    * **Amplification coefficient**: The coefficient determines the ratio between stable curve and uniswap curve. The higher the Amplification Coefficient the more closer final stableswap invariant is to stable curve.


## Testnet deployments

* Factory: [0x60913758635b54e6C9685f92201A5704eEe74748](https://explorer.testnet.aurora.dev/address/0x60913758635b54e6C9685f92201A5704eEe74748/transactions)
* Router: [0x26ec2aFBDFdFB972F106100A3deaE5887353d9B9](https://explorer.testnet.aurora.dev/address/0x26ec2aFBDFdFB972F106100A3deaE5887353d9B9/transactions)
* WETH: [0x1b6A3d5B5DCdF7a37CFE35CeBC0C4bD28eA7e946](https://explorer.testnet.aurora.dev/address/0x1b6A3d5B5DCdF7a37CFE35CeBC0C4bD28eA7e946/transactions)