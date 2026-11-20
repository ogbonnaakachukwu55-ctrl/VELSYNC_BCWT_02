# Learning Token (LGT) — ERC-20 Token

## Project Overview

This project involves creating and deploying a basic ERC-20 cryptocurrency token using Solidity and OpenZeppelin.

The token was developed as part of **Task 02** of the Velsync Blockchain & Web3 Technologies Internship.

## Token Details

| Property | Value |
|---|---|
| Token Name | Learning Token |
| Token Symbol | LGT |
| Initial Supply | 1,000,000 LGT |
| Decimals | 18 |
| Standard | ERC-20 |
| Network | Sepolia Testnet |

## Technologies Used

- Solidity
- OpenZeppelin ERC-20
- Remix IDE
- MetaMask
- Sepolia Testnet
- Etherscan

## Smart Contract

The `LearningToken.sol` contract inherits from OpenZeppelin's ERC-20 implementation.

During deployment, the constructor mints 1,000,000 LGT to the deploying wallet.

## Deployment Information

**Network:** Sepolia Testnet

**Contract Address:**
`0x34D9345197c68F4a6B839d032679f6Aa3952455a`

**Useful Explorer Links:**

- [View Contract on Sepolia Etherscan](https://sepolia.etherscan.io/address/0x34D9345197c68F4a6B839d032679f6Aa3952455a)
- [View Deployment Transaction](https://sepolia.etherscan.io/tx/0xd8168343a88af2f7ffa25e01dbf02f6f016720bee0c057497369e5b982c903ee)
- [View Token Transfer Transaction](https://sepolia.etherscan.io/tx/0xfd0f44a6f1ea278130fd9e09ea16a3c46c606efd7fa167bc19b34d6506795a9d)

## Testing

The following operations were tested:

1. Retrieved the token name and symbol.
2. Checked the total token supply.
3. Checked the deployer's token balance.
4. Transferred 100 LGT to another wallet on Sepolia.
5. Confirmed the successful transfer on Etherscan.

After the transfer:

- Deployer balance: 999,900 LGT
- Recipient balance: 100 LGT

## Learning Outcomes

Through this project, I gained practical experience with:

- Creating an ERC-20 token using Solidity.
- Using OpenZeppelin contracts.
- Compiling and deploying smart contracts with Remix.
- Connecting MetaMask to a test network.
- Deploying a smart contract to Sepolia.
- Transferring tokens between wallets.
- Inspecting blockchain transactions using Etherscan.

## Disclaimer

Learning Token (LGT) is an educational test token deployed on the Sepolia test network. It has no real monetary value.
