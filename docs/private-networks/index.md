---
description: Private networks overview
---

# Hyperledger Besu for private networks

You can use Besu to develop enterprise applications requiring secure, high-performance transaction
processing in a private network.

A private network is a network not connected to Ethereum Mainnet or an Ethereum testnet.
Private networks typically use a different [chain ID](../public-networks/concepts/network-and-chain-id.md) and
proof of authority consensus ([QBFT](how-to/configure/consensus/qbft.md),
[IBFT 2.0](how-to/configure/consensus/ibft.md), or [Clique](how-to/configure/consensus/clique.md)).

You can also [create a local development network](tutorials/ethash.md) using proof of work (Ethash).

Besu supports enterprise features including [privacy](concepts/privacy/index.md) and
[permissioning](concepts/permissioning/index.md).

Get started with the [Developer Quickstart](tutorials/quickstart.md) to rapidly generate local
blockchain networks.
