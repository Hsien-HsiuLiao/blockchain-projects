# Blockchain projects

* https://hh-eth-portfolio.vercel.app
* 
* 

* https://github.com/Hsien-HsiuLiao/Decentralized-Autonomous-Organization
* https://github.com/Hsien-HsiuLiao/ETB-voting-app

## DeFi

* https://github.com/Hsien-HsiuLiao/DEX-erc20 - deployed to netlify, kovan testnet
* https://github.com/Hsien-HsiuLiao/fork-uniswap
* https://github.com/Hsien-HsiuLiao/defi-api - deployed to heroku
* https://github.com/Hsien-HsiuLiao/liquidity-mining

## NFT

https://github.com/Hsien-HsiuLiao/nft-marketplace



## Resources

### Security
https://github.com/Hsien-HsiuLiao/smart-contract-best-practices

https://docs.soliditylang.org/en/develop/security-considerations.html?highlight=check%20effects#use-the-checks-effects-interactions-pattern - when writing functions, use Checks-Effects-Interactions Pattern

https://github.com/OpenZeppelin/ethernaut

https://blog.trailofbits.com/2018/10/19/slither-a-solidity-static-analysis-framework/

### EVM

https://github.com/Hsien-HsiuLiao/evm-opcodes

https://docs.soliditylang.org/en/v0.8.5/assembly.html

https://kauri.io/#collections/A%20Deep%20Dive%20Into%20The%20Ethereum%20Virtual%20Machine%20%28EVM%29%20Series/a-deep-dive-into-the-ethereum-virtual-machine-%28ev/#evm-execution-state-overview

### other

https://github.com/Hsien-HsiuLiao/defi-score

https://github.com/Hsien-HsiuLiao/brownie - A Python-based development and testing framework for smart contracts targeting the Ethereum Virtual Machine.

https://github.com/Hsien-HsiuLiao/create-eth-app



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


https://kyber.network/ - Kyber is a blockchain-based liquidity protocol that aggregates liquidity from a wide range of reserves, powering instant and secure token exchange in any decentralized application.

https://0x.org/ - 0x API is a professional grade liquidity aggregator enabling the future of DeFi applications





todo
https://github.com/Hsien-HsiuLiao/blockchain-ecommerce-app
- migrate to HH ethers
- migrate to Typescript
- use risc0 to verify eth account purchased song and hhas access to play
- add ticker for stablecoins to bottom

https://github.com/Hsien-HsiuLiao/multisig-wallet
- migrate to HH, typescript
