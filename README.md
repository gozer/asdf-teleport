<div align="center">

# asdf-teleport [![Build](https://github.com/gozer/asdf-teleport/actions/workflows/build.yml/badge.svg)](https://github.com/gozer/asdf-teleport/actions/workflows/build.yml) [![Lint](https://github.com/gozer/asdf-teleport/actions/workflows/lint.yml/badge.svg)](https://github.com/gozer/asdf-teleport/actions/workflows/lint.yml)

[teleport](https://goteleport.com/docs) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add teleport
# or
asdf plugin add teleport https://github.com/gozer/asdf-teleport.git
```

teleport:

```shell
# Show all installable versions
asdf list-all teleport

# Install specific version
asdf install teleport latest

# Set a version globally (on your ~/.tool-versions file)
asdf global teleport latest

# Now teleport commands are available
tsh version

# Override the architecture of installed binary
# For example, to install amd64 binary on and M1 Mac
TELEPORT_ARCH_OVERRIDE=amd64 asdf install telerpot latest
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/gozer/asdf-teleport/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Philippe M. Chiasson](https://github.com/gozer/)
