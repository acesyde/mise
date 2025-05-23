# `mise plugins`

- **Usage**: `mise plugins [FLAGS] <SUBCOMMAND>`
- **Aliases**: `p`
- **Source code**: [`src/cli/plugins/mod.rs`](https://github.com/jdx/mise/blob/main/src/cli/plugins/mod.rs)

Manage plugins

## Flags

### `-c --core`

The built-in plugins only
Normally these are not shown

### `--user`

List installed plugins

This is the default behavior but can be used with --core
to show core and user plugins

### `-u --urls`

Show the git url for each plugin
e.g.: <https://github.com/asdf-vm/asdf-nodejs.git>

## Subcommands

- [`mise plugins install [FLAGS] [NEW_PLUGIN] [GIT_URL]`](/cli/plugins/install.md)
- [`mise plugins link [-f --force] <NAME> [DIR]`](/cli/plugins/link.md)
- [`mise plugins ls [-u --urls]`](/cli/plugins/ls.md)
- [`mise plugins ls-remote [-u --urls] [--only-names]`](/cli/plugins/ls-remote.md)
- [`mise plugins uninstall [-p --purge] [-a --all] [PLUGIN]…`](/cli/plugins/uninstall.md)
- [`mise plugins update [-j --jobs <JOBS>] [PLUGIN]…`](/cli/plugins/update.md)
