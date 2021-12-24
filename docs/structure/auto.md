---
sidebar_position: 5
---

# Auto-scaling storage
------

## How does auto-scaling storage work?

The Main (Router) Canister caches 1000 event log data. When n>=1000, judge whether the current storage has reached the limit. Create a new storage when memorySize>7Gb, and start transferring data to the storage canister when memorySize<=7Gb , Record the starting index of the current canister log record. Synchronize data through index.

![images](/img/auto-scaling.svg)