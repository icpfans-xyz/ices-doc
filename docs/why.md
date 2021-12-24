---
sidebar_position: 2
---

# Why use ICES
------

The data on the Dfinity contract chain is determined by Canister itself. Each Cainster storage limit is 8Gb. Canister stores the business data of its own contract. In order to save storage space, it generally does not store log-level data. Limited by the storage size of Canister, if you need to store log event data, you need to consider implementing an expansion plan. This increases the complexity of the Canister contract and the difficulty of maintenance. This part of the log event data is not necessary, but we need it very much in order to analyze the data. Data storage at the log event level should be separated to provide a simple out-of-the-box functionality like a plug-in.



ICES exists to solve the above-mentioned repetitive and somewhat troublesome things. ICES not only provides log storage and analysis solutions, but also provides front-end display pages. It is simple to use, users do not need to consider storage issues, 100% of the log data is stored on the chain, and query APIs and display pages are provided.

