# Dirk

[![Tag](https://img.shields.io/github/tag/attestantio/dirk.svg)](https://github.com/attestantio/dirk/releases/)
[![License](https://img.shields.io/github/license/attestantio/dirk.svg)](LICENSE)
[![GoDoc](https://godoc.org/github.com/attestantio/dirk?status.svg)](https://godoc.org/github.com/attestantio/dirk)
![Lint](https://github.com/attestantio/dirk/workflows/golangci-lint/badge.svg)
[![Go Report Card](https://goreportcard.com/badge/github.com/attestantio/dirk)](https://goreportcard.com/report/github.com/attestantio/dirk)

An Ethereum 2 distributed remote keymanager.

## Table of Contents

- [Install](#install)
  - [Binaries](#binaries)
  - [Docker](#docker)
  - [Source](#source)
- [Usage](#usage)
- [Maintainers](#maintainers)
- [Contribute](#contribute)
- [License](#license)

## Install

### Binaries

Binaries for the latest version of `dirk` can be obtained from [the releases page](https://github.com/wealdtech/dirk/releases/latest).

### Docker

You can obtain the latest version of `dirk` using docker with:

```
docker pull attestant/dirk
```

### Source

`dirk` is a standard Go module which can be installed with:

```sh
go get github.com/attestantio/dirk
```

## Usage
`dirk` provides an interface to wallet operations such as listing accounts and signing requests.  The daemon provides a number of security measures to avoid unauthorised uses of the private keys, and protection against invalid actions (_e.g._ slashing events).

## Documentation
The following documentation is available:

  - [Getting started](docs/getting_started.md) an introduction to configuring Dirk
  - [Distributed key generation](docs/distributed_key_generation.md) setting up multiple instances of Dirk to carry out distributed key generation
  - [Prometheus metrics](docs/metrics/prometheus.md) Prometheus metrics
  - [Configuration](docs/configuration.md) Sample annotated configuration file
  - [Permissions](docs/permissions.md) Details information about Dirk's permissions

## Maintainers

Jim McDonald: [@mcdee](https://github.com/mcdee).

## Contribute

Contributions welcome. Please check out [the issues](https://github.com/attestantio/dirk/issues).

## License

[Apache-2.0](LICENSE) © 2020 Attestant Limited.
