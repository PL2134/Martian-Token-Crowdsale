# Martian-Token-Crowdsale

## Background
After waiting for years and passing several tests, the Martian Aerospace Agency selected me to become part of the first human colony on Mars. As a prominent fintech professional, they chose me to lead a project developing a monetary system for the new Mars colony. I decided to base this new system on blockchain technology and to define a new cryptocurrency named KaseiCoin. (Kasei means Mars in Japanese.)

KaseiCoin will be a fungible token that’s ERC-20 compliant. I have launched a crowdsale that will allow people who are moving to Mars to convert their earthling money to KaseiCoin.

## Compile and Deploy the Smart Contract (Evaluation Evidence)
First I have compiled the `KaseiCoin Token` contract.

![Alt text](Images/KaseiCoin_compiled.png)

I have compiled the `KaseiCoin Crowdsale` contract.

![Alt text](Images/KaseiCoin_Crowdsale_compiled.png)

I have also compiled the `KaseiCoin Deployer` contract.

![Alt text](Images/KaseiCoin_Deployer_compiled.png)

Next, I deployed the `KaseiCoin Deployer` contract.

![Alt text](Images/deployer_before_deploy_sidebar.png)

![Alt text](Images/deployer_after_deployed.png)

I then opened the deployed `KaseiCoin Deployer` contract, here you can see the two addresses for the `KaseiCoin Crowdsale` and the `KaseiCoin Token` contract.

![Alt text](Images/deployer_after_deployed_sidebar.png)

As the contracts have been deployed, I used the `At Address` function to interact with the `KaseiCoin Crowdsale` and the `KaseiCoin Token` contract.

![Alt text](Images/crowdsale_before_deploy_sidebar.png)

![Alt text](Images/KaseiCoin_before_deploy_sidebar.png)

These are the functions in the `KaseiCoin Crowdsale` contract:

![Alt text](Images/crowdsale_after_deployed_sidebar.png)

These are the functions in the `KaseiCoin Token` contract:

![Alt text](Images/KaseiCoin_after_deployed_sidebar.png)

## Interact with The Deployed Smart Contract
To test the functionality of the crowdsale until this step, I used some test accounts to buy new tokens and then checking the balances of those accounts.
![Alt text](Images/buy_token_sidebar_before_01.png)
![Alt text](Images/buy_token_sidebar_before_02.png)

Up to this step, because we have not finalised the crowdsale, hence only the gas fee was deducted from the account. We can see the account balance has dropped slightly:

![Alt text](Images/buy_token_after.png)
![Alt text](Images/buy_token_sidebar_after_01.png)
![Alt text](Images/buy_token_sidebar_after_02.png)
![Alt text](Images/buy_token_sidebar_after_03.png)

And this transaction can be varified in Ganache:

![Alt text](Images/ganache_transaction.png)
