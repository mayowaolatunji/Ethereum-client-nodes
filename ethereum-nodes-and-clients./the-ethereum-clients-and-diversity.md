# The Ethereum Clients & Diversity

## overview

Ethereum comprises two main parts: the consensus client and the execution client. The consensus client uses the proof-of-stake consensus mechanism to validate data from execution clients on the beacon chain. The execution client collects data on the network, executes it, and updates the new states.

Ethereum has a variety of Clients that are interoperable and written in different languages. However, currently, a majority of Ethereum nodes run on a single particular client, which can increase security risks if an attack or bug is detected on the dominant client.&#x20;

Before, the Ethereum mainnet used the proof-of-work consensus mechanism to validate transactions. However, in 2020, the beacon chain, the consensus layer for the proof-of-stake mechanism, began running parallel to the execution layer. After the merge was completed in September 2022, the beacon chain and execution client now work together to verify and update the state of Ethereum.



## Client Diversity

Ethereum has different clients that are majorly differentiated by their language but follow the same [specification](https://github.com/ethereum/consensus-specs)s. This diversity allows Ethereum nodes to disperse their operation in order to secure it from dominant client-related flaws or single-point failure. Ideally, no single client should power 33% of the Ethereum node because a single dominant client will have excess functional power and the majority of staked Ether in their control.

The current Data record shows that G0 Ethereum([Geth](https://geth.ethereum.org/docs/)) client has [over 71%](https://ethernodes.org/) Dominance and is unsafe for the entire network in case of a Bug or attack. Also, for the Consensus client, Lighthouse holds [over 61%](https://clientdiversity.org/) dominance.&#x20;

<figure><img src="https://lh6.googleusercontent.com/ns6ufP3YTXVmigJ38NKN04yA2EQhBR4N-an_-hw3UwkDkMDDW0Z9TWYoQ_sbCnCovSKQtHkVdE-Rwhcuh_VBwfT8gZ0u56fgtjcAMGkEe5LMmffAhWk6jD8F81nctAzXByS_ILY0YN_WEyGvQRm2hYoMjFC1Vu97ktjAvvzzniNAXBSfLAJ0VzzMULCatQ" alt="Ethereum client Dominance chart"><figcaption><p><a href="https://ethernodes.org/">Source: ethernodes.org</a></p></figcaption></figure>

<figure><img src="https://lh4.googleusercontent.com/0YE2XAd9FDJMuNbN1Q2HfOCUvj1Mqltx6i7ALoJ94RXdQ3NZUPx0ZwkKJ5bG53HD7aeBExYRbnQs34ciHQwf4Vdioxvk7x4wLGLa3vvO0575Bfo0-XALjhdJ64Hpk0CqPbpPVlB2WaWHM6z4C9cAQAa_YKwTOxX8j-ie4ggwvEbg_H-Jh_41Gyr2gLedqQ" alt=""><figcaption><p><a href="https://clientdiversity.org/">Source: Miga Lab</a></p></figcaption></figure>



## Real-time Client Diversity Advantages

* During the  Shanghai DevCon conference in 2016, hackers attacked [Ethereum](https://www.youtube.com/watch?v=nhr5nlMNvRQ) exploiting vulnerabilities in the Geth client software, causing a [distributed denial-of-service (DDoS) attack](https://blog.ethereum.org/2016/09/22/ethereum-network-currently-undergoing-dos-attack/?ref=hackernoon.com). While the Dev team tried to combat the vulnerability, the network was able to thrive on alternative clients.
* in 2021 Prysm [suffered a bug](https://github.com/prysmaticlabs/prysm/issues/8298) relating to invalid Eth1 deposit roots, which spread quickly because of its large validator share; this invalid root spread quickly through the network. Alternative client implementation was used to augment the situation.

\
