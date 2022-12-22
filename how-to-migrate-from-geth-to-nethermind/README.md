---
description: 'Here is a step-by-step procedure for migrating from Geth to Nethermind:'
---

# How to Migrate from Geth to Nethermind?

**1. Install Nethermind on your machine:**

* [x] Download the latest version of Nethermind from the official website (Nethermind.io/](https://downloads.nethermind.io/)) or the GitHub repository.
* [x] Follow the installation instructions provided to install Nethermind on your machine.

**2. Export your Geth data:**

* [x] Use Geth's "export" command to export your data as a JSON file.&#x20;

_For example, you can use the command `"geth export <filename>"` to export your account data. Replace \<filename> with the name you want to give to your exported data file._

3\. **Import your Geth data into Nethermind:**&#x20;

* [x] Use the "import" command to import your data from the JSON file you exported from Geth. For example, you can use the command `"nethermind import <filename>"` to import your account data.&#x20;

&#x20;        Replace `<filename>` with the name of your exported data file.

**4. Synchronize your data with the Ethereum network:**

* [x] Start Nethermind and allow it to sync with the network. This will ensure that your data is up-to-date and consistent with the Ethereum blockchain.

**5. Migrate your Ethereum address (optional):**

* [x] If you want to use the same Ethereum address with Nethermind that you were using with Geth, you will need to migrate your address.
* [x] To do this, export your private key from Geth and import it into Nethermind.
* [x] Keep your private key secure, and do not share it with anyone.
