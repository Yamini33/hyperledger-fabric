# Hyperledger Fabric

[![OpenSSF Scorecard](https://api.scorecard.dev/projects/github.com/hyperledger/fabric/badge)](https://scorecard.dev/viewer/?uri=github.com/hyperledger/fabric)
[![CII Best Practices](https://bestpractices.coreinfrastructure.org/projects/955/badge)](https://bestpractices.coreinfrastructure.org/projects/955)
[![Go Report Card](https://goreportcard.com/badge/github.com/hyperledger/fabric)](https://goreportcard.com/report/github.com/hyperledger/fabric)
[![GoDoc](https://godoc.org/github.com/hyperledger/fabric?status.svg)](https://godoc.org/github.com/hyperledger/fabric)
[![Documentation Status](https://readthedocs.org/projects/hyperledger-fabric/badge/?version=latest)](http://hyperledger-fabric.readthedocs.io/en/latest)
[![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/hyperledger/fabric/verify-build.yml?branch=main&label=build%20-%20main)](https://github.com/hyperledger/fabric/actions/workflows/verify-build.yml)
[![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/hyperledger/fabric/verify-build.yml?branch=release-2.5&label=build%20-%20release-2.5)](https://github.com/hyperledger/fabric/actions/workflows/verify-build.yml)
[![Security vulnerability scan](https://github.com/hyperledger/fabric/actions/workflows/vulnerability-scan.yml/badge.svg?branch=main)](https://github.com/hyperledger/fabric/actions/workflows/vulnerability-scan.yml)
[![GitHub go.mod Go version](https://img.shields.io/github/go-mod/go-version/hyperledger/fabric)](https://github.com/hyperledger/fabric/blob/main/go.mod)
[![GitHub Release](https://img.shields.io/github/v/release/hyperledger/fabric)](https://github.com/hyperledger/fabric/releases)

## Overview

**Hyperledger Fabric** is a **Graduated** project under the Hyperledger umbrella, designed for distributed ledger solutions. Its modular architecture provides high levels of confidentiality, resiliency, flexibility, and scalability. Hyperledger Fabric allows for pluggable implementations of various components, accommodating the complexities of different economic ecosystems.

This platform offers a uniquely elastic and extensible architecture, setting it apart from other blockchain solutions. Building on a fully-vetted, open-source framework, Hyperledger Fabric is an ideal starting point for enterprise blockchain initiatives.

Hyperledger Fabric

Hyperledger Fabric is a highly modular and scalable open-source blockchain framework, designed for enterprise-level distributed ledger solutions. It offers a unique approach to consensus, governance, and membership services, making it ideal for a variety of industries such as finance, supply chain, healthcare, and more.

Key features of Hyperledger Fabric include:

Permissioned Network: Unlike public blockchains, Hyperledger Fabric operates as a permissioned network where participants are known to each other, ensuring higher privacy and security.
Modular Architecture: Its plug-and-play design allows components such as consensus algorithms and membership services to be easily customized based on the network’s needs.
Smart Contracts (Chaincode): Hyperledger Fabric uses chaincode, written in languages like Go, Java, and JavaScript, for defining and executing business logic on the blockchain.
Private Data and Channels: It supports private transactions and confidential data through private channels and collections, enabling fine-grained data access control.
Pluggable Consensus Mechanism: This allows for flexibility in how transactions are validated and committed, enhancing the scalability and performance of the network.
Hyperledger Fabric is widely adopted for its ability to build permissioned blockchains that offer more control over network participants and data access, making it a preferred choice for enterprises.



## Releases

Hyperledger Fabric provides periodic releases with new features and improvements. Certain releases are designated as **Long-Term Support (LTS)**, ensuring that important fixes are backported during overlap periods.

### Current LTS Release:
- **[v2.5.x](https://hyperledger-fabric.readthedocs.io/en/release-2.5/whatsnew.html)**

### Historic LTS Releases:
- **[v2.2.x](https://hyperledger-fabric.readthedocs.io/en/release-2.2/whatsnew.html)** (maintenance ended February 2024)
- **[v1.4.x](https://hyperledger-fabric.readthedocs.io/en/release-1.4/whatsnew.html)** (maintenance ended April 2021)

For complete release notes, visit the **[GitHub releases page](https://github.com/hyperledger/fabric/releases)**.

## Documentation and Getting Started

To familiarize yourself with Hyperledger Fabric, visit our comprehensive online documentation:
- **[Getting Started with v2.5](http://hyperledger-fabric.readthedocs.io/en/release-2.5/)**
- **[Previous Versions](http://hyperledger-fabric.readthedocs.io/en/release-2.4/)**

We recommend that first-time users start with the **Getting Started** section to understand the components and basic transaction flow.

## Contributing

We welcome contributions to Hyperledger Fabric in various forms. There’s always plenty to do! Check our [contribution guidelines](http://hyperledger-fabric.readthedocs.io/en/latest/CONTRIBUTING.html) for more details on how to get involved.

## Community

Engage with the Hyperledger community:
- **[Hyperledger Community Meetup](https://www.meetup.com/pro/hyperledger/)**
- **[Mailing Lists and Archives](http://lists.hyperledger.org/)**
- **[Discord Chat](https://discord.com/invite/hyperledger)**
- **[Issue Tracking](https://github.com/hyperledger/fabric/issues)**

## License

Hyperledger Fabric source code is available under the **Apache License, Version 2.0 (Apache-2.0)**, and documentation files are under the **Creative Commons Attribution 4.0 International License (CC-BY-4.0)**.
