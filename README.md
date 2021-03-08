# Smart Contracts

## Overview
In this homework, the goal was to utilize three smart contracts that would provide three different purposes. The first purpose was to evenly distribute an amount of ether. The second was to tier split an amount of ether. and the third was to "{manage} an employee's 'deferred equity incentive plan'".

## Applications Used
1. Remix - where we will write our code for Solidity
2. MetaMask - a Google Chrome extension where we are able to store and manage our accounts and keys
3. MyCrypto - where we first began with our crypto wallet journey

## Processes and Procedures
1. Import the following files into Remix:
    - AssociateProfitSplitter.sol
    - TieredProfitSplitter.sol
    - DeferredEquityPlan.sol

2. For this example, we will be using the AssociateProfitSplitter.sol. Complete the code. Do not forget your ';'. 

3. Compile AssociateProfitSplitter.sol. You can do this in the 'Compile' tab in Remix, or you can 'command+S', like saving a file, and it will compile as well.

4. Click on the 'Deploy' tab in Remix. 

5. Change the 'Environment' to 'Injected Web3'. Your 'Account' should change to account that is in MetaMask and Ganache.

6. MAKE SURE THE 'Value' is 0. 
    - It is important to remember that when you deploy the file you must not put an amount in the 'Value' portion in the 'Deploy & Run Transactions' section in Remix.
    - If you do this you will probably get this error, like I did many times before I figured it out.

    ![Image of Error When Deploying with Amount](https://github.com/jtmcginley123/unit20/blob/master/screenshots/error.png)

7. Make sure 'Contract' says 'AssociateProfitSplitter.sol ....'

8. Add three addresses from Ganache. Make sure you do not put the address that is also the 'Account'. 
    - Your accounts would look something like this:
    ![Image of Ganache Accounts Before Transaction](https://github.com/jtmcginley123/unit20/blob/master/screenshots/AssociateProfitSplitter/ganache-accounts-before-transaction.png)

9. Press 'Transact'. The following should happen:
    - Your transaction will connect with MetaMask and a transaction of 0 will show. Like this:

    ![Image of Deployment](https://github.com/jtmcginley123/unit20/blob/master/screenshots/AssociateProfitSplitter/deployment.png)

    - Click 'Confirm' to proceed.
    
10. Next, you will complete an actual transaction that will split the Ether you send evenly three ways.
    - Your transaction should look something like this:

    ![Image of Transaction](https://github.com/jtmcginley123/unit20/blob/master/screenshots/AssociateProfitSplitter/transaction.png)

    - Click 'Confirm' to proceed.

11. After you have confirmed the transaction in MetaMask, you should go over to Ganache to see that there was a transfer of funds.
    - Your Ganache accounts should look something like this:

    ![Image of Ganache Accounts After Transaction](https://github.com/jtmcginley123/unit20/blob/master/screenshots/AssociateProfitSplitter/transaction.png)

12. You will repreat the same steps for the other two contracts. The difference will be in the amounts that split between accounts. 