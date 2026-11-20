# Homebrew tap

Homebrew casks for [claude-sessions-sync](https://github.com/ashiqfardus/claude-sessions-sync),
which backs up Claude Code conversations to a synced folder and resumes them on another
computer.

```sh
brew install --cask ashiqfardus/tap/claude-sessions
```

Works on macOS and Linux. The binary is not signed by Apple, so the cask clears macOS's
quarantine flag after installing it; otherwise macOS refuses to run it the first time.

The casks are written by GoReleaser on each release. Do not edit them by hand.
