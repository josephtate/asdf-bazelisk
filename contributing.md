# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test bazelisk https://github.com/josephtate/asdf-bazelisk.git "bazelisk --print_env"
```

Tests are automatically run in GitHub Actions on push and PR.
