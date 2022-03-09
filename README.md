# Arweave <> Polygon Bridge
> Live Demo: https://welightproject.github.io/Arweave-Polygon-Bridge/
## Introduction
This app demonstrates usage of the [`bundlr-client`](https://github.com/Bundlr-Network/js-client) to facilitate a bridge for users in Polygon to easily store data into Arweave, packaging them into bundles using a bundler from the [Bundlr Network](https://bundlr.network) app, and dispatching them to the Arweave network.

## Prerequistes
### Arweave
[Arweave](https://www.arweave.org) is a permanent storage network that enables you to store documents and applications forever.

### Polygon
[Polygon](https://polygon.technology) is a decentralised Ethereum scaling platform that enables developers to build scalable user-friendly dApps with low transaction fees without ever sacrificing on security.

### Bundlr

> Bundlr is Bundlr, not Bundler!

[Bundlr](https://bundlr.network) is a multi-chain layer 2 solution for Arweave which enables native support for Arweave storage on different smart contract blockchains using those networks' native tokens for storage payment.

## Features

- Allow the user to login with their Polygon wallet
- Use bundlr.network to store files with their MATIC tokens
- Use bundlr.network to store code/text with their MATIC tokens

## As TaiShang ArweaveUploadPlugin

This app enables Polygon users to easily store either small quantity or large quantity data onto Arweave with the assistance of the bundlr-client. Data is packaged into bundles using a bundler from Bundlr Network and dispatched to the Arweave network.

In the TaiShang Projects ecosystem, this application is regarded as a kind of "plug-in", so that other projects related to Arweave in the ecosystem can easily upload data onto the Arweave network by jumping or embedding iframe plugins.
For example, as shown in the following structure diagram:

![](/structure.png)

In this case, we use three examples of TaiShangArweaveUploaderPlugin to mark the interaction relationship with three different colors:

- TaiShang FaaS

Based on Arweave's FaaS system, code snippets written in languages such as Elixir/Rust can be pulled from the Arweave chain and loaded into Runtime to provide functional service support for other applications. Plugin is used for uploading code snippets.

- TaiShang NFT Renderer

TaiShang NFT renderer for rendering abstract NFTs. Plugin is used to upload resources.

- TaiShang Voxel Handler

TaiShang Voxel processor. Plugin is used to upload Voxel resources, convert Voxel Mint to NFT or transfer them to 3D printing device.
