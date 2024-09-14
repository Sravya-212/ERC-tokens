# ERC-tokens
This Solidity contract, titled Transfer, allows the owner of the contract to transfer different types of tokens, including ERC721 (NFTs), ERC1155 (multi-token standard NFTs), and ERC20 tokens . The contract imports interfaces from the OpenZeppelin library for these token standards and implements various token transfer functionalities.
# Hardhat common usage

## Normal command

npx hardhat

npx hardhat compile

npx hardhat test

## Migrate & Deploy command

npx hardhat run scripts/`Script Name`.js [--network `Network`]

## Verify command

npx hardhat verify [--network `Network`] DEPLOYED_CONTRACT_ADDRESS ["Constructor Argument"]

## Other command

npx sol-merger "contracts/`ContractName.`"
