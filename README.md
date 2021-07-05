# Mac-Setup
Tools installed on a fresh Mac

## 1. Install brew

```sh
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

## 2. Install deps

```sh
git clone https://github.com/tomtucka/Mac-Setup.git
cd Mac-Setup
# edit Brewfile to remove/add things
brew bundle
```

## 3. Install dotfiles

Outdated: follow instructions in https://github.com/tomtucka/dotfiles

```sh
git clone https://github.com/tomtucka/dotfiles.git ~/.dotfiles
cd ~/.dotfiles
./script/bootstrap
zsh
```

## 4. Setup SSH
## 5. Setup GPG
## 6. Reboot
