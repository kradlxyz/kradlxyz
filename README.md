## Kradl — On-Chain App & Project Launchpad

**Fund real apps from block one.** Kradl is a non-custodial, multi-chain EVM launchpad for real software (Web2 & Web3) on **Robinhood Chain** and **Base**.

- **App:** https://kradl.xyz
- **X / Twitter:** https://x.com/kradlxyz
- **Main Repository:** [kradlxyz/kradl](https://github.com/kradlxyz/kradl)

### Core Architecture
- Fair-launch `1B` fixed-supply ERC-20 (`KradlToken` — no mint, no tax, no blacklist)
- Constant-product bonding curve with **0.5% continuous ETH builder fee** & automatic DEX graduation (`UniswapV3Migrator` / `UniswapV2Migrator`)
- On-chain anti-rug `KradlVestingVault` (cliff + linear vesting) & `KradlMerkleDistributor`

### Verified Contracts (Robinhood Chain Testnet · `46630`)
| Contract | Address |
| --- | --- |
| `KradlLaunchpad` | `0x2FEE1b921F68A19bFdA0B587dff8bC245727D518` |
| `KradlVestingVault` | `0xD02a30af2430FD2CCE14987016819AeD4744d20f` |
| `KradlMerkleDistributor` | `0xe66D459b6E4E5b70Cb6129f827869E3e5D38E60C` |
