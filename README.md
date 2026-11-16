# Buckler

Buckler is a menu bar app for macOS that finds compromised and vulnerable software on your Mac.

## Install

Buckler needs macOS 15 (Sequoia) or later.

```bash
brew tap caretak3r/buckler
brew trust caretak3r/buckler
brew install --cask caretak3r/buckler/buckler
xattr -dr com.apple.quarantine /Applications/Buckler.app
```

The documentation is at [silent.engineer/buckler](https://silent.engineer/buckler/).
