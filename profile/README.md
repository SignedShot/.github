<div align="center">
  
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/SignedShot/.github/main/profile/signedshot-logo-white.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/SignedShot/.github/main/profile/signedshot-logo.svg">
  <img alt="SignedShot" src="https://raw.githubusercontent.com/SignedShot/.github/main/profile/signedshot-logo.svg" height="60">
</picture>

**Signed at capture. Verified anywhere.**

An open protocol for proving photos and videos haven't been altered since capture—cryptographically, not by guessing.

</div>

## The Problem

Digital manipulation is easy. Anyone can alter a photo in seconds. Detection is an arms race that AI will always win. SignedShot takes a different approach: **prove authenticity at capture**, not detection after the fact.

## How It Works

Two layers of cryptographic proof:

1. **Capture Trust** — Server verifies the device is legitimate before capture
2. **Media Integrity** — Device signs the content hash using secure hardware

Together they prove: *"This exact content was captured on a real device, in a verified session, and hasn't been modified."*

## Repositories

| Repository | Description |
|------------|-------------|
| [signedshot-api](https://github.com/SignedShot/signedshot-api) | Backend API (Python/FastAPI) |
| [signedshot-ios](https://github.com/SignedShot/signedshot-ios) | iOS SDK + Example App |
| [signedshot-validator](https://github.com/SignedShot/signedshot-validator) | Rust CLI + Python library for verification |
| [signedshot-docs](https://github.com/SignedShot/signedshot-docs) | Technical documentation |

## Quick Links

- [Website](https://signedshot.io)
- [Documentation](https://signedshot.io/docs)
- [Interactive Demo](https://signedshot.io/demo)
- [Python Package (PyPI)](https://pypi.org/project/signedshot/)

## License

MIT — See individual repositories for details.
