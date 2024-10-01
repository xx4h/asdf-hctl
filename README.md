<div align="center">

# asdf-hctl [![Build](https://github.com/xx4h/asdf-hctl/actions/workflows/build.yml/badge.svg)](https://github.com/xx4h/asdf-hctl/actions/workflows/build.yml) [![Lint](https://github.com/xx4h/asdf-hctl/actions/workflows/lint.yml/badge.svg)](https://github.com/xx4h/asdf-hctl/actions/workflows/lint.yml)

[hctl](https://github.com/xx4h/hctl) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add hctl
# or
asdf plugin add hctl https://github.com/xx4h/asdf-hctl.git
```

hctl:

```shell
# Show all installable versions
asdf list-all hctl

# Install specific version
asdf install hctl latest

# Set a version globally (on your ~/.tool-versions file)
asdf global hctl latest

# Now hctl commands are available
hctl version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/xx4h/asdf-hctl/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Fabian 'xx4h' Sylvester](https://github.com/xx4h/)
