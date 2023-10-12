# Module-20-Challenge

## Description

I will be building and deploying a smart contract via Solidity. This contract will be using a multitude of functions including some that have set requirements to ensure the proper accounts are able to withdraw funds and all others and incapable of doing so. I will use two dummy addresses that will be allowed to withdraw from the contract I created. First I must create the "Joint Savings Account" contract and then I will compile and deploy it all within Solidity. Afterwards I will test the functions to be sure it is working properly and that the two set accounts are able to withdraw from the contract.

## Smart Contract Testing

This section is all about what I saw during my testing of my built smart contract. I will be showing you screenshots of every step to show that it worked as intended.

Step 1: Using the setAccounts function which will define the authorized Ethereum addreses.

![setaccounts](https://github.com/nkp1027/Module-20-Challenge/assets/133065472/ff592ac7-ca8a-4705-b17a-fa98071df09c)

Step 2: Testing transactions and the deposit functionality of the smart contract by sending various amounts of ether and checking the contract balance.

Sending 1 ether as wei:

![transaction1](https://github.com/nkp1027/Module-20-Challenge/assets/133065472/808f126e-ef70-4c2a-ba20-30ffda6a4816)

Sending 10 ether as wei:

![transaction2](https://github.com/nkp1027/Module-20-Challenge/assets/133065472/6c6ae2e8-9d63-43d5-9d3e-e261e1d15d53)

Sending 1 ether:


![transaction3](https://github.com/nkp1027/Module-20-Challenge/assets/133065472/7c32f812-3063-45c9-b570-6ea0b24bdd64)

Step 3: After these funds have been successfully deposited into the smart contract, I must test the withdrawal function. In doing so I will withdraw 5 ether into accountOne and 10 into accountTwo. I will verify that it is working by checking the contract balance, last to withdraw and last withdraw amount functions as a whole.

Withdrawal 1: Withdrawing 5 ether into accountOne:


![lasttowithdraw1](https://github.com/nkp1027/Module-20-Challenge/assets/133065472/7da2e8e2-6400-4b1e-a02a-d865387f663c)

Withdrawal 2: Withdrawing 10 ether into accountTwo:

![lasttowithdraw2](https://github.com/nkp1027/Module-20-Challenge/assets/133065472/d09d19c5-85f1-4bb6-8d16-d8a93f3b406d)

As shown above, the smart contract functionality was proven to work effectively.

## Tech Used
Remix IDE - the website to create, compile and deploy a smart contract. https://remix.ethereum.org/
