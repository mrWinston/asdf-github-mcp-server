<div align="center">

# asdf-github-mcp-server [![Build](https://github.com/mrWinston/asdf-github-mcp-server/actions/workflows/build.yml/badge.svg)](https://github.com/mrWinston/asdf-github-mcp-server/actions/workflows/build.yml) [![Lint](https://github.com/mrWinston/asdf-github-mcp-server/actions/workflows/lint.yml/badge.svg)](https://github.com/mrWinston/asdf-github-mcp-server/actions/workflows/lint.yml)

[github-mcp-server](https://github.com/github/github-mcp-server) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add github-mcp-server
# or
asdf plugin add github-mcp-server https://github.com/mrWinston/asdf-github-mcp-server.git
```

github-mcp-server:

```shell
# Show all installable versions
asdf list-all github-mcp-server

# Install specific version
asdf install github-mcp-server latest

# Set a version globally (on your ~/.tool-versions file)
asdf global github-mcp-server latest

# Now github-mcp-server commands are available
github-mcp-server --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/mrWinston/asdf-github-mcp-server/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [mrWinston](https://github.com/mrWinston/)
