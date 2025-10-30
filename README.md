# dotfiles

This repository uses
[zgenom](https://github.com/jandamm/zgenom)
as a plugin and load manager for zsh.

Zgenom will initialize
[Homebrew](https://github.com/Homebrew/brew)
for package management.

Additionally
[direnv](https://github.com/direnv/direnv)
is installed for project related environment management.

## Installation

```sh
git clone https://github.com/frieren21/dotfiles ~/.config
ln -nfs ~/.config/zsh/.zshrc ~/.zshrc
exec zsh
```
