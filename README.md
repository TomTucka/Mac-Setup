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

```bash
bash <(curl -fsSL https://raw.githubusercontent.com/tomtucka/dotfiles/main/setup.sh)
```

## 4. Setup SSH
## 5. Setup GPG
## 6. Reboot
