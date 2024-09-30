# Merkly Use Case

## TL;DR

This PoC shows that it is possible to integrate:

- [MerkleTreeJs](https://github.com/merkletreejs/merkletreejs) (JavaScript)
- [Merkly](https://github.com/olivmath/merkly) (Python)
- [Keccaky](https://github.com/olivmath/keccaky) (Python)
- Solidity Smartcontract

## How to Work

1. Given a VIP list (addresses).
2. A merkle root is created with `Merkly` and `Keccaky`.
3. Using `ApeWorx`, deploy a contract in `Solidity` with the merkle root.
4. Frontend uses `Metamask` to login.
5. Frontend uses `MerkleTreeJs` to create merkle proof.
6. Frontend uses smartcontract `Solidity` to validate VIP.
