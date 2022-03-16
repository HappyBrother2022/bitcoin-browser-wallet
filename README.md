# Bitcoin Browser Wallet

A simple bitcoin wallet for your browser (Chrome Extension).

The Bitcoin Browser Wallet lets you easily send payments to anybody right from your browser. It detects bitcoin links on websites you're on to make payments fast and easy.
Your private key will be encrypted using your password and stored in Googles Sync storage, so you can access your wallet from any chrome browser.

This wallet uses the blockchain.info APIs for sending payments and retrieving balances.
The generated/imported private key is encrypted using a password and stored in the chrome sync/local storage

## Install

- download the wallet code from [github].
- Open chrome settings -> extensions
- check developer mode
- click "load unpacked extension"
- select either the "bitcoin-browser-wallet" folder, or the "dist" folder inside. ("dist" is the folder created when you run "$ grunt dist", which concatenates all js files)

## Tests

To run the tests, run the following from inside the bitcoin-browser-wallet folder

    $ karma start

## Deploy

This will create the dist folder, with concatenated and uglified js files.

$ grunt dist
