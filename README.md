# zsh

install zsh and ohmyzsh:
```bash
sudo apt install zsh git -y
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

---

### Install plugins

move to plugins directory:
```bash
cd ~/.oh-my-zsh/custom/plugins
```

clone plugins:
```bash
git clone https://github.com/zsh-users/zsh-autosuggestions.git
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git
git clone https://github.com/MichaelAquilina/zsh-you-should-use.git
```

update config file:
```bash
vim ~/.zshrc
```

add the following lines in `~/.zshrc` file:
```bash
# zsh plugins
plugins=(git
zsh-autosuggestions
zsh-syntax-highlighting
zsh-you-should-use
docker docker-compose
kubectl kubectx kube-ps1
)

# Not needed for ubuntu
ZSH_AUTOSUGGEST_HIGHLIGHT_STYLE='fg=250'
```

---

### Install themes

move to themes directory:
```bash
cd ~/.oh-my-zsh/custom/themes
```

clone themes:
```bash
git clone https://github.com/romkatv/powerlevel10k.git
git clone https://github.com/spaceship-prompt/spaceship-prompt.git
```

update config file:
```bash
vim ~/.zshrc
```

Update theme:
```bash
ZSH_THEME="robbyrussell"
#ZSH_THEME="powerlevel10k/powerlevel10k"
#ZSH_THEME="spaceship-prompt/spaceship"
```
> pick only one

Start configuration wizard:
```bash
p10k configure
```

---

Git Aliases

https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/git/README.md

