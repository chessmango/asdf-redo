# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test redo https://github.com/chessmango/asdf-redo.git "REDO_HISTORY_PATH=~/.bash_history REDO_EDITOR=vim redo help"
```

Tests are automatically run in GitHub Actions on push and PR.
