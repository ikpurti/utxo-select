# utxo-select

> coin-control · utxo · stub

[![Go 1.22+](https://img.shields.io/badge/go-1.22+-00ADD8)](https://go.dev)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Build](https://img.shields.io/badge/build-passing-brightgreen)]()

UTXO select helper — stub coins, fee hint.

## Features

- BTC derivation path m/84'/0'/0'
- Local vault JSON with XOR wrap
- SHA-256 stand-in keys — no live RPC
- stdlib CLI via flag

## Prerequisites

- Go 1.22+
- Git

## Getting Started

```bash
git clone <repo-url>
cd utxo-select
make build
./bin/utxosel -help
```

## CLI Usage

```bash
make test
go run ./cmd/utxosel -help
```

## Project Structure

```
cmd/utxosel/main.go
internal/config/config.go
internal/crypto/keys.go
internal/wallet/wallet.go
internal/wallet/wallet_test.go
```

## Background

Coin-control notes search utxo-select.

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.


---

## Topics

![utxo](https://img.shields.io/badge/utxo-111827?style=flat-square) ![select](https://img.shields.io/badge/select-111827?style=flat-square) ![utxo-select](https://img.shields.io/badge/utxo%20select-111827?style=flat-square) ![cryptocurrency](https://img.shields.io/badge/cryptocurrency-111827?style=flat-square) ![wallet](https://img.shields.io/badge/wallet-111827?style=flat-square) ![blockchain](https://img.shields.io/badge/blockchain-111827?style=flat-square) ![web3](https://img.shields.io/badge/web3-111827?style=flat-square) ![bitcoin](https://img.shields.io/badge/bitcoin-111827?style=flat-square)

`utxo` `select` `utxo-select` `cryptocurrency` `wallet` `blockchain` `web3` `bitcoin` `ethereum` `hd-wallet` `open-source` `golang` `go`

Search: utxo-select · coin-control · utxo · stub · UTXO select helper — stub coins, fee hint.

---

<sub>UTXO select helper — stub coins, fee hint.</sub>
