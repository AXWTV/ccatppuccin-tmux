# CCATPPUCCIN-TMUX
## Install 💻
Add this to your .tmux.conf and run Ctrl-I for TPM to install the plugin.
```bash
set -g @plugin 'AXWTV/ccatppuccin-tmux'
```
In order to have the icons displayed correctly please use/update your favorite
[nerd font](https://www.nerdfonts.com/font-downloads).
If you do not have a patched font installed, you can override or remove any
icon. Check the [documentation](./docs/reference/configuration.md) on the
options available.

1. (Optional) Set your preferred flavor, it defaults to `"mocha"`:

    ```bash
    set -g @catppuccin_flavor 'mocha' # latte, frappe, macchiato, mocha or black
    ```
<!-- x-release-please-end -->

> [!IMPORTANT]
> You may have to run `~/.config/tmux/plugins/tpm/bin/clean_plugins`
> To clean cache from an earlier version

## ![MyDotfiles:](https://github.com/AXWTV/Hyprland-DotFiles)
