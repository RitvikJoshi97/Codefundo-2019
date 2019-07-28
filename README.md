# Codefundo++ 2019
Voting in India is dependant upon one's voting card. This consists of voting area and voting ID number. These will be used to keep pre-existing systems partially in place to increase redundancies. 

## App and website
Use a Azure Active Directory OAuth2 authentication to access account with the person's details including voter ID card number to cast vote. 
This app can be used to give information about the different people standing for elections and the party they are associated to. 
This app would be a Flutter app, which can be scaled to Android and iOS easily. 
Each account would be allowed to vote for only one party. 
(This model assumes that everyone either has a smartphone or has access to one.)

## Azure Key Vault
Use Azure Key Vault to link each account with the private and public keys. This will be used to link to an Etherum network.  

## Azure Blockchain Workstation
We use the Etherum network with the help of the Azure Blockchain Workstation to easily deploy it. We use each account as a Etherum user. Each account will ensure the vote of other accounts is done once, if not, then the ledger will remove the account's data completely and will add it later when another cycle comes up. After the voting period is over, the ledgers would be used to count the votes and thus give the accurate result, where no one could have tampered with it. 
