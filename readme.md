# BIP39 Tool

A tool for converting BIP39 mnemonic phrases to addresses and private keys.

## Usage

Enter your BIP39 phrase into the 'BIP39 Phrase' field, or press
'Generate Random Phrase'

If required, set the derivation path, although the defaults are quite usable.

See the table for a list of addresses generated from the phrase.

Toggle columns to blank to easily copy/paste a single column of data, eg to
import private keys into a wallet or supply someone with a list of addresses.

The BIP32 keys can be used at [bip32.org](https://bip32.org) if desired.

# Side Notes

## Main reasons to use the tool

1. **Security**: Use the tool offline to ensure that your seed and private keys are never exposed to an internet connection.

2. **Wallet Backup and Restoration**: The seed generated by Ian Coleman allows you to restore all your keys and funds in any compatible wallet, simply by importing the seed + passphrase.

3. **Compatibility with Multiple Derivation Paths**: Supports BIP44, BIP49, and BIP84.

## Advantages

### 1. Offline Wallet Generation

Download the tool and run it on a computer disconnected from the internet. This way, your seed and private keys are never exposed, avoiding potential attacks or theft of funds.

### 2. Cold Wallet

When generating a seed on Ian Coleman, you should **write down the seed on paper** and store it in a safe place, as the seed is the only way to recover your wallet.

### 3. Creation of Multiple Addresses

The ability to use a new address for each transaction without needing to create a new wallet.

### 4. Self-custody

You have full control of your private keys.

## In addition...

The tool is effective for **accumulation** and **succession** of cryptocurrencies, as well as for address segregation when there isn’t much wallet movement. However, it has some limitations, such as:

1. It does not offer ways to **move** funds, as its operations are entirely manual.
2. It does not allow the **management** or **viewing** of balances and transactions for your addresses.

A good **usage strategy** is to use it to **generate the seed**. Then, wallets like **Electrum** or **BlueWallet** can be used to **manage** and **monitor** transactions using the key pairs derived from the seed generated by Ian Coleman.
