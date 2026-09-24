# AppLovinMediationIronSourceAdapter (X3M compatibility package)

Unofficial Swift Package Manager compatibility package published by X3M.
**Not affiliated with or endorsed by AppLovin.**

## Why this package exists

The official package <https://github.com/AppLovin/AppLovin-MAX-Swift-Package-IronSource.git> (tag `904020000.0.0`) depends on
<https://github.com/ironsource-mobile/Unity-Mediation-iAds-Swift-Package.git>. XMediator integrations use the LevelPlay SDK package
<https://github.com/ironsource-mobile/LevelPlay-Swift-Package.git> instead. This package's files are authored by X3M: its
`Package.swift` is generated from an X3M template using only factual values
read from the upstream manifest (names, version requirements, and the
adapter binary URL and checksum), with the SDK dependency pointing to the
LevelPlay SDK package. No upstream files are copied. No vendor binaries are
hosted here: the adapter binary is fetched from the official URL by SwiftPM.

## Usage

Depend on this repository (`https://github.com/x3mads/xmediator-applovin-max-ironsource-swift-package.git`) at tag `904020000.0.0` and
use the `AppLovinMediationIronSourceAdapter` product. Tags match the upstream adapter versions
one-to-one.

## License

The Apache License 2.0 in `LICENSE` covers only the X3M-authored content of
this repository. It does not license the AppLovin adapter, the LevelPlay
SDK, or any other vendor software or trademarks, which remain subject to
their owners' terms.
