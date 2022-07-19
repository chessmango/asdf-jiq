<div align="center">

# asdf-jiq [![Build](https://github.com/chessmango/asdf-jiq/actions/workflows/build.yml/badge.svg)](https://github.com/chessmango/asdf-jiq/actions/workflows/build.yml) [![Lint](https://github.com/chessmango/asdf-jiq/actions/workflows/lint.yml/badge.svg)](https://github.com/chessmango/asdf-jiq/actions/workflows/lint.yml)


[jiq](https://github.com/fiatjaf/jiq) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add jiq https://github.com/chessmango/asdf-jiq.git
```

jiq:

```shell
# Show all installable versions
asdf list-all jiq

# Install specific version
asdf install jiq latest

# Set a version globally (on your ~/.tool-versions file)
asdf global jiq latest

# Now jiq commands are available
jiq --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/chessmango/asdf-jiq/graphs/contributors)!

# License

See [LICENSE](LICENSE)
