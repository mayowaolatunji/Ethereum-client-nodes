# Risk Scenario of single-Client dominance & Fixes

1. &#x20;Ethereum transactions reach finality when ⅔ of the nodes on the beacon chain validate it. And if the ⅓ of the nodes become inactive due to attacks or Bugs on client software, the Inactivity Leak Mechanism is activated. The beacon chain will use this mechanism to reduce the stakes of offline validators in order to make the ⅔ available for validation of the transaction.
2. &#x20;In the case where ½  of the nodes are running on an affected client, the beacon chain could split into two irrecoverable forks. This scenario can also lead to an inactivity leak mechanism.
3. &#x20;If more than 2/3 of nodes use the affected client, a new chain is split from the beacon chain. The faulty client has a supermajority and can issue finality to corrupt blocks, except the software bug is patched in 13 minutes.

## Quadratic inactivity leak mitigation.&#x20;

Quadratic inactivity leak is a mechanism used in Ethereum to encourage client diversity among the nodes participating in the network. This mechanism aims to prevent the network from becoming dominated by a small group of active nodes and encourage a more diverse set of nodes to participate in the network.

Quadratic inactivity leak is a penalty that is applied to nodes that have been inactive for an extended period of time. The penalty is designed to be quadratic in nature, meaning that it increases rapidly as the period of inactivity lengthens.&#x20;

To implement quadratic inactivity leaks, the network tracks the activity of each node over time. If a node is found to be inactive for a certain period of time, it may be subject to a penalty. The penalty may take the form of a reduction in the rewards earned by the node or an increase in the difficulty of the blocks it mines.



\
