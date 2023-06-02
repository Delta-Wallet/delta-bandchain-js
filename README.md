
# For deta Wallet DAPP Developer

## Using deta Wallet BandChain JS API


```
// config network
var network = {
    blockchain: "bandchain",
    chainId: "band-wenchang-mainnet"
};

// login
detaExtension.getIdentity(network)

// logout
detaExtension.forgetIdentity()

// sign transaction
detaExtension.requestSignature(transaction)
```

For details, please find the sample in this repo.


### Download deta Wallet 麦子钱包下载

[http://detawallet.org](http://detawallet.org)

If you would like to list your DAPP in deta Wallet, please follow the steps in http://blog.medishares.org/?p=398

如果您希望将您开发的DAPP加入麦子钱包，请查看 http://blog.medishares.org/?p=398

