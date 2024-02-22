IPLD core
=========

[![Crates.io](https://img.shields.io/crates/v/ipld-core.svg)](https://crates.io/crates/ipld-core)
[![Documentation](https://docs.rs/ipld-core/badge.svg)](https://docs.rs/ipld-core)

This crate provides core types for interoperating with [IPLD]. Codecs are not part of this crate, they are independent, but rely on `ipld-core`.

The code is based on [`libipld-core`].

[IPLD]: https://ipld.io/
[`libipld-core`]: https://crates.io/crates/libipld-core


Features
--------

 - `std`: Makes the error implement `std::error::Error`.
 - `serde`: Enables support for Serde serialization into/deserialization from the `Ipld` enum.
 - `arb`: Enables support for property based testing.


License
-------

Licensed under either of

 * Apache License, Version 2.0 ([LICENSE-APACHE](LICENSE-APACHE) or http://www.apache.org/licenses/LICENSE-2.0)
 * MIT license ([LICENSE-MIT](LICENSE-MIT) or http://opensource.org/licenses/MIT)

at your option.