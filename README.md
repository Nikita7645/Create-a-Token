# Metacrafters: Solidity Assessment
> Project: Create a Token 

 ## ASSESSMENT REQUIREMENTS:

This Solidity contract outlines the basic structure for creating a custom cryptocurrency token on the Ethereum blockchain. Let's break down the requirements and the contract code.

1. Public Variables:
Token Name: The name of your token (e.g., "MyToken").
Token Abbreviation: A short version or symbol of your token (e.g., "MTK").
Total Supply: The total number of tokens that exist.
2. Mapping:
A mapping is required to store the balance of each address. It links an Ethereum address to the number of tokens owned by that address (address => uint).
3. Mint Function:
This function allows the creation of new tokens.
It takes two parameters:
An address: The account that will receive the newly minted tokens.
A value: The number of tokens to mint.
The function increases the total supply by the specified value and also increases the balance of the specified address by that amount.
4. Burn Function:
This function destroys tokens, reducing the total supply.
It takes two parameters:
An address: The account from which the tokens will be burned.
A value: The number of tokens to burn.
The function checks if the balance of the specified address is greater than or equal to the amount to be burned. If the condition is met, the total supply is decreased by the specified value, and the balance of the specified address is also decreased by that amount.
5. Executing the Program:
To run this Solidity contract, you can use Remix, an online IDE for Ethereum smart contracts.
Simply copy the contract code into Remix, compile it, and then deploy it to start interacting with your token.
(https://remix.ethereum.org/) website.

---

*here is a basic contract file to get you started:*

```js
// SPDX-License-Identifier: MIT
pragma solidity 0.8.18;

contract MyToken {

    // public variables here
        // code here

    // mapping variable here
        // code here

    // mint function
        // code here

    // burn function
        // code here
}
```

You can find the solution [here](https://youtu.be/yfuMcRf1Ml4).



<details>
<summary>My Solution</summary>

```js
contract Token {
    string public tokenName = "jfmartinz";           
    string public tokenAbbreviation = "jmz";  
    uint public totalSupply = 0;       

    mapping(address => uint) public balances;  

  

    function mint(address account, uint value) public {
        totalSupply += value;          
        balances[account] += value;    
    }
    
    function burn(address account, uint value) public {
      if(balances[account] >= value){
        totalSupply -= value;          
        balances[account] -= value;    
      }  

    }

}
Author:Nikita kumari
