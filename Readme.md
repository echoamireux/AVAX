Datahub Link: https://datahub.figment.io/services/avalanche

First,open your terminal，then：
* Run the following command to download the project:
  
  git clone https://github.com/echoamireux/AVAX.git
* Run the following command to Switch to the project directory:
  
  cd AVAX
* Run the following command to create a directory for your project where you will initialize the new Node.js project:
  
  npm init -y
* Run the following command to install all dependencies:
  
  npm install --save avalanche dotenv
* Replace "NODE_API_KEY" in .env file with your API KEY, you can find your API KEY in https://datahub.figment.io/services/avalanche

# Task 1
* Run the following command to complete the task1:
  
  node connect.js

# Task 2
* Run the following command to complete the task2:
  
  node create_account.js
* Get free testnet tokens:https://faucet.avax-test.network :
  enter the address from the output above to get testnet tokens,the address is like "X-fujiXXX...XXX“

# Task 3
* Run the following command to complete the task3:
  
  node query.js

# Task 4
* Run the following command to complete the task4:
  
  node transfer.js

# Task 5
* Run the following command  import a new javascript package ethereumjs-util to deal with Ethereum-based credentials:
  
  npm install --save ethereumjs-util
* Run the following command to complete the task5:
  
  node interchain_transfer.js

After completing all tasks, Please pay attention to submit the main network address when filling out the form, You can generate the mainnet wallet address here:
https://wallet.avax.network/, the address is like "X-avaxXXX...XXX“

