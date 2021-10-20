<div align="center">

# asdf-frugal [![Build](https://github.com/charliestrawn/asdf-frugal/actions/workflows/build.yml/badge.svg)](https://github.com/charliestrawn/asdf-frugal/actions/workflows/build.yml) [![Lint](https://github.com/charliestrawn/asdf-frugal/actions/workflows/lint.yml/badge.svg)](https://github.com/charliestrawn/asdf-frugal/actions/workflows/lint.yml)

[frugal](https://github.com/Workiva/frugal) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `go`: golang install required to build the tool.

# Install

Plugin:

```shell
asdf plugin add frugal
# or
asdf plugin add frugal https://github.com/charliestrawn/asdf-frugal.git
```

frugal:

```shell
# Show all installable versions
asdf list-all frugal

# Install specific version
asdf install frugal latest

# Set a version globally (on your ~/.tool-versions file)
asdf global frugal latest

# Now frugal commands are available
frugal --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/charliestrawn/asdf-frugal/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Charlie Strawn](https://github.com/charliestrawn/)
