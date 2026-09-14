# Notchly Homebrew Tap

Install [Notchly](https://github.com/gronker22/Notchly) — the MacBook-notch
Dynamic-Island hub — with Homebrew:

```bash
brew tap gronker22/notchly
brew trust gronker22/notchly      # Homebrew 7+ requires trusting third-party taps once
brew install --cask notchly
```

Universal build (Intel + Apple Silicon), macOS Sonoma (14) or newer.

Because the app is unsigned, the first launch needs a right-click → **Open**
(or System Settings → Privacy & Security → **Open Anyway**). Update later with
`brew upgrade --cask notchly`.
