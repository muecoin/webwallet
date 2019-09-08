# MonetaryUnit - Web Wallet

MUE's web wallet is an open-source wallet written in html, css and javascript. All signatures are handled on the client-side and private keys never leave the browser.
To secure the account of users who login with an email and password rather than a private key, the wallet hashes the email and passsword 144,000 times, and then uses the final hash to create an address and private key in the end.
The wallet also enforces very strong passwords using a password strength meter to further secure the accounts against brute-force attacks.

# Hosting
To avoid becoming a victim of phishing attacks, make sure you always double check the domain in your browser's address bar. You can also download the wallet and run it locally. But you're still going to need Internet in order to transact with the blockchain.

# BTC, LTC and DOGE Support
Bitcoin, Litecoin and Dogecoin transactions are created and signed locally and then sent to their own networks using api(s) provided by https://blockchair.com/ - https://www.blockcypher.com is also used for following up on transaction details.

# Login With Your Private Key(s)
You can login with a MonetaryUnit, Bitcoin, Litecoin or Dogecoin private key. If you login with a MonetaryUnit private key, the wallet will generate a Bitcoin, Litecoin and Dogecoin address using your MonetaryUnit private key. If you login with a Bitcoin private key, the wallet will generate a MonetaryUnit, Litecoin and Dogecoin address using your Bitcoin private key. And so will be the case if you login with a Litecoin or Dogecoin private key. It is however highly recommended to use email and password to login if you intend to stash all your cryptos in the same wallet per se, and only use the login with private key feature to spend your paper or brain wallets.

# Transaction Fees
The wallet enforces a minimum of `0.1 MUE`, `0.0001 BTC`, `0.001 LTC` and `1 DOGE` transaction fees and allows users to increase this fee. To help avoid situations in which ridiculously high fees are paid by accident, the wallet enforces a maximum of `0.2 MUE`, `0.01 BTC`, `0.1 LTC` and `100 DOGE` transaction fees.

# Change Addresses
By default, all changes are sent back to the sender's address. To specify a custom change address, click on the vial icon. You need to specify a custom change address everytime you login or switch between different coins, to override the default behavior.

# Notes
* To copy your address, click on the copy icon next to your address.
* To refresh your balance, click on the bolt icon next to your balance.
* To view your balance in US dollars, click on your balance.
* To specify a custom change address, click on the vial icon.
* To change/adjust the transaction fee, click on the wrench icon.
* To copy your private key, click on the key icon.
* To donate, click on the donate icon.

# License
Copyright (C) 2014-2019 MonetaryUnit Developers <br />
This software is provided as is and with no warranty under the MIT license.

# Donation Addresses
* MUE: `7qhVjgsbJWo1RRE7TNqyT4NWFAHBEKs8zL`

# Support
For support, join https://discordapp.com/invite/2jWUncm

# Whitepaper
To find out more about MonetaryUnit, consider visiting our website!
https://monetaryunit.org
