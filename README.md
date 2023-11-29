## Decentralized P2P Protocol On Starknet

A decentralized replication of centralized p2p platforms on the blockchain.

### What are the use cases?

- Allow users to get tokens on a different chain in a p2p fashion.
    - For example user sends ether to a peer on the smart contract 
    - and the peer sends ether to the user on a different chain.
    - No need for bridges, swaps, wormholes etc ...
- An alternative for dexes as users can also buy tokens with tokens on the same chain in a p2p fashion.
- Allow users to get fiat for their crypto tokens in a p2p fashion.

### Starknet Development

Starknet Foundray -  https://foundry-rs.github.io/starknet-foundry/index.html

Testnet Explorer - https://testnet.starkscan.co/

Starknet Tutorials - https://www.starknet.io/en/tutorials

Starknet Dapps - https://www.starknet.io/en/ecosystem/dapps

Cairo Languae - https://book.cairo-lang.org/

Starknet Docs - https://docs.starknet.io/documentation/


## How does it work?

### Protocol Participants

#### Trader
A normal user going to buy or sell.  Anyone can connect their wallet and start trading. Needs to register. 

#### Buyers (Merchant)

they have registered on the platform to buy crypto from traders and send them fiat. They need to go through a registration process, KYC, etc... It will still use web3 verification, etc... 

#### Sellers (Merchant)

they have registered on the platform to sell. They send crypto and receive fiat from traders. They also need to register. 

#### Settlers

they are there to settle any issues on trades. Also needs to register.

#### How would trades work? 

##### Trader selling crypto to the buyer.

1. The trader will see a list of offers which are listed from the smart contract.

2. The trader will place the order by sending crypto to the smart contract. 

3. The buyer will see the order and send fiat. 

4. The trader will confirm receipt. 

5. Money will be released to the buyer. 

6. In case of dispute, several settlers are invited to investigate and vote.


##### Trader buying crypto from the seller.

1. The trader will see a list of offers which are listed from the smart contract.

2. The trader will place the order and send fiat to the seller. 

3. The trader will confirm they've sent fiat. 

4. The seller will see the order and confirm receipt

5. Crypto will be released to the trader. 

6. In case of dispute several settlers are invited to investigate and vote.

#### How do we ensure no one loses money? 

##### Proof of stake.

Settlers, Buyers, and Sellers need to have a stake in the platform to carry out their functionalities.

Punishment and rewards.

If any of these parties are found trying to cheat their stake will be slashed. Profit on trades will be much higher on decentralized platforms due to lower charges. 

##### Kyc & Reputation System

All parties will perform some sort of web3 KYC. Examples are Gitcoin passport, email verification, social media verification etc... World coin can be added later. 

Good behavior will be rewarded with a reputation system in place. Parties involved in every successful trade will receive a reputation increase. 

We can put all of this in something called the social score. You will require a certain amount of social score to be any of these participants. For example, completing KYC will increase your social score to a certain level before you can start doing any trade. 

Also, your social score will determine the trade volume.
We can have various mechanisms around these.

#### Settler

1. They secure the protocol by settling transaction disputes and getting rewarded for that. 

2. They have to stake a certain amount to ensure that they are truthful. If any untruthfulness is detected they will be slashed. 

3. We can have an extra layer where after settlers give their dispute, the protocol dao will review before passing. 

#### Buyer

1. They will need to have a certain deposit locked on the contract in addition to their stake. For example, a buyer can take orders up to half of their amount locked. This ratio can be determined. 

#### Seller

1. Similar to seller. 

#### Trader

1. Also affected by reputation system and KYC. 

2. Still trying to figure out staking for them...
