# EQUITYY-voucher

EQUITYY Vouchers is the DeFi application for users to customize their financial instruments as Vouchers. Through the smart contract of Solv Vouchers, digital assets like tokens could be transformed into Vouchers representing investment allocations as splittable, composable NFTs.

This repository contains the core smart contracts for EQUITYY Protocol V2, along with their configuration files, initialization scripts and deployment information.

More information about EQUITYY Protocol:

- Official Website: 
- Documentation: 

## Structure

Smart contracts are packaged into four sub-projects, all contained in the `packages` directory.

### EQUITYY-token

[`EQUITYY-token`](./packages/EQUITYY-token) contains the smart contract of the standard ERC-20 token `EQUITYY`.

### EQUITYY-vnft-core

[`EQUITYY-vnft-core`](./packages/EQUITYY-vnft-core) contains the interface definition of the `VNFT` protocol and the implemention of which to represent splittable, composable Financial NFTs.

### EQUITYY-voucher

[`EQUITYY-voucher`](./packages/EQUITYY-voucher) contains the core smart contracts of `Vouchers` and its `VestingPool`, along with the initialization scripts and deployment information. 

By utilizing the VNFT token standard, the smart contracts of `EQUITYY-voucher` allow digital assets to be transformed into Vouchers representing investment allocations as splittable, composable NFTs.

### solver

[`solver`](./packages/solver) contains the smart contract of the manager `Solver`, which provides abilities to enable/disable Vouchers, as well as verify permissions whether users have or not to proceed operations such as depositing, withdrawing and transferring.

