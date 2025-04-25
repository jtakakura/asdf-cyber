<div align="center">

# asdf-cyber [![Build](https://github.com/jtakakura/asdf-cyber/actions/workflows/build.yml/badge.svg)](https://github.com/jtakakura/asdf-cyber/actions/workflows/build.yml) [![Lint](https://github.com/jtakakura/asdf-cyber/actions/workflows/lint.yml/badge.svg)](https://github.com/jtakakura/asdf-cyber/actions/workflows/lint.yml)

[cyber](https://fubark.github.io/cyber/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add cyber
# or
asdf plugin add cyber https://github.com/jtakakura/asdf-cyber.git
```

cyber:

```shell
# Show all installable versions
asdf list-all cyber

# Install specific version
asdf install cyber latest

# Set a version globally (on your ~/.tool-versions file)
asdf global cyber latest

# Now cyber commands are available
cyber --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/jtakakura/asdf-cyber/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Junji Takakura](https://github.com/jtakakura/)
