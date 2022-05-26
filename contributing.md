# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test teleport https://github.com/gozer/asdf-teleport.git "tsh version"
```

Tests are automatically run in GitHub Actions on push and PR.
