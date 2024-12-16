# Crypto Challenge

## Overview

Implement the REST API for working with the blockchain (to choose BSC, ETH, TRON).

## Requirements

1. The basis of the system is HD wallet. New wallets must be generated based on the HD algorithm.
2. Minimum required methods:
    - Wallet generation (deposit address).
    - Balance check (for a certain currency).
    - Make a transaction (FROM - hd wallet —> TO deposit address).
    - Output of completed transactions in the system according to certain filters (currency, amount, address).
3. The methods should work both for the main currency of the blockchain and for smart contracts (like ERC20).
4. Basic end-to-end and unit test.
5. Project run in docker-compose.

## Implementation Notes

- DB - for what you prefer.
- Framework - FastAPI.
- Connection to the node must be via JSON-RPC. Free services: INFURA, TronGrid, QuickNode, etc.
