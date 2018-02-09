# Non-Fungible-Token ABI (ERC721)

This package provides ABIs for ERC721.

Currently it exposes the following ABIs:

* `MintableNonFungibleToken` from https://github.com/buhrmi/NonFungibleToken/blob/master/contracts/MintableNonFungibleToken.sol

## Usage

```
import {MintableNonFungibleToken} from 'erc721'
import web3 from 'web3'

let contract = new web3.eth.Contract(MintableNonFungibleToken, '0xSomeContractAddress')
```
