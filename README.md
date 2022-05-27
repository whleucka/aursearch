# aursearch
Search and install Arch Linux packages in fzf.

Behind the scenes, it is basically feeding
results from `yay -Ss` to fzf. You can select the package you want to install
from the PUM by pressing Enter.

<img src='https://i.ibb.co/34CZx61/Screenshot-from-2022-05-27-14-23-38.png' alt='screenshot' title='aursearch' />

#### Usage
Put the aursearch script in `~/.local/bin/` or whatever suits your needs.

Running the command:
```
aursearch name-of-package
```

Pressing enter installs the package via yay.

#### Requirements
- fzf 
- yay
- tmux (optional for fzf-tmux)
