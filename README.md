# **ETH-Proof-Beginner**
This Solidity program contract provides basic functionalities to mint new tokens and burn existing ones, following the specified requirements.

# **Description**
This repository contains a Solidity smart contract for creating custom tokens on the Ethereum blockchain. The program was created and compiled on Remix, an online Solidity IDE. https://remix.ethereum.org/.

# **Getting Started**
I used different concepts of solidity language to write this smart contract like struct, mapping, functions, etc. And I learned this from the course provided by Metacrafters. 
# **REQUIREMENTS**
''' 1. Your contract will have public variables that store the details about your coin (Token Name, Token Abbrv., Total Supply)
 2. Your contract will have a mapping of addresses to balances (address => uint)
 3. You will have a mint function that takes two parameters: an address and a value. 
   The function then increases the total supply by that number and increases the balance 
   of the “sender” address by that amount
 4. Your contract will have a burn function, which works the opposite of the mint function, as it will destroy tokens. 
   It will take an address and value just like the mint functions. It will then deduct the value from the total supply 
   and from the balance of the “sender”.
 5. Lastly, your burn function should have conditionals to make sure the balance of "sender" is greater than or equal  to the amount that is supposed to be burne


# **Installing**
You can test this code by copy-pasting it on the Remix Online IDE for solidity.
There you can compile and deploy the code online only without any need to set up local environment.
# **Executing program**
In Remix IDE, compile the smart contract by pressing CTRL+S or from the left menu.
When compiled we can deploy the code from the menu itself.
After deploying we have to enter the required values, and we can check the outputs there only.
# **Author**
Nikita Kumari

# **License**
This project is licensed under the MIT License - see the LICENSE.md file for details.
