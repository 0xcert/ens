# ENS

ENS module for ens domain management on the Ethereum blockchain.
The ENS module enables a secure and decentralized ENS domain management on the Ethereum blockchain. It maps human-readable names to machine-readable identifiers such as Ethereum addresses and vice versa.
Read more about about the [Ethereum Name Service](https://ens.domains/).

# Usage

## Init

```ts
// Provider is an instance of 0xcert framework provider.
const ens = new Ens(provider, NetworkKind.ROPSTEN);
```

## Resolve domain into address

```ts
const address = await ens.getAddress('domain.eth');
```

## Get domain from address

```ts
const domain = await ens.getDomain('address');
```

# Live example

Live example is available for ropsten network on codesandbox:
https://codesandbox.io/s/github/0xcert/ens-example?module=%2FREADME.md
