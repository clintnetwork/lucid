# About Lucid ᵏᵛ - [[Project Move Here]](https://github.com/lucid-kv/lucid)

High performance and distributed KV store accessible through an HTTP API. Written in Rust. 🦀

[![Build Status](https://github.com/lucid-kv/lucid/workflows/Lucid/badge.svg)](https://github.com/lucid-kv/lucid/actions?workflow=Lucid)
[![Made with Rust](https://img.shields.io/badge/Made%20With-Rust-dea584)](https://www.rust-lang.org/)
[![License](https://img.shields.io/badge/license-MIT-lightgrey.svg)](https://github.com/clintnetwork/lucid/blob/master/LICENSE.md)
[![Telegram](https://img.shields.io/badge/t.me-clintnetwork-informational.svg)](https://t.me/clintnetwork)
[![Twitter](https://img.shields.io/twitter/follow/clint_network.svg?style=social)](https://twitter.com/intent/follow?screen_name=clint_network)

## Introduction

Lucid is currently in an embryonic state but we wish to achieve a fast, secure and distributed key-value store accessible through an HTTP API, we also want to propose persistence, encryption, WebSocket streaming, replication and a lot of features.

## Works Progress

<ins>__**Warning: Empty project for now, the development is ensured in the [development](https://github.com/lucid-kv/lucid/tree/development) branch.**__</ins>

- [x] Minimum Viable Product (MVP)
  - [x] Initialization process
  - [x] Configuration files handling
  - [x] JWT token Issuing
  - [ ] HTTPS Support
  - [x] Rest API
     - [x] KV-Base, HashMap-based
     - [ ] JWT Authentication
- [ ] WebUI in VueJS
- [ ] Persistence
- [ ] Encryption on the Fly (AES-256)
- [ ] Access Control List (ACL)
- [ ] WebSocket or Event Source (SSE)

## Some Use Cases

- Private Keys Storing (for a wallet by example)
- IoT: collect and save statistics data
- A distributed cache for an application
- Service Discovery
- Distributed Configuration
- Blob Storage

## Command Line Interface

[![asciicast](https://asciinema.org/a/277538.svg)](https://asciinema.org/a/277538)

## Web Interface (UI)

Lucid wants to propose a web UI to manage data, issue tokens, organize nodes and configure instances.

## About the Author

Lucid is powered by [Clint.Network](https://twitter.com/clint_network) and published under the [MIT License](LICENSE.md).

**Donate to Clint.Network**
- ![Paypal](https://raw.githubusercontent.com/reek/anti-adblock-killer/gh-pages/images/paypal.png) Paypal: [Donate](http://paypal.me/clintnetwork)
- ![btc](https://raw.githubusercontent.com/reek/anti-adblock-killer/gh-pages/images/bitcoin.png) Bitcoin: 3AEqgvpiHC2LzPDunf6PBPBLeT98YruKmg
