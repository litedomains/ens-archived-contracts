# Archive Contracts

This repo includes the list of contracts before our contracts are consolidated into @ensdomains/ens-contracts

All the abi and compiled binaries are under `abi` dirctory.
All the source contract codes are under `contracts` directory.

Those includes some contracts which do no longer exist on `ens-contracts`

```
contracts/
├── ens-022
│   ├── Deed.sol
│   ├── DeedImplementation.sol
│   ├── ENS.lll
│   ├── ENS.lll.bin
│   ├── HashRegistrar.sol
├── ethregistrar-202
│   ├── OldBaseRegistrarImplementation.sol
│   ├── RegistrarMigration.sol
│   ├── ShortNameAuctionController.sol
│   ├── ShortNameClaims.sol

```

## How to install

```
npm install --save '@ensdomains/ens-archived-contracts'

```

## How to use

```
import { abi as oldResolverContract } from 'ensdomain-contracts/abis/ens-022/PublicResolver.json'
```

