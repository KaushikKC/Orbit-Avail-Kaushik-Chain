# Arbitrum Nitro Rollup Contracts - Orbit Avail Kaushik Chain

 
This package contains the smart contract code that powers Arbitrum Nitro and is customized for the Orbit Avail Kaushik Chain using Avail Data Availability (DA) and Arbitrum Orbit from scratch. The rollup operates with a Chain ID of 13339999.

It includes the rollup and fraud proof smart contracts, as well as interfaces for interacting with precompiles.

For more information, visit the Arbitrum Developer Docs.

For the deployed addresses of these contracts for Arbitrum chains, see Useful Addresses.

For the token bridge contracts, see Token Bridge Contracts.

## Setup Instructions

To compile and build these contracts locally, follow these steps:

```bash
git clone https://github.com/offchainlabs/nitro-contracts
cd nitro-contracts
yarn install
yarn build
```

## Additional Steps for Orbit Avail Kaushik Chain

1. Download avail-nitro-node Docker Image
To set up the data availability layer with Avail, download the avail-nitro-node image:

```bash
docker pull availj/avail-nitro-node:v2.1.0-upstream-v3.1.1

```
2. Add Docker Image in the Dockerfile
Integrate this Docker image in your Dockerfile to enable the use of Avail for data availability with Arbitrum Nitro.

## License

Nitro is currently licensed under a [Business Source License](./LICENSE.md), similar to our friends at Uniswap and Aave, with an "Additional Use Grant" to ensure that everyone can have full comfort using and running nodes on all public Arbitrum chains.

The Additional Use Grant also permits the deployment of the Nitro software, in a permissionless fashion and without cost, as a new blockchain provided that the chain settles to either Arbitrum One or Arbitrum Nova.

For those that prefer to deploy the Nitro software either directly on Ethereum (i.e. an L2) or have it settle to another Layer-2 on top of Ethereum, the [Arbitrum Expansion Program (the "AEP")](https://docs.arbitrum.foundation/assets/files/Arbitrum%20Expansion%20Program%20Jan182024-4f08b0c2cb476a55dc153380fa3e64b0.pdf) was recently established. The AEP allows for the permissionless deployment in the aforementioned fashion provided that 10% of net revenue is contributed back to the Arbitrum community in accordance with the requirements of the AEP.

## Contact

Discord - [Arbitrum](https://discord.com/invite/5KE54JwyTs)

Twitter: [Arbitrum](https://twitter.com/arbitrum)
