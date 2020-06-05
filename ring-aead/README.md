# RustCrypto: *ring* AEAD trait wrappers

[![crate][crate-image]][crate-link]
[![Docs][docs-image]][docs-link]
![Apache2/MIT licensed][license-image]
![Rust Version][rustc-image]
[![CodeCov Status][codecov-image]][codecov-link]
[![Build Status][build-image]][build-link]

[`aead::AeadInPlace`] trait wrappers for high-performance implementations of
AES-GCM and ChaCha20Poly1305 in the [*ring*] crate.

[Documentation][docs-link]

## License

Licensed under either of:

 * [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0)
 * [MIT license](http://opensource.org/licenses/MIT)

at your option.

### Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Apache-2.0 license, shall be
dual licensed as above, without any additional terms or conditions.

[//]: # (badges)

[crate-image]: https://img.shields.io/crates/v/ring-aead.svg
[crate-link]: https://crates.io/crates/ring-aead
[docs-image]: https://docs.rs/ring-aead/badge.svg
[docs-link]: https://docs.rs/ring-aead/
[license-image]: https://img.shields.io/badge/license-Apache2.0/MIT-blue.svg
[rustc-image]: https://img.shields.io/badge/rustc-1.41+-blue.svg
[codecov-image]: https://codecov.io/gh/RustCrypto/AEADs/branch/master/graph/badge.svg
[codecov-link]: https://codecov.io/gh/RustCrypto/AEADs
[build-image]: https://github.com/RustCrypto/AEADs/workflows/ring-aead/badge.svg?branch=master&event=push
[build-link]: https://github.com/RustCrypto/AEADs/actions

[//]: # (general links)

[`aead::AeadInPlace`]: https://docs.rs/aead/latest/aead/trait.AeadInPlace.html
[*ring*]: https://github.com/briansmith/ring
