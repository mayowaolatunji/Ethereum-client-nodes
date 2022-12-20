---
description: >-
  This documentation briefly explores the relationship between Nodes & Ethereum
  clients implementations.
---

# Ethereum Nodes & Clients.

A node is simply a connection junction that allows data entry and exit. In blockchain technology, a computer serves as a node. A network of computers runs software, known as clients, that makes verifying transactions or storage possible.

Ethereum Nodes are a set of computers that are admitted to contributing to the system by running an Ethereum implementation software. While a client is an Ethereum software that ensures & secures Ethereum protocol.

## Types of Nodes

Ethereum nodes can be distinguished based on their role in the Ethereum network.&#x20;

### A Full Node

&#x20;This type of Ethereum node stores a complete copy of the Ethereum blockchain and is responsible for validating all transactions and blocks. Full nodes are designed to support the operation of the Ethereum network by participating in the consensus process, which is the process by which the network reaches an agreement on the current state of the blockchain.

Full nodes are responsible for verifying all blocks and states, ensuring that the Ethereum network maintains a consistent and accurate record of all transactions by applying the Ethereum consensus rules to incoming blocks and transactions.

In addition to participating in the consensus process and verifying blocks and states, full nodes also serve as data sources for other nodes and clients. When requested, a full node can provide block headers, blocks, and transaction receipts to other nodes and clients, which can be used to synchronize their own copies of the blockchain and validate transactions.

### A Light Node

Light nodes are a type of Ethereum node that download only block headers rather than the full blocks. Block headers contain summary information about the contents of the blocks, including the state roots, which are hashes of the state data in the blocks. To access additional information, light nodes can request data from full nodes, which are nodes that store a complete copy of the Ethereum blockchain.

Light nodes are designed to enable users to participate in the Ethereum network with less powerful hardware and lower bandwidth requirements than full nodes. This makes it possible for light nodes to run on devices such as mobile phones or embedded devices, potentially expanding the reach of the Ethereum network to a wider range of devices.

While light nodes do not participate in the consensus process, they can still access the Ethereum blockchain with the same functionality and security guarantees as a full node. This is because light nodes can independently verify the data they receive from full nodes against the state roots in the block headers, ensuring that the data is consistent with the Ethereum consensus rules.

### Archival nodes

Archival nodes are Ethereum nodes that store a complete copy of the Ethereum blockchain and are designed to support historical data queries.&#x20;

Archival nodes are similar to full nodes in that they store all the data that full nodes keep, including block headers, blocks, and transaction receipts. However, unlike full nodes, archival nodes are not typically used for day-to-day operations on the Ethereum network. Instead, they are used to build an archive of historical states and to support research and analysis of the Ethereum blockchain and its history.

One reason to use an archival node is to query information about the Ethereum blockchain at a specific point in its history. For example, if you wanted to know the gas price at block #560,000, you could use an archival node to retrieve that information. Archival nodes can also be useful for testing your own transactions without having to mine them using tracing.

However, it's important to note that archival nodes store a large amount of data, which is measured in units of terabytes. This can make them less attractive for average users but can be useful for services like block explorers, wallet vendors, and chain analytics, which may require access to historical data on the Ethereum blockchain.

\
\
\
