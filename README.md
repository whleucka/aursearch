# aursearch
Search and install Arch Linux packages with fzf.

A simple script to pipe results from `yay -Ss` to `fzf`. You can select the package you want to install
from the PUM.

<img src='https://i.ibb.co/34CZx61/Screenshot-from-2022-05-27-14-23-38.png' alt='screenshot' title='aursearch' />

#### Usage
Put the aursearch script in `~/.local/bin/` or whatever suits your needs.

Running the command:
```
aursearch name-of-package
```

Pressing enter installs the package via `yay`.

#### Requirements
- `fzf`
- `yay`
- `tmux` (optional for `fzf-tmux`)
