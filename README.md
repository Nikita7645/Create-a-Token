Metacrafters: Solidity Assessment
Project: Create a Token

ASSESSMENT REQUIREMENTS:
Your contract will have public variables that store the details about your coin (Token Name, Token Abbrv., Total Supply)

Your contract will have a mapping of addresses to balances (address => uint)

You will have a mint function that takes two parameters: an address and a value. The function then increases the total supply by that number and increases the balance of the “sender” address by that amount

Your contract will have a burn function, which works the opposite of the mint function, as it will destroy tokens. It will take an address and value just like the mint functions. It will then deduct the value from the total supply and from the balance of the “sender”.

Lastly, your burn function should have conditionals to make sure the balance of "sender" is greater than or equal to the amount that is supposed to be burned.

Excuting the program
To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website.

here is a basic contract file to get you started:

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
