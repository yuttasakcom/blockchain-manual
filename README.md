# Blockchain Manual

## Note

```
Blockchain คือ

Bitcoin คือ

Ethereum คือ

web3.js คือ

* Metamask
  * Account Address (Hex)
  * Public Key (Hex)
  * Private Key (Hex)
    Mist Browser

* Rinkeby Test Network
  * rinkey-faucet.com
  * https://faucet.rinkeby.io

* Transaction
  * nonce -> How many times the sender has sent a transaction
  * to -> Address of account this money is goint to
  * value -> Amount of ether to send to the target address
  * gasPrice -> Amount of ether the sender is willing to pay per unit gas to get this transaction proccessed
  * startGas/gasLimit -> Units of gas that this transaction can consume
  * v/r/s -> Cryptographic pieces of data that can be used to generate the senders account address. Generated from the sender's private key

* Node

* Block
  * Transaction

* Ethereum Average Block Time Chart
  * https://etherscan.io/chart/blocktime

* Smart Contack
  * balance -> Amount of ether this account owns
  * storage -> Data storage for this contract
  * code -> Raw machine code for this contract

* Solidity
  * https://remix.ethereum.org/#optimize=false&version=soljson-v0.4.24+commit.e67f0147.js

=== code ===
pragma solidity ^0.4.17; <--- Specifies the version of Solidity that our code is written with

contract Inbox { <--- Defines a new contract
    string public message;

    constructor(string initalMessage) public {
        message = initalMessage;
    }

    function setMessage(string newMessage) public {
        message = newMessage;
    }

    function getMessage() public view returns (string) { <--- function name, function type, return types
        return message;
    }
}
=============

* function types
  * public
  * private
  * view
  * constant
  * pure
  * payable

Wei

* gasPrice 300, Used 14gas
* Totol cost = 300 wei/gas x 14 gas = 300x14 wei = 4,200 wei
```
