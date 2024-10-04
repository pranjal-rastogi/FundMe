# FundMe Project

## Overview

**FundMe** is a crowdfunding platform built on Ethereum using Solidity. Users can contribute funds in Ether (ETH) to support projects, with contributions validated against Chainlink price feeds.

## Features

- **Fund Projects:** Users can send ETH to fund projects.
- **Withdrawal Control:** Only the contract owner can withdraw funds.
- **Price Conversion:** Uses Chainlink to convert ETH to USD.

## Smart Contract

- **PriceConverter Library:** Handles fetching ETH/USD prices.
- **FundMe Contract:**
  - Tracks contributions and funders.
  - Enforces a minimum contribution of $5 USD.
  - Handles fund withdrawals securely.

## Usage

1. Deploy the contract on an Ethereum network (e.g., Sepolia).
2. Fund a project using the `fund` function.
3. Withdraw funds using the `withdraw` function (only for the owner).

## Requirements

- Solidity
- Remix IDE
- Chainlink price feed address for the network


