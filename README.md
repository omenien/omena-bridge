# `omena-bridge`

Rust bridge crate for CME-coupled Omena semantic graph surfaces.

`omena-semantic` owns generic style semantic contracts. This crate owns the
entry points that combine those contracts with CSS Module Explainer source
inputs such as `EngineInputV2`.

Current public products:

- `omena-bridge.cme-semantic-bridge`
- `omena-semantic.style-semantic-graph`
- `omena-semantic.selector-references`
- `omena-semantic.source-input-evidence`
- `omena-semantic.promotion-evidence`

`omena-semantic.source-input-evidence` includes value-domain derivation counts
from the source-backed expression-semantics payload.

Primary check:

```sh
cargo test
```
