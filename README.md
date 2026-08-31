# homebrew-wxemo

Homebrew tap for [wxemo](https://github.com/cv-yushen/wxemo_mac) (private).

## Install

```bash
# Required for private GitHub sources
export HOMEBREW_GITHUB_API_TOKEN="$(gh auth token)"

brew tap cv-yushen/wxemo
brew install wxemo

wxemo status
wxemo wizard
```

## Upgrade

```bash
export HOMEBREW_GITHUB_API_TOKEN="$(gh auth token)"
brew update
brew upgrade wxemo
```
