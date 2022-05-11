
# 1. Explain why we wouldn't call changeGreeting in a script.
We are unable to call changeGreeting in a script because the changeGreeting function was set up to change data.  
A script can only view data, so the changeGreeting function must be utilizied in a transaction.

# 2. What does the AuthAccount mean in the prepare phase of the transaction?
After you sign the transaction, this is the account that data is accessed from.

# 3. What is the difference between the prepare phase and the execute phase in the transaction?
Prepare phase allows you to access the information/data in your account.
Execute phase allows you to call funtions and change data on the blockchain.  
The execute phase isn't needed, as everything can be done in prepare, but it makes the code cleaner when used.

# 4. Additions to contract, transaction and script below
![image](https://user-images.githubusercontent.com/104528601/167929416-6827e448-5cde-4de7-b067-9c79d1071c5e.png)
![image](https://user-images.githubusercontent.com/104528601/167929572-b392a063-a4e3-47e1-820b-a63adcd0a24b.png)
![image](https://user-images.githubusercontent.com/104528601/167929629-fa8c306e-6f98-4851-a524-f1329fe0d256.png)
