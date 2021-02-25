# My MacOS dev setup
## Firefox
- Set as default browser
- Login in Firefox sync (now with containers)
- Unlock Bitwarden key wallet
## System
- Show battery percentage on menu
- Show Bluetooth icon
- Mouse: uncheck "Natural scroll"
- Shortcuts
    - Remove command+arrow to move through spaces
    - **TODO** Add command to cycle through application windows
- Install Flycut for multiple clipboards
## Brew
Install the Brew package manager

## Python
`brew install python3`

`pip3 install --user pipenv`

## Other apps
- Fork (Git)
- VSCode
- Sketch

## VSCode extensions
- Python
- DotENV
- Vetur

## Setup SSH keys
**TODO**

## Node
LTS Version: 14 (until Oct21). Installed with `nodenv`:
```bash
$ brew install nodenv
$ nodenv install 14.16.0
$ nodenv global 14.16.0
$ touch ~/.zshrc
```
Then add `eval "$(nodenv init -)"` to `.zshrc` file.

## Font
- JetBrains Mono
- Google FiraCode
