# Cryptocurrency-Wallet

This project will be focusing on integrating the Ethereum blockchain network into the application in order to enable client to instantly pay professionals whom they hire with cryptocurrency.


## Methods and Techniques Used:

In this project I will use two Python files.

The first file that I will use is called fintech_finder.py. It contains the code associated with the web interface of the application. The code included in this file is compatible with the Streamlit library. I will write all the code for this Challenge in this file.

The second file that I will use is called crypto_wallet.py. This file contains the Ethereum transaction functions that I have created throughout this module’s lessons. By using import statements, I will integrate the crypto_wallet.py Python script into the Fintech Finder interface program that is found in the fintech_finder.py file.

Integrating these two files will allow us to automate the tasks associated with generating a digital wallet, accessing Ethereum account balances, and signing and sending transactions via a personal Ethereum blockchain called Ganache.

Specifically, I will assume the perspective of a Fintech Finder customer in order to do the following:

1. Generate a new Ethereum account instance by using the mnemonic seed phrase provided by Ganache.

2. Fetch and display the account balance associated with your Ethereum account address.

3. Calculate the total value of an Ethereum transaction, including the gas estimate, that pays a Fintech Finder candidate for their work.

4. Digitally sign a transaction that pays a Fintech Finder candidate, and send this transaction to the Ganache blockchain.


Review the transaction hash code associated with the validated blockchain transaction.


Once I receive the transaction’s hash code, I will navigate to the Transactions section of Ganache to review the blockchain transaction details. To confirm that I have successfully created the transaction, I will be providing screenshots to the GitHub repository for this project.

The steps for this challenge are broken out into the following sections:

1. Importing Ethereum Transaction Functions into the Fintech Finder Application
2. Signing and Executing a Payment Transaction
3. Inspecting the Transaction on Ganache


## Goals Of This Project: 

The main purpose of this project is to integrate the Ethereum blockchain network into an application in order to enable customers to instantly pay the professionals whom they hire with cryptocurrency without the use of any middleman or medium to send money. This project intends to disrupt the traditional banking methods and provide a quick and efficient way to make payments from one wallet to another.
