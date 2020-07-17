# Blockchain-and-Web3-Basic-app
A **web3.js** app for greeting


Required Applications
- Ganache For blockchain as localhost
- Metamask Wallet for transactions
- Node.js
- Truffle


# How to use

- Install Node.js from [Official Nodejs website](https://nodejs.org/en/)
  or If you use linux

  ```bash
    sudo apt-get install nodejs
  ```

- Now  after install check if you have Node.js properly installed by going into the terminal and type..
  ```bash
    node -v

    npm -v
  ```
  This will show you versions of Node and npm respectively.

- Now install Truffle
  ```bash
      npm install -g truffle
  ```

- After installation is complete go to terminal and type..
    ```bash
      truffle
    ```
  This will show you all commands of Truffle
  
  
- Now all dependencies are setup. Download the repository
  ```git
    git clone https://github.com/HarshOza36/Blockchain-and-Web3-Basic-app.git
  ```
  
  ```
    cd Blockchain-and-Web3-Basic-app/client
  ```

- Unzip the node_modules folder here

- In truffle-config.js replace your network settings or use the default

- Now run truffle first

  ```bash
      cd ..
  
      truffle build
      
      truffle compile
      
      truffle deploy
  ```
  Now if these run, there are no errors and we can go and use FrontEnd with Web3.js
  
- Now again change directory to client folder to run the React based frontend.

  ```bash
    npm run start
  ```
  
- Once everything is compiled localhost will start and metamask will try to connect accounts.
