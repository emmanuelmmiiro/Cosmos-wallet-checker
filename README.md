# cw20-token-testnet
Deployed CW20 fungible token on Cosmos theta-testnet for Ctrl Alt portfolio.

## Token Standard
CW20 = Cosmos equivalent of ERC-20. Used for fungible asset representation. 
Why: Maps directly to Ctrl Alt’s "tokenization of real estate, funds, private credit"

## Contract Details
Name: CtrlAltTest | Symbol: CAT | Decimals: 6
Contract Address: cosmos1...abc123 
Explorer: https://explorer.theta-testnet.polypore.xyz/cosmwasm/cosmos1...abc123

## Auditability
1. Source: CosmWasm cw-plus v1.1.2 - audited base contract
2. Immutable on testnet. Instantiate msg logged on-chain.
3. Verified via Mintscan.

## How to Test
Send CAT to another testnet address using Keplr.
# Cosmos Wallet Checker
Built on Replit + Phone. Part of Blockchain Engineer portfolio for Ctrl Alt.

## What it does
Queries Cosmos Hub balances, delegations, and rewards via RPC. 

## Tech 
Frontend: React/TS. Backend: Cosmos RPC via cosmjs. 
Why: Matches Ctrl Alt’s multi-chain architecture requirement.

## How to Run
1. Open: (https://7e04d47b-5a87-471c-999f-7d90df2e4c2e-00-3p1fm1zy5ub.picard.replit.dev) 
2. Paste Cosmos address → Click "Check Wallet"

## Security
No private keys stored. Read-only RPC calls only. .env used for endpoints.

## Why This Matters for Tokenization
This app proves I can:
1. Query multi-chain L1 data reliably - core to Ctrl Alt’s multi-chain architecture
2. Build auditable UIs for financial data - balances, delegations, rewards = asset state
3. Use public REST + no secrets - matches regulated, compliant infra requirements
