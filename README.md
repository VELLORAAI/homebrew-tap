# Dragon Code Homebrew tap

Install [Dragon Code](https://github.com/VELLORAAI/dragoncode-public-dist) with Homebrew on macOS (Apple Silicon) and Linux:

```sh
brew install velloraai/tap/dragon
```

Upgrade to the latest release:

```sh
brew upgrade dragon
```

Or tap first, then install:

```sh
brew tap velloraai/tap
brew install dragon
```

## Notes

- **Apple Silicon and Linux only.** There is no native Intel-Mac (`darwin-x64`) build; on Intel macOS the formula fails cleanly — use the [curl installer](https://github.com/VELLORAAI/dragoncode-public-dist) instead.
- Binaries are the same artifacts published to the [distribution repo](https://github.com/VELLORAAI/dragoncode-public-dist) releases; this tap just points Homebrew at them.
- `Formula/dragon.rb` is regenerated automatically by this repo's [`update-formula`](.github/workflows/update-formula.yml) workflow, which tracks the latest stable release in the [distribution repo](https://github.com/VELLORAAI/dragoncode-public-dist) — do not hand-edit the version or checksums.
