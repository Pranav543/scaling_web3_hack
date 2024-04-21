### Vision

Anik is a crypto economic trust layer for the Filecoin Ecosystem which uses Restaking to allow developers to launch trusted IPC Subnets and Storage Providers to provide trusted deals with the future goal of providing for all areas of Filecoin Ecosystem

### Description
**Anik** : Anik is the trust layer for Filecoin Ecosystem.

**Restaking for Filecoin**: Anik is a restaking layer focussed on providing cryptoeconomic trust to participants in the Filecoin Ecosystem

### Use Cases
1. **IPC Subnet Security:** 
Bootstrap trusted IPC subnets by delegation of Restaked LSTs to Subnet Validators. This allows developers to create high impact subnets with cryptoeconomic trust delegated to validators via restaking.

2. **Storage Providers:**
Help manage Storage Provider capital by delegating LSTs for deal collaterals

3. **Retrieval Protocols:**
Delegate to offchain retrieval attestors & storage providers to secure the next generation of Retrieval Protocols.

### Structure

![image](https://github.com/Pranav543/scaling_web3_hack/assets/64905367/ebfb4ef0-d54d-4887-858d-e74708661fde)

Strategy manager contains a whitelisted set of strategies. Strategies allow underlying tokens to be staked with the strategy manager. Users can delegated their staked tokens to Operators via delegation manager. Operators currently can be either IPC Validators or Storage Providers. In case operators do not conduct their services properly, they are slashed.

### IPC Validator Slashing

![image](https://github.com/Pranav543/scaling_web3_hack/assets/64905367/caef856c-97c8-4734-913e-91adaf52f59f)


### Storage Provider Slashing

![image](https://github.com/Pranav543/scaling_web3_hack/assets/64905367/066513c6-65b0-419e-890d-a6a1493680e7)
