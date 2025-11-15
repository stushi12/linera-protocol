<!-- cargo-rdme start -->
fix: add safe satoshi arithmetic for overflow protection

Introducing a new module `linera_core accounting satoshi` that provides
safe addition of satoshi values using `u128` internally and checks
against a `MAX_SATOSHIS` limit to prevent integer overflow. This
improves robustness of accounting logic when summing large balances.

This module defines the core Linera protocol.

<!-- cargo-rdme end -->

## Contributing

See the [CONTRIBUTING](../CONTRIBUTING.md) file for how to help out.

## License

This project is available under the terms of the [Apache 2.0 license](../LICENSE).
