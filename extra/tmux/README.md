# Tmux Themes

Making your Tmux multiplexer colors match your Catppucino colors is easy! Simply copy the `.conf` file into your `.tmux.conf` (which should be located under `$HOME`).

The themes include the base color palette for the respective theme, most notably used for Tmux's statusline.

## Base config

In this directory you'd also find a [base config for Tmux](https://github.com/Pocco81/Catppuccino.nvim/blob/dev/extra/tmux/.tmux.conf) with useful comment to get you started if you don't already have one. In case you decide to use the base config, make sure to paste it in your `.tmux.conf` before the Catppucino theme you chose. You may as well copy the base first and then source the theme with the `source-file` on your `.tmux.conf`.

## Alacritty/Kitty Incompatibility

If you are having issues with the colors not displaying accordingly, see the [README from the Catppucino themes for Alacritty](https://github.com/Pocco81/Catppuccino.nvim/tree/main/extra/alacritty)
