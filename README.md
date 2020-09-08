# My Dot files
My dot and atom files

## Install
### iTerm
https://www.iterm2.com/downloads.html

### HomeBrew
```sh
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

### Dropbox
https://www.dropbox.com/install

### VSCode
https://code.visualstudio.com/download

### Postico
https://eggerapps.at/postico/



### Git
```
brew install git node yarn git-recent rbenv zsh direnv

```

### Ohmyzsh
```sh
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

## Pull Configs
```sh
git clone https://github.com/kiwiupover/dotfiles.git
```

### Volta
curl https://get.volta.sh | bash

Add node dependancies ember-cli and bower
```
volta install ember-cli bower yarn
```

### Editor Font
http://www.dafont.com/bitstream-vera-mono.font


## Symlink Files

```sh
cd ~
mkdir code
mkdir projects
ln -shi dotfiles/.gitconfig .gitconfig
ln -shi dotfiles/.zshrc .zshrc
ln -shi dotfiles/.gitignore_global .gitignore_global
ln -shi dotfiles/.githelpers .githelpers
ln -shi ~/dotfiles/vscode/settings.json ~/Library/Application\ Support/Code/User/settings.json
ln -Fshfiv ~/dotfiles/vscode/snippets/ ~/Library/Application\ Support/Code/User
```
