# zsh

install zsh and ohmyzsh:
```bash
sudo apt install zsh git -y
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

move to plugins directory:
```bash
cd ~/.oh-my-zsh/plugins
```

clone plugins:
```bash
git clone https://github.com/zsh-users/zsh-autosuggestions.git
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git
```

open config file:
```bash
vim ~/.zshrc
```

add the following lines in `~/.zshrc` file:
```bash
# zsh plugins
plugins=(git
zsh-autosuggestions
zsh-syntax-highlighting
docker docker-compose
kubectl kubectx kube-ps1
)

ZSH_AUTOSUGGEST_HIGHLIGHT_STYLE='fg=245'
```

