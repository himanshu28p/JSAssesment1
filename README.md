# NFT Collection

This project is a simple implementation of a Non-Fungible Token (NFT) collection using JavaScript. It includes functions to mint new NFTs, list all minted NFTs, and get the total supply of NFTs.

## Table of Contents

- [NFT Collection](#nft-collection)
  - [Table of Contents](#table-of-contents)
  - [Description](#description)
  - [Functions](#functions)
    - [`mintNFT(name, creator, price)`](#mintnftname-creator-price)
    - [`listNFTs()`](#listnfts)
    - [`getTotalSupply()`](#gettotalsupply)
  - [Usage](#usage)
  - [Example](#example)
  - [License](#license)

## Description

This project allows you to create and manage a collection of NFTs. Each NFT has the following metadata:

- `name`: The name of the NFT.
- `creator`: The creator of the NFT.
- `price`: The price of the NFT.

## Functions

### `mintNFT(name, creator, price)`

Creates a new NFT object with the given metadata and adds it to the NFT collection.

- **Parameters**:
  - `name` (string): The name of the NFT.
  - `creator` (string): The creator of the NFT.
  - `price` (number): The price of the NFT.

### `listNFTs()`

Iterates over the NFT collection and prints the metadata of each NFT to the console.

### `getTotalSupply()`

Returns the total number of NFTs in the collection.

## Usage

1. Clone or download this repository.
2. Include the JavaScript code in your project.
3. Call the functions to mint NFTs, list NFTs, and get the total supply of NFTs.

## Example

```javascript
// Create some NFTs
mintNFT("Art Piece 1", "Artist A", 1.5);
mintNFT("Art Piece 2", "Artist B", 2.0);
mintNFT("Art Piece 3", "Artist C", 2.5);

// List all NFTs
listNFTs();

// Get total supply of NFTs
console.log("Total Supply:", getTotalSupply());




NFT 1:
Name: Art Piece 1
Creator: Artist A
Price: 1.5
NFT 2:
Name: Art Piece 2
Creator: Artist B
Price: 2.0
NFT 3:
Name: Art Piece 3
Creator: Artist C
Price: 2.5
Total Supply: 3
