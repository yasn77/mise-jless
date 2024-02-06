# Contributing

Testing Locally (you will need [asdf](https://asdf-vm.com/) installed):

```shell
mise plugin test <plugin-name> <plugin-url> [--mise-tool-version <version>] [--mise-plugin-gitref <git-ref>] [test-command*]

mise plugin test jless https://github.com/yasn77/mise-jless.git "jless version"
```

Tests are automatically run in GitHub Actions on push and PR.
