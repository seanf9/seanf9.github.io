---
title: "Cold Storage"
date: 2021-11-02T13:08:40-05:00
draft: true
---

A great option for storing Bitcoin in cold storage is ColdCard.

Using this device with a microSD card, you are able to air gap the wallet entirely.

Use ColdCard with your own node: Use Specter Desktop with Bitcoin Core on your existing laptop

 #### Method 1: Specter + Core on existing laptop
* Download and double click install bitcoin core from bitcoin.org
* When running for the first time, the wizard popup allows you to select the radio button to use less hard drive space aka ‘pruned mode’. This allows you to save on hard drive space for ease of use. So while it will be an initial download of 360GB or so, it will only keep the last 5GB or so.
* Edit the bitcoin.conf file in your bitcoin app directory (using NotePad or similar) adding this line:
server=1
* Download and double click install the latest version of Specter Desktop from GitHub repo releases page here.
* When running Specter Desktop for the first time, it should automatically find your local Bitcoin Core instance
* Update your Coldcard firmware from the official Coldcard docs site
* Initialise your hardware wallet (e.g. Coldcard) (writing down the 24 seed words)
* Using microSD card, export the ‘Generic JSON’ file from the advanced – microSD menu
* Import that Generic JSON into your Specter Desktop to import the device
* Using that device, create a single signature wallet
* Save the Specter Backup file created as a backup of your wallet
* Use the receive tab on your newly created wallet to receive bitcoin from the exchange or other wallets


https://www.ministryofnodes.com.au/how-to-get-your-bitcoin-off-the-exchange-2021-edition

