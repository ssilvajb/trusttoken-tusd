# TrueUSD (TUSD) subgraph

The world's most transparent stable coin, attested live on-chain.

## Types of Data

- data on Total Supply
- data on transactions (mint, burn and transfers)
- data on holders

## Entities:

- User : data on users and their balances
- Minter: data on Merchants and related minted and burnt tokens
- UserCounter: data on users per day
- MinterCounter: data on number of Minters
- TransferCounter: data on number of transfers per day
- TotalSupply: data on total supply

## EventHandlers
- event: Burn(indexed address,uint256)
  - handler: handleBurn
- event: Mint(indexed address,uint256)
  - handler: handleMint
- event: Transfer(indexed address,indexed address,uint256)
  - handler: handleTransfer

## Running Locally

Make sure to update package.json settings to point to your own graph account.

## Deployed Version

A deployed version of the WBTC subgraph can be found in 


