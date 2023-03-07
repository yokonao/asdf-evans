<div align="center">

# asdf-evans [![Build](https://github.com/yokonao/asdf-evans/actions/workflows/build.yml/badge.svg)](https://github.com/yokonao/asdf-evans/actions/workflows/build.yml) [![Lint](https://github.com/yokonao/asdf-evans/actions/workflows/lint.yml/badge.svg)](https://github.com/yokonao/asdf-evans/actions/workflows/lint.yml)


[evans](https://github.com/yokonao/asdf-evans) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add evans
# or
asdf plugin add evans https://github.com/yokonao/asdf-evans.git
```

evans:

```shell
# Show all installable versions
asdf list-all evans

# Install specific version
asdf install evans latest

# Set a version globally (on your ~/.tool-versions file)
asdf global evans latest

# Now evans commands are available
evans --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/yokonao/asdf-evans/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [yokonao](https://github.com/yokonao/)
