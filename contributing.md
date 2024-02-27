# Contributing

## Issues and Pull Requests

Enter issues in the [GitHub Issue Tracker](https://github.com/josephtate/asdf-bazelisk/issues). Pull requests are
welcome.

## Developing

Fork this repository and create a new branch with your work in it. When finished, create a pull request against the main
branch in the parent repository.

### Testing Locally

To run this plugin locally, use the following commands.

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test bazelisk https://github.com/josephtate/asdf-bazelisk.git "bazelisk --print_env"
```

Tests are automatically run in GitHub Actions on push and PR.
