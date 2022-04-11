<div align="center">

# asdf-redo [![Build](https://github.com/chessmango/asdf-redo/actions/workflows/build.yml/badge.svg)](https://github.com/chessmango/asdf-redo/actions/workflows/build.yml) [![Lint](https://github.com/chessmango/asdf-redo/actions/workflows/lint.yml/badge.svg)](https://github.com/chessmango/asdf-redo/actions/workflows/lint.yml)


[redo](https://github.com/barthr/redo) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add redo https://github.com/chessmango/asdf-redo.git
```

redo:

```shell
# Show all installable versions
asdf list-all redo

# Install specific version
asdf install redo latest

# Set a version globally (on your ~/.tool-versions file)
asdf global redo latest

# Now redo commands are available
redo help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/chessmango/asdf-redo/graphs/contributors)!

# License

See [LICENSE](LICENSE)
