# ERC20 Compliant Token Crowdsale
Here we will create a crowdsale launch of ERC20 compliant token using the OpenZepplin and SafeMath libraries in Solidity. Much of the functionality employed in the following code is inherited from OpenZepplin's `Crowdsale` and `MintedCrowdsale` contracts available from their [GitHub](https://github.com/OpenZeppelin/openzeppelin-contracts/tree/release-v2.5.0/contracts) repo. 

### KaseiCoin Contract
The actual KaseiCoin fungible token itself is extremely simple. It is in fact, nearly identical to a `ERC20Mintable` token.  
`contract KaseiCoin is ERC20, ERC20Detailed, ERC20Mintable`  


### The CrowdsaleDeployer Contract
The `CrowdsaleDeployer` contract is nearly identical to OpenZepplin's `MintedCrowdsale` contract.  
`contract KaseiCoinCrowdsale is Crowdsale, MintedCrowdsale`  

### User Reproduction of Contract
To reproduce my contract and verify the utility of my code, please navigate to  
```python
https://remix.ethereum.org/
```

### Evaluation Evidence
See video titled eval.mp4 for a guided walkthrough of my smart contract deployment and evaluation.
