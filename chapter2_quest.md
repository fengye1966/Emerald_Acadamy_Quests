# Chapter 2 #

## Day 1 ##
1. Deploy a contract to account 0x03 called "JacobTucker". Inside that contract, declare a constant variable named is, and make it have type String. Initialize it to "the best" when your contract gets deployed.


2. Check that your variable is actually equals "the best" by executing a script to read that variable. Include a screenshot of the output.
![image](https://github.com/fengye1966/Emerald_Acadamy_Quests/blob/main/Chapter2D1Quest.png?raw=true)

## Day 2 ##
1. Explain why we wouldn't call changeGreeting in a script.
   changeGreeting function change the value of a variable on the blockchain and therefore it need gas to change it. However, script can only view the blockchain data but cannot      modify it.
2. What does the AuthAccount mean in the prepare phase of the transaction?
   AuthAccount means get the authority of the target account so the transsaction executing part can operate over the data belongs to this account.
3. What is the difference between the prepare phase and the execute phase in the transaction?
   The prepare phase allows the contract access the data or information of the account and this is only happned in the prepare phase. The execte phase allows the contract to          modify the data or information on blockchain.  
   
4. This is the hardest quest so far, so if it takes you some time, do not worry! I can help you in the Discord if you have questions.
Add two new things inside your contract:

A variable named myNumber that has type Int (set it to 0 when the contract is deployed)
A function named updateMyNumber that takes in a new number named newNumber as a parameter that has type Int and updates myNumber to be newNumber
Add a script that reads myNumber from the contract

Add a transaction that takes in a parameter named myNewNumber and passes it into the updateMyNumber function. Verify that your number changed by running the script again.
![image](https://github.com/fengye1966/Emerald_Acadamy_Quests/blob/0c7a7500ff3a977183426bb22e91a9677afd536d/Chapter2D2QuestContract.png)
![image](https://github.com/fengye1966/Emerald_Acadamy_Quests/blob/0c7a7500ff3a977183426bb22e91a9677afd536d/Chapter2D2QuestTransaction.png)
![image](https://github.com/fengye1966/Emerald_Acadamy_Quests/blob/0c7a7500ff3a977183426bb22e91a9677afd536d/Chapter2D2QuestScript.png)
