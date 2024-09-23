# **ETH-Proof-Beginner**
This repository is made as the submission of the course ETH-Proof Beginner offered by Metacrafters. This course provided me the insights of the basics of Etheriumn blockchain as well as Solidity language. The basics of Solidity like variables, structs, mapping, functions, conditional statements were all taught in this course. Also it is used in this project!

# **Description**  
The project of this course was to write a smart contract in the solidity, to create a new token. I have named it "KHUSHI" and it's abbreviation is "KSI". Also there are two functions, first being the mint function where if someone mints my tokens, his wallet balance will get updated as well as the total supply of my token. The second function is Burn function, where if someone burns the YSH tokens, it will first check if that person has that much balance or not and then burn accordingly and update the balances.

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
