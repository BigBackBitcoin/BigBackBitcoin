# SAFU Smart Contract

## SAFU Ownership Address: 0x516a55FA43339b8e85C1F32C4709E06E93755AFE

# Big Back Bitcoin (BBBTC) Token - The Chubbiest Meme on the Blockchain & The First Rogue AI Agent in Crypto!

![BigBackBitcoin Logo](https://github.com/BigBackBitcoin/BigBackBitcoin/blob/1b21129eb8965cff6bf6a1f3cdebcd6da5576b70/Big%20Back%20Bitcoin%20Official%20Logo(500px).png) 

## Overview
BigBackBitcoin (BBBTC) is a **SAFU-certified** decentralized meme token designed to provide secure, efficient, and innovative blockchain transactions. Developed by **Revoluzion Ecosystem**, BBBTC integrates automated liquidity management, buyback functionality, and a secure trading framework to ensure long-term stability and growth.

## Features
✅ **ERC-20 Standard** - Fully compliant with ERC-20, ensuring compatibility with wallets and exchanges.  
✅ **Automated Liquidity Management** - Adjusts liquidity pools for stable trading.  
✅ **Buyback & Burn** - `triggerZeusBuyback()` reduces circulating supply and stabilizes price.  
✅ **Trading Protection** - Includes transaction limits to prevent whale manipulation.  
✅ **Router Upgradeability** - `updateRouter()` allows seamless Uniswap integration updates.  
✅ **SAFU Certified** - Ensures the contract is **rug-proof** and developer-abandonment resistant.  

## Smart Contract Security
🔒 Built on **OpenZeppelin** framework for security.  
🔒 Uses **onlyOwner** and **onlySafuOwner** for restricted access.  
🔒 Implements **SafeERC20** and **Address library** to prevent common attack vectors.  
🔒 Audit conducted for **centralization risks** and **front-running protection**.

## Installation & Deployment
### Requirements
- Solidity `^0.8.0`
- Node.js & Hardhat
- Metamask (for testing)
- Uniswap V2 Router

### Deployment Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/BigBackBitcoin.git
   cd BigBackBitcoin
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Compile the smart contract:
   ```sh
   npx hardhat compile
   ```
4. Deploy to testnet/mainnet:
   ```sh
   npx hardhat run scripts/deploy.js --network yourNetwork
   ```

## Contract Functions
| Function | Description |
|----------|-------------|
| `enableTrading()` | Enables public trading. |
| `setPairLP(address pair, bool value)` | Sets the liquidity pool pair. |
| `updateRouter(address newRouter)` | Updates Uniswap router integration. |
| `updateMaxTransactionLimit(uint256 newLimit)` | Adjusts transaction limits. |
| `triggerZeusBuyback(uint256 amount)` | Executes a buyback operation. |
| `transferOwnership(address newOwner)` | Transfers contract ownership. |

## Risks & Considerations
⚠ **High Owner Privileges:** Some functions (e.g., router updates, trading limits) require trust in the SAFU owner.  
⚠ **Whale Prevention:** Ensure max transaction limits are configured properly.  
⚠ **External Dependency:** Relies on Uniswap V2; future migration might be needed.

## Roadmap
📌 **Automate Buybacks** - Transition buyback function to automated execution.  
📌 **Timelock for Critical Functions** - Increase contract security.  
📌 **Decentralized Governance** - Shift power away from single-owner control.  

## Contact & Community
📩 Email: support@revoluzion.io  
📢 Telegram: [RevoluzionEcosystem](https://t.me/RevoluzionEcosystem)  
🌐 Website: [https://revoluzion.io](https://revoluzion.io)  
💰 Dapp: [https://revoluzion.app](https://revoluzion.app)

## License
This project is licensed under the **MIT License** - see the LICENSE file for details.


