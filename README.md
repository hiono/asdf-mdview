<div align="center">

# asdf-mdview [![Build](https://github.com/hiono/asdf-mdview/actions/workflows/build.yml/badge.svg)](https://github.com/hiono/asdf-mdview/actions/workflows/build.yml) [![Lint](https://github.com/hiono/asdf-mdview/actions/workflows/lint.yml/badge.svg)](https://github.com/hiono/asdf-mdview/actions/workflows/lint.yml)

[mdview](https://github.com/hiono/mdview) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add mdview
# or
asdf plugin add mdview https://github.com/hiono/asdf-mdview.git
```

mdview:

```shell
# Show all installable versions
asdf list-all mdview

# Install specific version
asdf install mdview latest

# Set a version globally (on your ~/.tool-versions file)
asdf global mdview latest

# Now mdview commands are available
mdview --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/hiono/asdf-mdview/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Hiro Ono](https://github.com/hiono/)
