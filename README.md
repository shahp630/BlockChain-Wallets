# BlockChain-Wallets

![download](https://github.com/shahp630/BlockChain-Wallets/assets/133065460/6a9f93a0-1e06-4e2a-a138-36d5c4b7cdb5)

# Background

You work at a startup that is building a new and disruptive platform called KryptoJobs2Go. KryptoJobs2Go is an application that its customers can use to find fintech professionals from among a list of candidates, hire them, and pay them. As KryptoJobs2Go’s lead developer, you have been tasked with integrating the Ethereum blockchain network into the application in order to enable your customers to instantly pay the fintech professionals whom they hire with cryptocurrency.
In this Challenge, you will complete the code that enables your customers to send cryptocurrency payments to fintech professionals. To develop the code and test it out, you will assume the perspective of a KryptoJobs2Go customer who is using the application to find a fintech professional and pay them for their work.

# What You're Creating

To complete this Challenge, you will use two Python files, both of which are contained in the starter folder.
The first file that you will use is called krypto_jobs.py. It contains the code associated with the web interface of your application. The code included in this file is compatible with the Streamlit library. You will write all of your code for this Challenge in this file.
The second file that you will use is called crypto_wallet.py. This file contains the Ethereum transaction functions that you have created throughout this module’s lessons. By using import statements, you will integrate the crypto_wallet.py Python script into the KryptoJobs2Go interface program that is found in the krypto_jobs.py file.
Integrating these two files will allow you to automate the tasks associated with generating a digital wallet, accessing Ethereum account balances, and signing and sending transactions via a personal Ethereum blockchain called Ganache.
Specifically, you will assume the perspective of a KryptoJobs2Go customer in order to do the following:


Generate a new Ethereum account instance by using the mnemonic seed phrase provided by Ganache.


Fetch and display the account balance associated with your Ethereum account address.


Calculate the total value of an Ethereum transaction, including the gas estimate, that pays a KryptoJobs2Go candidate for their work.


Digitally sign a transaction that pays a KryptoJobs2Go candidate, and send this transaction to the Ganache blockchain.


Review the transaction hash code associated with the validated blockchain transaction.


Once you receive the transaction’s hash code, you will navigate to the Transactions section of Ganache to review the blockchain transaction details. To confirm that you have successfully created the transaction, you will save screenshots to the README.md file of your GitHub repository for this Challenge assignment.

# Instructions
The steps for this challenge are broken out into the following sections:

Import Ethereum Transaction Functions into the KryptoJobs2Go Application
Sign and Execute a Payment Transaction
Inspect the Transaction on Ganache

# Step 1: Import Ethereum Transaction Functions into the KryptoJobs2Go Application

![Screenshot (74)](https://github.com/shahp630/BlockChain-Wallets/assets/133065460/9dd10fa8-89ce-4e30-8116-a65ebde00184)

# 2. Add your mnemonic seed phrase (provided by Ganache) to the starter code’s `SAMPLE.env` file.

# 3. Import the following functions from the `crypto_wallet.py` file:
# * `generate_account`
# * `get_balance`
# * `send_transaction`

![Screenshot (75)](https://github.com/shahp630/BlockChain-Wallets/assets/133065460/f289b080-a596-468d-bf8d-709325c8328c)

# 4. Within the Streamlit sidebar section of code, create a variable named
# `account`. Set this variable equal to a call on the `generate_account`
# function. This function will create the KryptoJobs2Go customer’s (in this
# case, your) HD wallet and Ethereum account.

# 5. Within this same section of the `krypto_jobs.py` file, define a
# new `st.sidebar.write` function that will display the balance of the
# customer’s account. Inside this function, call the `get_balance` function
# and pass it your Ethereum `account.address`.

![Screenshot (76)](https://github.com/shahp630/BlockChain-Wallets/assets/133065460/accb027c-9480-4a9d-9e60-e132d3a065d9)

