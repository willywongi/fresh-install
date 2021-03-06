# My MacOS dev setup
No links are provided since most of the software to download is a search-engine-query away.
## Firefox
- Set as default browser
- Login in Firefox sync (now with containers)
- Set DuckDuckGo as default search engine (looks like Firefox conveniently forgets this setting)
- Unlock Bitwarden key wallet
## System
- Show battery percentage on menu
- Show Bluetooth icon
- Mouse: uncheck "Natural scroll"
- Shortcuts
    - Remove command+arrow to move through spaces
    - Add command to cycle through application windows (Settings / Keyboard / Shortcuts / Keyboard / Show the next window): `⌘ \`
- Install Flycut for multiple clipboards; preferences:
    - General: Launch Flycut on login
    - Appearance: Menu item icon: Black scissors

## Brew
Install the Brew package manager

## Python

```bash
$ brew install python3
```

```bash
$ pip3 install --user pipenv
```
This is a user installation. If `pipenv` isn’t available in your shell after installation, you’ll need to add the user base’s binary directory to your `PATH`.
1. Get the *base* path from: `python3 -m site --user-base`
2. Open the shell profile file in an editor: `vi ~/.zshrc`
3. Add the path to `PATH`: `export PATH=$PATH:<the base path from before>/bin`. Notice we added `/bin` at the end.

## Other apps
- Fork (Git)
- VSCode
- Sketch
- Docker Desktop Community Edition:
    - I used to have an hard time figuring out the [download page](https://hub.docker.com/editions/community/docker-ce-desktop-mac/).

## VSCode extensions
- Python
    - Change language server to Pylance (follow instructions)
    - no need for a linter now.
- DotENV
- Vetur
- [Django](https://marketplace.visualstudio.com/items?itemName=batisteo.vscode-django)

## Setup SSH keys
Fork did that for me. I then copy/pasted the public key in my Github profile.

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
- [FiraCode](https://github.com/tonsky/FiraCode)
- JetBrains Mono
