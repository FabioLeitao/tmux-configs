# tmux-configs

Personal [tmux](https://github.com/tmux/tmux) configuration: prefix `Ctrl+Space`, mouse, large scrollback, vim-style navigation, [TPM](https://github.com/tmux-plugins/tpm) plugins (catppuccin, yank, sensible, vim-tmux-navigator).

## Install

1. Install **tmux** 3.x and **git**.
2. Clone [TPM](https://github.com/tmux-plugins/tpm):

   ```bash
   git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
   ```

3. Copy or symlink this repo’s `tmux.conf` to the path tmux loads, for example:

   ```bash
   mkdir -p ~/.config/tmux
   ln -s "$(pwd)/tmux.conf" ~/.config/tmux/tmux.conf
   # or: cp tmux.conf ~/.config/tmux/tmux.conf
   ```

   Some setups use `~/.tmux.conf` instead; either works if tmux finds it (`tmux show -g`).

4. Start tmux and run **`<prefix> I`** (capital I) to fetch TPM plugins.

## License

See [LICENSE](LICENSE).
