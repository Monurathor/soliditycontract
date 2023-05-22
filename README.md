# MetaCrafters Solidity Course
Welcome to the MetaCrafters Solidity Course! This course will guide you through the fundamentals of Solidity programming language and help you build a basic token contract called MyToken.sol.

# Requirements
The contract should store the details about your coin, such as the token name, token abbreviation, and total supply.
It should keep track of the balances of different addresses using a mapping.
The contract should have a mint function that increases the total supply and the balance of a specific address.
The contract should have a burn function that decreases the total supply and the balance of a specific address.
The burn function should check if the balance of the address is greater than or equal to the amount to be burned.
How to Run
To run the MyToken.sol contract, follow these steps:

Install Solidity Compiler: Make sure you have the Solidity compiler installed on your system. You can find the installation instructions on the Solidity website.

Create a new Solidity file: Open a text editor and create a new file called MyToken.sol.

Copy the code: Copy the code provided in the MyToken.sol file from this repository and paste it into your MyToken.sol file.

Compile the contract: Open your command-line interface, navigate to the directory where you saved the MyToken.sol file, and run the Solidity compiler to compile the contract:

Copy code
solc MyToken.sol
This will generate compiled bytecode (MyToken.bin) and an interface file (MyToken.abi).

Deploy the contract: You can deploy the contract on a local Ethereum development network like Ganache or on a public Ethereum network using a deployment tool like Remix, Truffle, or Hardhat. Refer to the documentation of your chosen deployment tool for instructions on contract deployment.

Interact with the contract: Once the contract is deployed, you can interact with it by calling its functions. In the case of MyToken.sol, you can mint new tokens and burn existing tokens. Use the appropriate functions with the required parameters to perform these actions.
