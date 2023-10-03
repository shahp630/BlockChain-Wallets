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
* `generate_account`
* `get_balance`
* `send_transaction`

![Screenshot (75)](https://github.com/shahp630/BlockChain-Wallets/assets/133065460/f289b080-a596-468d-bf8d-709325c8328c)

# 4. Within the Streamlit sidebar section of code, create a variable named
`account`. Set this variable equal to a call on the `generate_account`
function. This function will create the KryptoJobs2Go customer’s (in this
case, your) HD wallet and Ethereum account.

# 5. Within this same section of the `krypto_jobs.py` file, define a
new `st.sidebar.write` function that will display the balance of the
customer’s account. Inside this function, call the `get_balance` function
and pass it your Ethereum `account.address`.

![Screenshot (76)](https://github.com/shahp630/BlockChain-Wallets/assets/133065460/accb027c-9480-4a9d-9e60-e132d3a065d9)

# Step 2: Sign and Execute a Payment Transaction

# Step 2 - Part 1: Write the equation that calculates the candidate’s wage

![Screenshot (77)](https://github.com/shahp630/BlockChain-Wallets/assets/133065460/9bf123c2-9942-4664-9ea8-91c2dc765927)

# Step 2 - Part 2: Call the `send_transaction` function and pass it three parameters:

![Screenshot (78)](https://github.com/shahp630/BlockChain-Wallets/assets/133065460/b47c2695-0331-4ed1-904e-f3a13018ae03)

# Step 3: Inspect the Transaction

# 1. From your terminal, navigate to the project folder that contains your `.env` file and the `krypto_jobs.py` and `crypto_wallet.py` files.

# 2. To launch the Streamlit application, type `streamlit run krypto_jobs.py`.

# KryptoJobs2Go! 4 Candidate Options: 

![Screenshot (70)](https://github.com/shahp630/BlockChain-Wallets/assets/133065460/5677c586-fe86-4179-a6f3-360987ae5fcf)

![Screenshot (71)](https://github.com/shahp630/BlockChain-Wallets/assets/133065460/06a27abf-8b7c-4649-8c31-097f4fca572f)

![Screenshot (72)](https://github.com/shahp630/BlockChain-Wallets/assets/133065460/246bc74b-d19f-415b-bd76-62425d3fd167)

![Screenshot (73)](https://github.com/shahp630/BlockChain-Wallets/assets/133065460/e0492bb2-2ff3-467a-b39c-2e77df26c5ac)


# 3. On the resulting webpage, select a candidate that you would like to hire from the appropriate drop-down menu. Then, enter the number of hours that you would like to hire them for.

![Screenshot (79)](https://github.com/shahp630/BlockChain-Wallets/assets/133065460/c95802c7-3ed5-4d70-ac11-7708012338ea)

![Screenshot (82)](https://github.com/shahp630/BlockChain-Wallets/assets/133065460/2d9408a7-ee39-44fb-9eda-39c57fa0d486)

# Although it wasn't the most ideal decision, our Company decided to hire two candidates: Jane & Jo. Jane was hired for a total of 20 hours. Our remaining Ethereum balance after this transaction is listed below:

![Screenshot (80)](https://github.com/shahp630/BlockChain-Wallets/assets/133065460/71c7786e-2e77-422d-b607-a4f64e83faea)

# Our Company decided to hire Jo for a total of 40 hours. After paying both Lane & Jo, our remaining Ethereum balance is as follows:

![Screenshot (83)](https://github.com/shahp630/BlockChain-Wallets/assets/133065460/f1038de7-2e3c-4f87-82ca-565e3ec3c207)



















