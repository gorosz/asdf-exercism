<div align="center">

# asdf-exercism [![Build](https://github.com/gorosz/asdf-exercism/actions/workflows/build.yml/badge.svg)](https://github.com/gorosz/asdf-exercism/actions/workflows/build.yml) [![Lint](https://github.com/gorosz/asdf-exercism/actions/workflows/lint.yml/badge.svg)](https://github.com/gorosz/asdf-exercism/actions/workflows/lint.yml)


[exercism](https://exercism.org/cli-walkthrough) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add exercism
# or
asdf plugin add exercism https://github.com/gorosz/asdf-exercism.git
```

exercism:

```shell
# Show all installable versions
asdf list-all exercism

# Install specific version
asdf install exercism latest

# Set a version globally (on your ~/.tool-versions file)
asdf global exercism latest

# Now exercism commands are available
exercism --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/gorosz/asdf-exercism/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Gergely Orosz](https://github.com/gorosz/)
