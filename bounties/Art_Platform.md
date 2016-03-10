![alt text](https://github.com/bitDubai/media-kit/blob/master/MediaKit/Fermat%20Branding/Fermat%20Logotype/Fermat_Logo_3D.png "Fermat Logo")
​
# Art Platform Bounty
​
## Introduction
​
The main objective of ART platform is to connect artist and fan type Fermat actors, additionally, provide a route to the artists websites for exchange of tokens for songs and the creation of a “wallet” to submit to fans a purchased songs catalog directly from the artist.

This document describes the scope, design and timeline for this development.
​
## Scope
​
### Current developments in progress
​

For this version we will use **Tokenly** as external system for **"tokens"** management, currently Tokenly public API only allows to consult the catalog of tokens of a system user (swapbot) and check the status of exchange transactions of tokens for services (token slots). Additionally, Tokenly is developing a website for downloads of songs bought through tokens, but, it's in a very early stage of development and it doesn't provide a public API. We will develop a plugin to manage this Tokenly API (WRD – API – Tokenly) with the current status of said platform
​
​
### Bounty scope
​
### New Android App: Fan song wallet.
This **Wallet** will allow the fan to review a list of artist connected to the fan that have an active account in **Tokenly**. Also, it must show available songs on the local storage device and display songs purchased through **Tokenly**.
​
### New Android Sub-App: Artist Community
This sub app will provide a list of Artists Actors registered on the platform and the functionality to connect a Fermat actor with any of the artist displayed in the list.
​
### New Android Sub-App: Fan Community
This sub app will provide a list of Fans actors registered on the platform and the functionality to connect a Fermat actor with any Fans displayed in the list.
​
### New Android Sub-App: Artist Identity
This sub app will provide the functionality to create an identity as an Artist on the platform.
​
### New Android Sub-App: Fan Community
This sub app will provide the functionality to create an identity as an Fan on the platform.
​
### New Wallet Module: Fan song wallet
Wallet module for Fan song wallet.
​
### New Sub app Module: Artist Community
Sub app module for Artist Community.
​
### New Sub app Module: Fan Community
Sub app module for Fan Community.
​
### New Sub app Module: Artist Identity
Sub app module for Artist Identity.
​
### New Sub app Module: Fan Identity
Sub app module for Fan Identity.
​
### New Wallet: Fan Song Wallet
This plugin must register credits and debits of songs obtained through **Tokenly**.
​
### New Identity: Artist.
This plugin must have the ability to create an Artist identity in Fermat.
​
### New Identity: Fan.
This plugin must have the ability to create an Fan identity in Fermat.
​
### New Actor Network Service: Artist.
This plugin should be able to allow connections to a remote Artist and return the list of Artists connected to the system.
​
### New Actor Network Service: Fan.
This plugin should be able to allow connections to a remote Fan and return the list of fans connected to the system.
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


* Create a Fan identity.
* Create an Artist identity.
* Display artists connected to a Fan.
* Allow the device to route the URL to the external management system of tokens.
* Display the list of songs purchased through the external management system of tokens.
* Play a song on the device.

*[Evaluation results to be completed after evaluation]*
​
## Limitations
​
The following limitations when evaluating the platform should be considered:
​

* The state of the P2P Fermat platform.
* The external and internal Tokenly's API implementation.

​
## Distribution
​
*[Distribution to be completed after evaluation]*
