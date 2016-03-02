![alt text](https://github.com/bitDubai/media-kit/blob/master/MediaKit/Fermat%20Branding/Fermat%20Logotype/Fermat_Logo_3D.png "Fermat Logo")
​
# Digital Asset Store Bounty (Draft)
​
## Introduction
​
Is required a Digital Asset Store to allow publish digital asset available to sell to another Asset Users.
​
## Scope
​
### Current developments in progress
​
In the present, DAP is being changed and improved in the following way:
​
* Changes to Community Apps: actually no authorization is requested for connections between DAP actors. Asset Issuer, Asset User and Redeem Point community apps will me modified to perform connections only after authorization is received. [Issue #4692 on Github](https://github.com/bitDubai/fermat/issues/4692)
​
* Multiple network selection: all DAP wallets and sub apps will allow the selection of the NetworkType (MainNet, TestNet and RegTestNet) while all processes and transactions must still continue working as expected. [Issue #4693 on Github](https://github.com/bitDubai/fermat/issues/4693)
​
* Wallets GUI small improvements: we are enhancing the user experience by adding Search options, filter of data for assets with no positive balance, etc. [Issue #4694 on Github](https://github.com/bitDubai/fermat/issues/4694)
​
* BCH layer changes to support all network types: changes to BCH to support transactions in any network concurrently. [Issue #4658 on Github](https://github.com/bitDubai/fermat/issues/4658)
​
* Chat platform implementation: the team is involved in fixing issues on CHT platform to reach the demo ASAP. [Issue #4234 on Github](https://github.com/bitDubai/fermat/issues/4234)
​
* Assets Transfer: This transaction will be used to transfer assets between users (Asset User --> Asset User).
​
* Asset Sell: This transaction will allow the selling and buying of Assets between users (Asset User --> Asset User).
​
​

### Bounty scope

### To improve: Actor Asset User
Must include the basic data from digital asset availables to sell.

### To improve: Actor Asset Issuer
Must include the basic data from digital asset availables to sell.
​
### New Android App: Digital Asset Stock Wallet
This **Wallet** will allow the asset seller to manage it's stock, It should display available assets in it's **Asset Issuer Wallet** or  **Asset User Wallet**, display stock and allow assets destock and restock.
​
### New Android App: Digital Asset Store Wallet
This **Wallet** will allow the asset buyer to look at the available assets for sale, it must be capable of 
filtering by seller, type of integrated resource to the asset or both filters at once.
​
### New Android Wallet Module: Digital Asset Stock Wallet
Wallet module for Digital Asset Seller Wallet.
​
### New Android Wallet Module: Digital Asset Store Wallet
Wallet module for Digital Asset Store Wallet.
​
### New Middleware: Digital Asset Store Middleware
This plug in must be in charge of collecting all available assets for sale and provide methods to display 
information in order, or by filters requested by the buyer.
​
### New Transaction: Asset User Hold.
This plug in should be in the capacity to “Book” a digital asset that is available in the asset user wallet to be used in the digital asset store for sale and prevent it's distribution or transfer.

### New Transaction: Asset Issuer Hold.
This plug in should be in the capacity to “Book” a digital asset that is available in the asset issuer wallet to be used in the digital asset store for sale and prevent it's distribution or transfer.
​
### New Transaction: Asset Issuer Unhold.
This plug in should be in the capacity to remove the “reserve” status from a digital asset to prevent it's sale and have it available for it's distribution or transfer from a Asset Issuer Wallet.

### New Transaction: Asset User Unhold.
This plug in should be in the capacity to remove the “reserve” status from a digital asset to prevent it's sale and have it available for it's distribution or transfer from a Asset User Wallet.
​
### New Layer: Stock Transactions.
This new layer must contain the necessary transaction to perform stock movements within the Digital Asset Wallets.
​
### New Stock Transaction: Asset Issuer Restock.
This plug in must be in the capacity to perform a “hold” of a digital asset and make a credit in the digital asset issuer wallet store for that asset on hold.

### New Stock Transaction: Asset User Restock.
This plug in must be in the capacity to perform a “hold” of a digital asset and make a credit in the digital asset user wallet store for that asset on hold.
​
### New Stock Transaction: Asset Issuer Destock.
This plug in must be in the capacity to perform an unhold of a digital asset and make a debit in the digital asset issuer wallet for that Digital Asset.

### New Stock Transaction: Asset User Destock.
This plug in must be in the capacity to perform an unhold of a digital asset and make a debit in the digital asset user wallet for that Digital Asset.

​
#### New Wallet: Digital Asset Wallet Store.
This wallet must keep record of digital assets that will be available to sell and keeps the selling statistics
​
***To define tokenly plugin integration***    
​
***Once approved, the design will be completed in dev.fermat.org flows with much more detail***
     
​
## Timeline
​
Based on current workload and resouces available, the delivery date of this bounty will be **To define**.
​
## Evaluation
​
To be considered success this bounty must pass the following tests:
​
* Display the information of the available assets for sale through the Digital Asset Store UI.
* Have an UI able to manage the digital assets stock.
* Make the purchase and sale of Digital Asset Store assets
​
*[Evaluation results to be completed after evaluation]*
​
## Distribution
​
*[Distribution to be completed after evaluation]*
