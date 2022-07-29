# Uniswap Interface


An open source interface for Uniswap V2 -- a protocol for decentralized exchange of Ethereum tokens.

 

## Accessing the Uniswap Interface

To access the Uniswap Interface, use an IPFS gateway link from the
[website](https://ipfs.io/ipfs/QmW25cGaqCYszCsFEWbGL1utD5WQywVRrvKT2owsjFUG8m/).


## Development

### Install Dependencies

```bash
yarn
```

### Run

```bash
yarn start
```

### Configuring the environment (optional)

To have the interface default to a different network when a wallet is not connected:

1. Make a copy of `.env` named `.env.local`
2. Change `REACT_APP_NETWORK_ID` to `"{YOUR_NETWORK_ID}"`
3. Change `REACT_APP_NETWORK_URL` to e.g. `"https://{YOUR_NETWORK_ID}.infura.io/v3/{YOUR_INFURA_KEY}"` 

Note that the interface only works on testnets where both 
[Uniswap V2](https://uniswap.org/docs/v2/smart-contracts/factory/) and 
[multicall](https://github.com/makerdao/multicall) are deployed.
The interface will not work on other networks.

