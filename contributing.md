# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test github-mcp-server https://github.com/mrWinston/asdf-github-mcp-server.git "github-mcp-server --version"
```

Tests are automatically run in GitHub Actions on push and PR.
