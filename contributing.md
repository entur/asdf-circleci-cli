# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test circleci-cli https://github.com/tommybo-entur/asdf-circleci-cli.git "circleci version"
```

Tests are automatically run in GitHub Actions on push and PR.
