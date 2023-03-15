---
title: Configurations
description: Learn how to configure your preferred wallet
---
Learn how to configure your preferred wallet

The SDK supports a veriety of wallets, including 

| Wallet      | Support | Type     |
| :---        |    :----:   |          ---: |
| In-game (new or restore)      | ✅       | In-app   |
| In-game (Web3auth)      | ✅       | In-app   |
| Phantom      | ✅       | External   |
| SMS      | 🏗       | In-app   |


## Interface
`IWalletBase` defines the common [interface](https://github.com/garbles-labs/Solana.Unity-SDK/blob/main/Runtime/codebase/IWalletBase.cs) 

The WalletBase abstract class implements `IWalletBase` interface and provides convenient methods shared by all wallet adapters. A few examples are:
* Connection to Mainnet/Devnet/Testnet or custom RPC
* Login/logout
* Account creation
* Get balance
* Get token accounts
* Sign/partially sign a transaction
* Send transaction


{% callout title="Additional methods" %} The complete list of methods is available [here](https://github.com/garbles-labs/Solana.Unity-SDK/blob/main/Runtime/codebase/WalletBase.cs) {% /callout %}

---
