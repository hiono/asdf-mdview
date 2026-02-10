<div align="center">

# asdf-mdview

[mdview](https://gist.github.com/karunru/512b78b430fad751d2466b72da4a4893) plugin for the [asdf version manager](https://asdf-vm.com).

mdview is a Markdown viewer with mermaid-ascii support (glow wrapper).

Inspired by [karunru's Zenn article](https://zenn.dev/karunru/articles/989af4abf9d71f). Thanks for the wonderful script!

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `python3` - required to run the mdview script
- `glow` - required for markdown rendering
- `mermaid-ascii` - required for mermaid diagram conversion

# Install

Plugin:

```shell
asdf plugin add mdview
# or
asdf plugin add mdview https://github.com/hiono/asdf-mdview.git
```

mdview:

```shell
# Show all installable versions (commit hashes)
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

[Thanks goes to these contributors](https://github.com/karunru/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [karunru](https://karunru.github.io/)
