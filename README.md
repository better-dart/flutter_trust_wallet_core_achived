# flutter_trust_wallet_core

- truset wallet core for flutter.
- support ios/android.


## Trust Wallet:

- https://github.com/trustwallet/wallet-core
- https://github.com/trustwallet/trust-wallet-ios
- https://github.com/trustwallet/trust-wallet-android-source
- https://github.com/trustwallet/trust-core

### Docs:

- https://developer.trustwallet.com/wallet-core/integration-guide/ios-guide
- https://developer.trustwallet.com/wallet-core/integration-guide/android-guide


## Platform Channels: 

- https://flutter.cn/docs/development/platform-integration/platform-channels
    - flutter call native codes.
- https://github.com/mintware-de/flutter_barcode_reader
    - a usage: write a flutter plugin with native binding.


## QuickStart:


```
flutter create --template=plugin --platforms=ios,android,windows,macos,linux,web flutter_trust_wallet_core

```

## Getting Started

This project is a starting point for a Flutter
[plug-in package](https://flutter.dev/developing-packages/),
a specialized package that includes platform-specific implementation code for
Android and/or iOS.

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

The plugin project was generated without specifying the `--platforms` flag, no platforms are currently supported.
To add platforms, run `flutter create -t plugin --platforms <platforms> .` under the same
directory. You can also find a detailed instruction on how to add platforms in the `pubspec.yaml` at https://flutter.dev/docs/development/packages-and-plugins/developing-packages#plugin-platforms.
