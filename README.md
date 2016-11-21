# atom-developer-packages
A curated list of Atom packages useful to software developers.

## Requirements
- [Atom](https://atom.io/) editor
- [Atom shell commands](https://atom.io/packages/atom-shell-commands) installed (```atom``` and ```apm```)

## How to generate/install a list of packages
Commands tested on macOS Sierra (10.12.1) and with the following versions:
- ```atom``` 1.12.5
- ```apm``` 1.12.9

### Generate list
```shell
apm list --installed --dev --bare > PACKAGES_FILENAME
```

### Install from list
```shell
apm install --compatible --packages-file PACKAGES_FILENAME
```
