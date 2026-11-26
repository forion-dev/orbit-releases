# Orbit Downloads

Official desktop and Android builds of **Orbit by Forion**.

## Desktop

Download the latest desktop release from the [Releases page](https://github.com/forion-dev/orbit-releases/releases/latest). Each release includes:

- **Windows** — `Orbit-Setup-<version>.exe`
- **macOS** — `Orbit-<version>.dmg`
- **Linux** — `Orbit-<version>.AppImage`

The desktop app checks for updates automatically and installs them from this release channel.

## Android

Download the signed Android package directly:

**https://github.com/forion-dev/orbit-releases/releases/download/android/Orbit.apk**

Install it on your Android phone. Orbit is not currently distributed on Google Play. Future builds use the same application identity and signing key, so a newer APK installs over the existing app without losing your data.

## Verify a download

Every desktop release includes a `SHA256SUMS` file. Verify an installer before running it:

```sh
sha256sum -c SHA256SUMS
```

On macOS, use `shasum -a 256 -c SHA256SUMS`.

## Security

Please report security issues privately through GitHub Security Advisories rather than in a public issue. See [SECURITY.md](SECURITY.md).

## About

Orbit is built by [Forion](https://forion.ai). This repository hosts customer-facing release artifacts only.
