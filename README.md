
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
