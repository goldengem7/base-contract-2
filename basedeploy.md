// SPDX-License-Identifier: MIT
pragma solidity 0.8.31;

contract MyNameContract {
    // This state variable is saved in 'storage' on the blockchain
    string public myName;

    // The constructor runs only once when you deploy the contract
    constructor(string memory _initialName) {
        myName = _initialName;
    }

    // This function allows you to change the name later
    function setName(string memory _newName) public {
        myName = _newName;
    }
}

//this is a simple contract to deploy your name onchain
//you have to write your 

![35818305_7100_7_09](https://github.com/user-attachments/assets/b7e15440-9f46-40d1-bee5-bda2664d693a)

