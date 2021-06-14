# awesome-ethereum-rollups

A list of resources related to increasing the throughput of transactions on the Ethereum mainnet.

## Rollups

- [An Incomplete Guide to Rollups](https://vitalik.ca/general/2021/01/05/rollup.html)
- [Hop: Send Tokens Across Rollups](https://ethresear.ch/t/hop-send-tokens-across-rollups/8581)
- [EVM optimistic rollup using Truebit](https://ethresear.ch/t/evm-optimistic-rollup-using-truebit/9318)

### Side chains and Layer 2

- [SIDECHAINS ARE NOT LAYER 2](https://www.gakonst.com/sidechains2019.pdf)
- [Why Smart Contracts are NOT feasible on Plasma](https://ethresear.ch/t/why-smart-contracts-are-not-feasible-on-plasma/2598)
- [OVM Deep Dive](https://medium.com/ethereum-optimism/ovm-deep-dive-a300d1085f52)
- [A note on bridges & layer-2 protocols](https://stonecoldpat.medium.com/a-note-on-bridges-layer-2-protocols-b01f8fc22324)
- [Pessimistic rollup: Scalable batched smart contract interactions](https://ethresear.ch/t/pessimistic-rollup-scalable-batched-smart-contract-interactions/7765)

## EIPs

- [EIP-2028: Transaction data gas cost reduction](https://eips.ethereum.org/EIPS/eip-2028)

## Electricity & Sustainability

- [Cambridge Bitcoin Electricity Consumption Index](https://cbeci.org/)

## Gas, Memory pool

- [Saving Gas on the Ethereum Mainnet](https://timdaub.github.io/2021/04/19/ethereum-web3-saving-gas-mainnet/)
- [Flashbots documentation](https://docs.flashbots.net/)

## Solidity

- [List of Solidity libraries in the wild](https://forum.openzeppelin.com/t/list-of-solidity-libraries-in-the-wild/2250)
- [ethereum/eth2.0-specs](https://github.com/ethereum/eth2.0-specs/blob/a553e3b18e77db954944d76994e40fb675b48009/ssz/merkle-proofs.md)

## Data Structures

- [Merkling in Ethereum](https://blog.ethereum.org/2015/11/15/merkling-in-ethereum/)

## Implementations

### Merkle Trees

sparse Merkle trees [can be gas optimized](https://ethresear.ch/t/optimizing-sparse-merkle-trees/3751). In the listing below, a ✔️ indicates that the authors claim to have made gas optimizations.

- [leapdao/leap-contracts SparseMerkleTree.sol](https://github.com/leapdao/leap-contracts/blob/3848ee1901f015ab9580922c602fc5921cfd1e67/contracts/SparseMerkleTree.sol) ✔️
- [loomnetwork/plasma-cash SparseMerkleTree.sol](https://github.com/loomnetwork/plasma-cash/blob/9f916cbd5d70f83a6da8b451eaa3d8881f444153/server/contracts/Core/SparseMerkleTree.sol) ✔️
- [thehubbleproject/hubble-contracts MerkleTree.sol](https://github.com/thehubbleproject/hubble-contracts/blob/402668797ff7454996323113128c693a87011c79/contracts/libs/MerkleTree.sol)
- [OffchainLabs/arbitrum MerkleLib.sol](https://github.com/OffchainLabs/arbitrum/blob/4f1a02688639f8f98f5357b30af5c437ba714553/packages/arb-bridge-eth/contracts/libraries/MerkleLib.sol)
- [ethereum-optimism/optimism MerkleTrie.sol](https://github.com/ethereum-optimism/optimism/blob/cc742715ecbca98248367d67f51a5f03038f5ba2/packages/contracts/contracts/optimistic-ethereum/libraries/trie/Lib_MerkleTrie.sol)
- [kautukkundan/pessimistic-swaps AccountTree.sol](https://github.com/kautukkundan/pessimistic-swaps/blob/afc6c7247ca7829dbbc9e47adc7e39c5c97783eb/contracts/AccountTree.sol)
- [OpenZeppelin/openzeppelin-contracts MerkleProof.sol](https://github.com/OpenZeppelin/openzeppelin-contracts/blob/9d5f77db9da0604ce0b25148898a94ae2c20d70f/contracts/utils/cryptography/MerkleProof.sol)

## Projects

- Optimistic Rollups:
  - [The Hubble Project](https://github.com/thehubbleproject)
  - [Arbitrum](https://github.com/OffchainLabs/arbitrum)
  - [Nutberry](https://github.com/NutBerry)
  - [Optimism](https://github.com/ethereum-optimism)
- Pessimistic Rollups:
  - [Pessimistic swaps](https://github.com/kautukkundan/pessimistic-swaps)
- Zero Knowledge Proof
  - [Cairo Programming Language](https://www.cairo-lang.org/)
- Rollup Interoperability
  - [hop.exchange](https://hop.exchange/)
