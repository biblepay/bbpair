# BiblePay - Air Wallet

BiblePay's air wallet is an open-source wallet written entirely in javascript (with a tad of css and html).  

This standalone wallet does not store your private key anywhere (not in the browser, not in localstorage, not in hard drive storage, and not on the network), hence the name Air Wallet. 

Instead, the private key is derived every time you Log In (from 777 hashes of your strong private credentials).

This means you can run the air wallet in a virtual machine, off the network, and can sign and prepare a transaction without an application - however, the air wallet does need to be connected to the internet to show your balance
or actually Push a transaction.  (You can also receive funds in the air wallet while it is offline, since the private key corresponds to the public key in the wallet).

The air wallet requires strong passwords using a password strength meter to further secure the private key against brute-force attacks.

# Hosting
This air wallet is hosted on github, (this is so you know you are running the original version) -- or you can run it within your own home domain (or from your local machine from the file).  
It also works on mobile phones.
No matter where you run it from, when you click LogIn, your coin public key and private key will be the same, because they are deterministically generated from your credentials.
(Your credentials are only used to pull up your wallet).  Therefore you can recover your coins whether you log in from a library computer or a work computer or a home computer with this page.
You can even put the file on a flash drive and log in from a flash drive!  To back up your wallet, simply store your credentials somewhere safe.

Source Code:
* https://biblepay.github.io/airwallet/

(WARNING:  When running the air wallet, Always double check the address bar and ensure you are not running it from a domain other than your own, or from the BBP Github Repo!).

# BTC, LTC and DOGE Support
Bitcoin, Litecoin and Dogecoin transactions are created and signed locally and then sent to their own networks using api(s) provided by 
https://blockchair.com/ and https://www.blockcypher.com.

# Transaction Fees
The wallet enforces a minimum of `0.10 BBP`, `0.0001 BTC`, `0.001 LTC` and `1 DOGE` transaction fees and allows users to increase this fee. 
To help avoid situations in which rediculously high fees are paid by accident, the wallet enforces a maximum of `50 BBP`, `0.01 BTC`, `0.1 LTC` and `100 DOGE` in transaction fees.

# Change Addresses
By default, all change is sent back to the sender's address. To specify a custom change address, click on the change-address icon. 

# Notes
* To copy your address, click on the copy icon next to your address.
* To refresh your balance, click on the icon next to your balance.
* To view your balance in US dollars, click on your balance.
* To specify a custom change address, click on the change-address icon.
* To change/adjust the transaction fee, click on the wrench icon.
* To copy your private key, click on the key icon.

# License
Copyright (C) 2021 - BiblePay
This software is provided as is and with no warranty.

# Donation Addresses
BBP: BFi9nRxRsKZ1mWnxarTQk2bMKJ5Cza1rhz 

# Support
For support, post here:  https://forum.biblepay.org/index.php?topic=517.405

