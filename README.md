<div align="center">

  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://sublab.dev/logo_light.png">
    <img alt="Sublab logo" src="https://sublab.dev/logo.png">
  </picture>

</div>

[![CocoaPods Compatible](https://img.shields.io/cocoapods/v/encrypting-swift)](https://img.shields.io/cocoapods/v/encrypting-swift)
[![Swift](https://img.shields.io/badge/Swift-5.0.0-orange?style=flat-square)](https://img.shields.io/badge/Swift-5.0.0-Orange?style=flat-square)
[![Telegram channel](https://img.shields.io/badge/chat-telegram-green.svg?logo=telegram)](https://t.me/sublabsupport)
[![GitHub License](https://img.shields.io/badge/license-Apache%20License%202.0-blue.svg?style=flat)](http://www.apache.org/licenses/LICENSE-2.0)

# Sublab's Encrypting Swift library

This is a Swift repository which has different Encryptiong algorithms such as ecdsa, ed25519, and sr25519, that are currently supported by Substrate ecosystem to sign extrinsics.

We don't expect yet to implement more of the algorithms unless some Substrate network develops an app which introduces new algorithm.

But currently we're borrowing implementation of some algorithms from alien libraries.

This repository collects all these algorithms to proxy them with common interface for easier usage in other Sublab's repositories.

In addition to algorithms, this repository solves key pair generation routine using those algorithms. However, even though there are a few convenient functions to cover as much as possible cases, some might be missing.

## Sublab

At Sublab we're making mobile-first libraries for developers in [Substrate](https://substrate.io) ecosystem. However, we seek our libraries to be available not only for mobile Apple OS or Android OS, but compatible with any Swift/Kotlin environment: web servers, desktop apps, and whatnot.

Our mission is to to develop fully native open-source libraries for mobile platforms in Polkadot and Kusama ecosystems, covering everything with reliable unit-tests and providing rich documentation to the developers community. 

Our goal is to have more developers to come into the world of development of client applications in Substrate ecosystem, as we find this as most promising and intelligent blockchain project we ever seen. Thus, we as mobile development gurus trying to create enormously professional libraries which might be very complicated under the hood, but very simple and convenient for final developers.

## Installation

[CocoaPods](https://cocoapods.org) is a dependency manager for Cocoa projects. For usage and installation instructions, visit their website. To integrate Alamofire into your Xcode project using CocoaPods, specify it in your `Podfile`:

```ruby
pod 'EncryptingSwift'
```

## Documentation

- Our GitBook: [https://docs.sublab.dev/swift-libraries/encrypting-library](https://docs.sublab.dev/swift-libraries/encrypting-library)
- API reference: [https://api-reference.sublab.dev/encrypting-swift/](https://api-reference.sublab.dev/encrypting-swift/)

## Contributing

Please look into our [contribution guide](CONTRIBUTING.md) and [code of conduct](CODE_OF_CONDUCT.md) prior to contributing.

## Contacts

- Website: [sublab.dev](https://sublab.dev)
- E-mail: [info@sublab.dev](mailto:info@sublab.dev)
- Telegram support channel: [t.me/sublabsupport](t.me/sublabsupport)
- Twitter: [twitter.com/sublabdev](https://twitter.com/sublabdev)
