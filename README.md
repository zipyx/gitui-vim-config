# gitui config

My `gitui` configuration based on `vim` keybindings. The `key_bindings.ron` file in the repository is what you would
generally use.

### Key Config

The key symbols in the config are customizable and can be reconfigured to suite your own needs. This configuration
follows a `vim` style navigation

- `h`, `j`, `k`, `l` to navigate.

### Installation

As of date, the `key_bindings.ron` file must be placed in your `.config` directory. Since I'm using `linux` - the file
must be stored in:

- `~/.config/gitui/key_bindings.ron`

Here's a quick copy command. This will copy from within the repo directory (assuming your working directory is within the repo)

```bash
cp -rf key_bindings.ron ~/.config/gitui/
```

and that's sorted.
