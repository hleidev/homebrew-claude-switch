# homebrew-claude-switch

Homebrew tap for [claude-switch](https://github.com/hleidev/claude-switch) — switch
Claude Code's backend per terminal with one command.

The cask in this tap is generated automatically by
[GoReleaser](https://goreleaser.com) on every tagged release of the main repo.

## Install (macOS)

```bash
brew tap hleidev/claude-switch
brew install --cask claude-switch
claude-switch setup   # wires the `cs` shell function into your rc file
exec $SHELL
```

> Linux: Homebrew casks are macOS-only. Download the binary for your arch from the
> [latest release](https://github.com/hleidev/claude-switch/releases/latest)
> instead, or build from source.

## Update

```bash
brew update && brew upgrade --cask claude-switch
```

## Uninstall

```bash
brew uninstall --cask claude-switch
cs uninstall          # removes shell integration; asks about config
```
