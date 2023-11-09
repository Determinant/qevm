> This repository is under development and experimental.

# qEVM: Quick/Quaint/Quality Ethereum Virtual Machine

In short, qEVM = EVM - janky stuff (stuff for ancient forks, terrible code,
etc.) + cool features (transaction-level parallelism, better composability).

qEVM is a clean rework of EVM from scratch in Rust, with a clear mind of
supporting its current instruction set to be able to run most of the smart
contracts compiled by solidity. It is what I would have done if I were
implementing the first EVM for the Ethereum client. It should be reusable
at different levels of abstraction and allow easy customization (storage,
checkpoints, caching policies, etc.) to adapt to a blockchain platform.

We hope to *eventually* replace the old EVM in the future if this initiative
turns out to work well.

One can always *run* faster without historical burden.
