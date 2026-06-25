# homebrew-claude-switch

Homebrew tap for [claude-switch](https://github.com/hleidev/claude-switch) — switch
Claude Code's backend per terminal with one command.

## Install

```bash
brew tap hleidev/claude-switch
brew install claude-switch
claude-switch setup   # wires the `cs` shell function into your rc file
exec $SHELL
```

## Update

```bash
brew update && brew upgrade claude-switch
```

## Uninstall

```bash
brew uninstall claude-switch
cs uninstall          # removes shell integration; asks about config
```
