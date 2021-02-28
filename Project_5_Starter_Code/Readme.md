## Environment Version
Truffle v5.1.66 (core: 5.1.66)
Solidity v0.5.16 (solc-js)
Node v14.8.0
Web3.js v1.2.9
## ERC-721 Token Name
StarToken
## ERC-721 Token Symbol
STR
## Rinkeby Network Address
truffle migrate --reset --network rinkeby

Compiling your contracts...
===========================
> Everything is up to date, there is nothing to compile.



Migrations dry-run (simulation)
===============================
> Network name:    'rinkeby-fork'
> Network id:      4
> Block gas limit: 10000000 (0x989680)


1_initial_migration.js
======================

   Deploying 'Migrations'
   ----------------------
   > block number:        8149944
   > block timestamp:     1614478671
   > account:             0x7cBacA000D38123bfC13EE41648C48F1269C38AE
   > balance:             7.49789763
   > gas used:            210237 (0x3353d)
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.00210237 ETH

   -------------------------------------
   > Total cost:          0.00210237 ETH


2_deploy_contracts.js
=====================

   Deploying 'StarNotary'
   ----------------------
   > block number:        8149946
   > block timestamp:     1614478682
   > account:             0x7cBacA000D38123bfC13EE41648C48F1269C38AE
   > balance:             7.4797594
   > gas used:            1786460 (0x1b425c)
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.0178646 ETH

   -------------------------------------
   > Total cost:           0.0178646 ETH


Summary
=======
> Total deployments:   2
> Final cost:          0.01996697 ETH





Starting migrations...
======================
> Network name:    'rinkeby'
> Network id:      4
> Block gas limit: 10000000 (0x989680)


1_initial_migration.js
======================

   Deploying 'Migrations'
   ----------------------
   > transaction hash:    0xfe97e5b32aac644e94ac178df6dd96d717718b445720884011e8bb9a2f61cb0c
   > Blocks: 1            Seconds: 16
   > contract address:    0x51B54455B953E03a38CBb25cB75684122174D064
   > block number:        8149945
   > block timestamp:     1614478702
   > account:             0x7cBacA000D38123bfC13EE41648C48F1269C38AE
   > balance:             7.49774763
   > gas used:            225237 (0x36fd5)
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.00225237 ETH


   > Saving migration to chain.
   > Saving artifacts
   -------------------------------------
   > Total cost:          0.00225237 ETH


2_deploy_contracts.js
=====================

   Deploying 'StarNotary'
   ----------------------
   > transaction hash:    0x0cfcd025bef1483e9a5f30f25c6002bd24d2f0ebc248aa7d955c92d9b72373c3
   > Blocks: 1            Seconds: 12
   > contract address:    0x777dce5a33eF47Fb478E4D5012Ee4ACd1e81dbCc
   > block number:        8149947
   > block timestamp:     1614478732
   > account:             0x7cBacA000D38123bfC13EE41648C48F1269C38AE
   > balance:             7.4791594
   > gas used:            1816460 (0x1bb78c)
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.0181646 ETH


   > Saving migration to chain.
   > Saving artifacts
   -------------------------------------
   > Total cost:           0.0181646 ETH


Summary
=======
> Total deployments:   2
> Final cost:          0.02041697 ETH

