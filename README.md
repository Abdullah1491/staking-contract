## BRIEF OVERVIEW OF PROJECT
- This is a smart contract project where users can stake their crypto assets to earn passive income. They have the chance to receive rewards throughout the year based on the staked amount. The contract operates on a decentralized system and is highly secure and transparent. The project targets investors, crypto enthusiasts, and others. Additional features will be added in the future. 

## INSTRUCTIONS FOR HOW TO  COMPILE AND DEPLOY THE SMART CONTRACT.

### Compile Insturctions
- Installation of the sc-meta and mxpy libraries.
- Writing the contract after installation.
- Building the written contract.
- 
### Deploy Insturctions
- First, establishing the wallet connection.
- Connecting the contract to the desired network (devnet, testnet, mainnet).

## A DESCRIPTION OF THE FUNCTIONS AND FEATURES OF THE SMART CONTRACT 

### Functions:
- Stake: The user stakes EGLD tokens. The staked amount is added to the user's existing staked amount.
- Unstake: The user can withdraw the tokens they have staked.
- Claim_rewards: The user can claim the rewards they have earned from the tokens they have staked.
- Calculate_rewards: Calculates the rewards based on the amount staked by the user.
- Staked_addresses: Returns the addresses of all users who have staked tokens.
- Staking_position: Returns the staking positions of the users.
- Apy: Holds the annual percentage yield (APY).

### Features
- Stake Tokens: Users can stake EGLD tokens into the contract. The staked tokens are held in the contract for a specific period, during which users earn rewards based on the amount they have staked.
- Unstake Tokens: Users can withdraw the tokens they have staked. When the staked amount is withdrawn, the rewards are also transferred to the user. If the user withdraws the entire staked amount and leaves no tokens behind, the staking position is reset.
- Claim Rewards: Users can claim the rewards they have earned from staking their tokens. The rewards are calculated based on the staking duration and amount and are sent to the user.
- Reward Calculation: The contract calculates the rewards earned by users based on the amount they have staked. The rewards are calculated considering the annual percentage yield (APY) and the staking duration.

## IMAGES OF THE USER INTERFACE
![image_alt](https://github.com/user-attachments/assets/d7059e53-ed11-4441-a55a-56efc81ce538)
![image_alt](https://github.com/user-attachments/assets/45ca4b70-2784-4447-9501-fd36e4c0a3b4)
![image_alt](https://github.com/user-attachments/assets/23495969-4bff-4be3-80f6-224a3212f976)
![image_alt](https://github.com/user-attachments/assets/0d306ed2-ec66-42a0-94e2-c578f3c827c7)
![image_alt](https://github.com/user-attachments/assets/791a9a4e-12f4-43dd-a4c4-f5654cfc5592)


