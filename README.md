<div align="center">
  <h1>BDK-RESERVES</h1>

  <img src="./static/bdk.png" width="220" />
  <br>
  <a href="https://www.aminagroup.com"><img src="./static/amina_logo.png" width="250" /></a>

  <p>
    <strong>Proof of reserves for Bitcoin dev kit</strong>
  </p>

  <p>
    <a href="https://crates.io/crates/bdk-reserves"><img alt="Crate Info" src="https://img.shields.io/crates/v/bdk-reserves.svg"/></a>
    <a href="https://github.com/bitcoindevkit/bdk-reserves/blob/master/LICENSE"><img alt="MIT or Apache-2.0 Licensed" src="https://img.shields.io/badge/license-MIT%2FApache--2.0-blue.svg"/></a>
    <a href="https://github.com/bitcoindevkit/bdk-reserves/actions?query=workflow%3ACI"><img alt="CI Status" src="https://github.com/ulrichard/bdk-reserves/workflows/CI/badge.svg"></a>
    <a href="https://docs.rs/bdk-reserves"><img alt="API Docs" src="https://img.shields.io/badge/docs.rs-bdk_reserves-green"/></a>
    <a href="https://blog.rust-lang.org/2022/08/11/Rust-1.63.0.html"><img alt="Rustc Version 1.63.0+" src="https://img.shields.io/badge/rustc-1.63.0%2B-lightgrey.svg"/></a>
    <a href="https://discord.gg/d7NkDKm"><img alt="Chat on Discord" src="https://img.shields.io/discord/753336465005608961?logo=discord"></a>
  </p>

  <h4>
    <a href="https://bitcoindevkit.org">Project Homepage</a>
    <span> | </span>
    <a href="https://docs.rs/bdk">Documentation</a>
  </h4>
</div>

## About

The `bdk` library aims to be the core building block for Bitcoin wallets of any kind.
The `bdk-reserves` library provides an implementation of `proof-of-reserves` for bdk.

* It produces and validates proofs in the form of PSBT's.
* The implementation was inspired by <a href="https://github.com/bitcoin/bips/blob/master/bip-0127.mediawiki">BIP-0127</a> and <a href="https://github.com/bitcoin/bips/blob/master/bip-0322.mediawiki">BIP-0322</a>.

## Sponsorship
The implementation of <b>bdk-reserves</b> was sponsored by <a href="https://www.aminagroup.com">AMINA Bank</a>.


## License

Licensed under either of

 * Apache License, Version 2.0
   ([LICENSE-APACHE](LICENSE-APACHE) or http://www.apache.org/licenses/LICENSE-2.0)
 * MIT license
   ([LICENSE-MIT](LICENSE-MIT) or http://opensource.org/licenses/MIT)

at your option.

## Minimum Supported Rust Version (MSRV)

This library should always compile with Rust **1.63.0**.

To build with the MSRV you will need to pin the below dependencies:

```shell
cargo update -p home:0.5.9 --precise 0.5.5
cargo update -p cc --precise 1.0.105
```

## Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Apache-2.0 license, shall be
dual licensed as above, without any additional terms or conditions.
