# Blockchain projects

https://github.com/Hsien-HsiuLiao/blockchain-ecommerce-app

https://github.com/Hsien-HsiuLiao/multisig-wallet - deployed to netlify, kovan testnet

https://github.com/Hsien-HsiuLiao/Decentralized-Autonomous-Organization

https://github.com/Hsien-HsiuLiao/Buy-Music-with-Ethereum-dApp

## DeFi

https://github.com/Hsien-HsiuLiao/DEX-erc20 - deployed to netlify, kovan testnet

https://github.com/Hsien-HsiuLiao/fork-uniswap

https://github.com/Hsien-HsiuLiao/defi-api

## NFT

https://github.com/Hsien-HsiuLiao/nft-marketplace



## Resources
https://github.com/Hsien-HsiuLiao/smart-contract-best-practices

https://github.com/Hsien-HsiuLiao/defi-score

https://github.com/Hsien-HsiuLiao/brownie - A Python-based development and testing framework for smart contracts targeting the Ethereum Virtual Machine.

https://github.com/Hsien-HsiuLiao/create-eth-app

https://github.com/Hsien-HsiuLiao/evm-opcodes

https://docs.soliditylang.org/en/v0.8.5/assembly.html

## Notes

https://stackoverflow.com/questions/52690481/how-to-create-new-ethereum-solidity-contract-for-each-test-in-javascript-truffle

> The .new keyword will deploy an instance of your contract in a new context.

But, .deployed will actually use the contract that you have deployed earlier i.e. when you are using truffle migrate command.

In the context of unit test, it's better to use .new so that you will always start with fresh contract.

https://twitter.com/zulhhandyplast/status/1026181801239171072

> Use 'deployer.deploy(YourContract)' in your migration file if you want to store the contract address in the build directory.

If you use 'http://YourContract.new()', the address won't get saved in the build directory.

https://www.trufflesuite.com/docs/truffle/getting-started/interacting-with-your-contracts

https://web3js.readthedocs.io/en/v1.2.7/web3-eth-contract.html#new-contract

https://www.mycryptopedia.com/ethereum-abi-explained/ - ABI encoding is usually automated by tools that form part of the compiler or other software, such as wallets capable of interacting with smart contracts. The so-called ABI encoder requires at least a description of the contract’s interface including function names and parameter types. A common way to provide such a description is in a standardized JSON file.

EVM - https://kauri.io/#collections/A%20Deep%20Dive%20Into%20The%20Ethereum%20Virtual%20Machine%20%28EVM%29%20Series/a-deep-dive-into-the-ethereum-virtual-machine-%28ev/#evm-execution-state-overview

https://kyber.network/ - Kyber is a blockchain-based liquidity protocol that aggregates liquidity from a wide range of reserves, powering instant and secure token exchange in any decentralized application.

https://0x.org/ - 0x API is a professional grade liquidity aggregator enabling the future of DeFi applications

### Troubleshooting

If having errors running npm, 
Restore ownership of the user's npm related folders, to the current user, like this:_


  `sudo chown -R $USER:$GROUP ~/.npm`

  `sudo chown -R $USER:$GROUP ~/.config`




