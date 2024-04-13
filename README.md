# asdf-butane

`asdf-butane` is a plugin for [asdf version manager](https://asdf-vm.com) that manages installations of [Butane](https://github.com/coreos/butane), a utility used to automatically generate machine-readable Ignition configs from human-readable Butane configs.

## Prerequisites

Before you begin, ensure you have installed `asdf` on your system. See the [asdf documentation](https://asdf-vm.com/guide/getting-started.html) for instructions.

## Installation

To install `asdf-butane` on your system, run the following command:

```bash
asdf plugin add butane https://github.com/thix/asdf-butane.git
```

## Usage

### List all available versions of Butane

```bash
asdf list-all butane
```

### Install a specific version of Butane

```bash
asdf install butane <version>
```

### Set a version globally (on your system)

```bash
asdf global butane <version>
```

### Set a version locally (in the current directory)

```bash
asdf local butane <version>
```

### Check current version

```bash
asdf current butane
```

### Uninstall a version

```bash
asdf uninstall butane <version>
```

## Contributing

Contributions are welcome! Feel free to submit a pull request to improve the plugin.

### Reporting Issues

Please report issues [here](https://github.com/thix/asdf-butane/issues) with a description of the problem, your operating system, asdf version, and any other relevant details.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
