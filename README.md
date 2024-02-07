# WSL
Dotfiles og installasjon i WSL

## Install

### APT

``` sh
sudo apt install bat fzf
```

### Oh My ZSH

``` sh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

### ZSH Autosuggestion

``` sh
git clone https://github.com/zsh-users/zsh-autosuggestions $HOME/.oh-my-zsh/custom/plugins/zsh-autosuggestions
```

### Dotfiles

```
cp .vimrc .zshrc .zsh_aliases $HOME
```
