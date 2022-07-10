# Crypto Wallet

![image](https://user-images.githubusercontent.com/98672852/178151104-3319c908-96dc-4148-9d08-8457e625ca07.png)

## Background
For this project, we will be building a blockchain payment system for ETH, along with a wallet and our main platform called Fintech Finder. Fintech Finder is an application that its customers can use to find fintech professionals from among a list of candidates, hire them, and pay them in cryptocurrency
As Fintech Finder’s lead developer, I will integrating the Ethereum blockchain network into the application in order to enable the customers to instantly pay the fintech professionals whom they hire with cryptocurrency.
We will complete the code that enables your customers to send cryptocurrency payments to fintech professionals. To develop the code and test it out, we will assume the perspective of a Fintech Finder customer who is using the application to find a fintech professional and pay them for their work.

## Technologies and libraries used: 

- Streamlit 

- Ganache

- Web3

- Bip44 (Wallet) 

The Fintech Finder application will allow to see list of candidates along with their hourly rate. If we decide to hire them we will be able ti input the number of hours worked and make an ether payment through the application directly. All the coding for the account mnemonic, transaction hashing, gas pricing and strategy are coded in the file crypto_wallet.py 
The Streamlit application code can be found in fintech_finder.py

Screenshot of Streamlit application with an ETH payment made to one of the employees:

![image](https://user-images.githubusercontent.com/98672852/178151123-f8554adc-3d1e-46c6-bfa4-802f7798db59.png)

Screenshot of Ganache application with block and mining details of the ETH transaction:

![image](https://user-images.githubusercontent.com/98672852/178151131-b318fc92-9be9-4e0f-985f-393b4ffeb172.png)

Screenshot of account balance:

![image](https://user-images.githubusercontent.com/98672852/178151844-060741cc-25cd-4331-8b77-4860991ba373.png)

