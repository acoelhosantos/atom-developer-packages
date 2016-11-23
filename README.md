# atom-developer-packages
A curated list of Atom packages useful to software developers - [packages-list.txt](packages-list.txt).

## Requirements
- [Atom](https://atom.io/) editor
- [Atom shell commands](https://atom.io/packages/atom-shell-commands) installed
  - ```atom``` 1.12.5
  - ```apm``` 1.12.9

## How to install the list of packages
*Note: Commands tested on macOS Sierra (10.12.1).*
```shell
apm install --compatible --packages-file packages-list.txt
```

The list was generated using the following command and options:
```shell
apm list --installed --dev --bare > packages-list.txt
```

## License
[MIT](LICENSE)
