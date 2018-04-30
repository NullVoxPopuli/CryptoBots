# CryptoBots
Trading bots, for anyone to use for educational or personal gain purposes.


## Development

### Submodules

This repo uses git submodules to manage cross-repo dependencies.
These submodules are readonly, and any issues that occur within the submodules should be brought up with that particular project

Submodules used:
- [CryptoExchangeClient](https://github.com/NullVoxPopuli/CryptoExchangeClient)

##### Adding
```
git submodule add https://github.com/NullVoxPopuli/CryptoExchangeClient.git modules/CryptoExchangeClient
```

##### Forcing Update
```
git submodule update --init --recursive
```

##### Removing

### Disclaimer

Anyone who has contributed to this repository is not responsible for any losses that occur.

Use with discretion.

While there are tests ensuring the intended behavior of these bots is correct, market conditions can always
lead to unexpected circumstances which result in a missed opportunity, resulting in stale orders.
