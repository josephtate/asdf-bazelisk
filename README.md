<div align="center">

# asdf-bazelisk [![Build](https://github.com/josephtate/asdf-bazelisk/actions/workflows/build.yml/badge.svg)](https://github.com/josephtate/asdf-bazelisk/actions/workflows/build.yml) [![Lint](https://github.com/josephtate/asdf-bazelisk/actions/workflows/lint.yml/badge.svg)](https://github.com/josephtate/asdf-bazelisk/actions/workflows/lint.yml)

[bazelisk](https://github.com/bazelbuild/bazelisk) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add bazelisk
# or
asdf plugin add bazelisk https://github.com/josephtate/asdf-bazelisk.git
```

bazelisk:

```shell
# Show all installable versions
asdf list-all bazelisk

# Install specific version
asdf install bazelisk latest

# Set a version globally (on your ~/.tool-versions file)
asdf global bazelisk latest

# Now bazelisk commands are available
bazelisk --print_env
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/josephtate/asdf-bazelisk/graphs/contributors)!

# License

See [LICENSE](LICENSE) (C) [Joseph S. Tate](https://github.com/josephtate/)
