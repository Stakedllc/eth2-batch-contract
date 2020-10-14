# ETH2 Deposit Batching Smart Contract

With the launch of ETH2 Phase One, owners of ETH will be able to deposit ETH to the canonical [ETH2 Deposit contract](https://github.com/ethereum/eth2.0-specs/blob/dev/solidity_deposit_contract/deposit_contract.sol) and become validators on the ETH2 Beacon Chain. The ETH2 Deposit contract only allows once deposit per transaction, while one needs to make one deposit per validator they wish to have.

Staked has created a smart contract that enables depositers to stake N ETH to N / 32 validators within a single transaction, with an upper bound of the block gas-limit. It offers high convenience for large ETH stakers and also saves them transaction costs.

## Technical

**Language:** Solidity

**Compiler:** `0.5.11`
