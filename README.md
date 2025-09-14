# Descoped Homebrew Tap

Custom Homebrew formulas for Descoped projects.

## Installation

```bash
brew tap descoped/tap
```

## Available Formulas

### dddns
Lightweight Dynamic DNS client with multi-provider support

```bash
brew install descoped/tap/dddns
# or after tapping:
brew install dddns
```

## Updating Formulas

For maintainers: Use the Makefile to update formulas after new releases.

### Update dddns formula
```bash
make update-dddns VERSION=v0.1.1
```

## Adding New Formulas

1. Create a new `.rb` file in the `Formula/` directory
2. Follow Homebrew formula conventions
3. Test locally: `brew install --build-from-source Formula/<name>.rb`
4. Commit and push to this repository

## License

MIT License - See individual project repositories for details.
