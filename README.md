# StakingDapp

A secure staking smart contract built with Solidity.

## What it does
- Users stake ETH and earn 10% reward
- 30-day lock period before unstaking
- Secure reward claiming system

## Security Features
- Checks-Effects-Interactions pattern
- ReentrancyGuard pattern (state reset before transfer)
- Access control with modifiers
- Lock period enforcement

## Functions
| Function | Description |
|---|---|
| stake(amount) | Stake ETH |
| unstake() | Unstake after 30 days + claim reward |
| claimReward() | Claim reward while still staking |
| getStakeInfo(address) | View stake details |
| getTimeLeft(address) | View seconds until unlock |

## Stack
- Solidity ^0.8.18
- Remix IDE
- Sepolia Testnet
