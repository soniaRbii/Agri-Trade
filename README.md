to test the project follow these steps  :

Step 1. Start ganache! Should work with ganache or geth!

Step 2. Go to AgroChain Directory and do 'npm install'
       update the node_modules folder when you run locally(npm install)

Step 3: truffle migrate

Step 4: Important Note:

In  src directory --> app.js

Line number 43820 --->

change the variable conaddress 

The above value of contract address should be changed to the result you get when you do truffle migrate.

When you do truffle migrate you get a contract address !!!
Put that value to conaddress!!!


Step 5: 'npm run dev' to start lite-server

Step 6: Goto localhost:3000

