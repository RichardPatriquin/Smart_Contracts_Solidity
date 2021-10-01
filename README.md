## Background

Your new startup has created its own Ethereum-compatible blockchain to help connect financial institutions, and the team wants to build smart contracts to automate some company finances to make everyone's lives easier, increase transparency, and to make accounting and auditing practically automatic!

Fortunately, you've been learning how to program smart contracts with Solidity! What you will be doing this assignment is creating a few `ProfitSplitter` contracts. These contracts will do several things:

* Pay your Associate-level employees quickly and easily.

* Distribute profits to different tiers of employees.

* Distribute company shares for employees in a "deferred equity incentive plan" automatically.

# Level One: The `AssociateProfitSplitter` Contract
## Description
* This will accept Ether into the contract and divide the Ether evenly among the associate level employees. This will allow the Human Resources department to pay employees quickly and efficiently. The before and after account images are listed in the testing contract section 
## Testing AssociateProfitSplitter contract
![associate-profit-splitter-01](https://github.com/RichardPatriquin/Smart_Contracts_Solidity/blob/main/Images/testingBallanceBefore.png)
![associate-Profit-Splitter-02](https://github.com/RichardPatriquin/Smart_Contracts_Solidity/blob/main/Images/testingBallanceBefore.png)


### Level Two: The `TieredProfitSplitter` Contract
## Description 
* that will distribute different percentages of incoming Ether to employees at different tiers/levels. For example, the CEO gets paid 60%, CTO 25%, and Bob gets 15%. The before and after account images are listed in the testing contract section 
## Testing TieredProfitSplitter contract
![tiered-profit-splitter-01](https://github.com/RichardPatriquin/Smart_Contracts_Solidity/blob/main/Images/testingBallanceBefore.png)
## Set Value to Deposit
![tiered-transfer](https://github.com/RichardPatriquin/Smart_Contracts_Solidity/blob/main/Images/TieredTransfer.png)
## Balance After 
![tiered-Profit-Splitter-02](https://github.com/RichardPatriquin/Smart_Contracts_Solidity/blob/main/Images/TieredBalanceAfter.png)