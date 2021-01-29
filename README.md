# ERC1155
multi standard token having functionality of both ERC20 and ERC721 token

# Simple Summary
A standard interface for contracts that manage multiple token types. A single deployed contract may include any combination of fungible tokens, non-fungible tokens or other configurations (e.g. semi-fungible tokens).

# Abstract
This standard outlines a smart contract interface that can represent any number of fungible and non-fungible token types. Existing standards such as ERC-20 require deployment of separate contracts per token type. The ERC-721 standard’s token ID is a single non-fungible index and the group of these non-fungibles is deployed as a single contract with settings for the entire collection. In contrast, the ERC-1155 Multi Token Standard allows for each token ID to represent a new configurable token type, which may have its own metadata, supply and other attributes.

The _id argument contained in each function’s argument set indicates a specific token or token type in a transaction.

for detailed explanation please visit: https://eips.ethereum.org/EIPS/eip-1155
