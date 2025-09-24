# bole-token
Bole Token on Hedera Testnet

# Bole Token on Hedera Testnet

This project creates a **fungible token** called **Bole (BOLE)** on the Hedera Testnet using JavaScript and the Hedera SDK.

## Project Files

- `createBole.js` → main script to create the Bole token  
- `.env` → stores your Hedera Testnet credentials (Account ID & Private Key)  
- `node_modules/` → installed dependencies (ignored by Git)  

## Setup Instructions

1. **Clone the repository** (if not already done):

```bash
git clone <your-repo-url>
cd <your-project-folder>

npm init -y
npm install @hashgraph/sdk dotenv

HEDERA_OPERATOR_ID=your-testnet-account-id
HEDERA_OPERATOR_KEY=your-testnet-private-key

node createBole.js
