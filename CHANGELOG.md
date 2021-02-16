# Changelog

All notable changes to this project will be documented in this file.

*Unreleased*

## [v0.0.21] - 2021-02-10

### Added Features

- Provide staking validators option for users when trying to delegate funds


## [v0.0.20] - 2021-02-08

### Added Features

- Good handling of maximum transfer or staking transactions
- Show user the fee that is being deducted on the transaction
- Present UI/UX tag of the transaction status in the transfer transaction listing

### Security Fixes & Improvements

- Replace previous pre-encryption disk persistence by temporary memory state that's flushed later on


## [v0.0.13] - 2021-01-07

### Added Features

- The capability to modify current wallet node configurations were added (NodeURL and ChainID)
- Make address validation checks stricter on transfer, prevent input of wrong validator address

### Changed Behaviours
- Hiding devtools tab on production builds and only show it on dev mode

### Known Limitation

- This wallet is only testnet-ready, do not use in mainnet.
- Do not transfer any ERC20 tokens to addresses generated by this sample code as it can cause loss of funds.
- Crypto.com is not liable for any potential damage, loss of data/files arising from the use of the wallet.