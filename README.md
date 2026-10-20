
# MiMC

> [!WARNING]
> **This library is experimental software. It has not been fully audited and is not guaranteed to be secure. Expect bugs!**
>
> mimc is provided "as is", without warranty of any kind (see [LICENSE](LICENSE)). Bugs in this library can lead to under-constrained circuits, allowing invalid proofs to be accepted. Do not rely on it to protect real assets or sensitive data without your own independent review.

A Noir implementation of the MiMC hash function.

## Benchmarks

TODO


## Installation

In your _Nargo.toml_ file, add the version of this library you would like to install under dependency:

```
[dependencies]
mimc = { tag = "v0.1.0", git = "https://github.com/noir-lang/mimc" }
```
