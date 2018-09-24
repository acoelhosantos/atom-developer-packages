# atom-developer-packages

A curated list of Atom packages useful to software developers - [packages-list.txt](packages-list.txt).

## Requirements

- [Atom](https://atom.io/) editor
- [Atom shell commands](https://atom.io/packages/atom-shell-commands) installed
  - `atom` 1.30.0
  - `apm` 1.19.0

## How to install the list of packages

_Note: Commands tested on macOS High Sierra (10.13.6)._

```shell
apm install --compatible --packages-file packages-list.txt
```

## How to generate your list of packages

```shell
apm list --installed --dev --bare > packages-list.txt
```

## License

[MIT](LICENSE)
