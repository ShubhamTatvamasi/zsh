# alias

```bash
export EDITOR="vim"

alias c='clear'
alias q='exit'

source <(kubectl completion zsh)
alias kubectl=kubecolor
compdef kubecolor=kubectl

alias k='kubectl'

alias ke='k edit'

alias kd='k describe'

alias ka='k apply'
alias kaf='ka -f'

alias kdl='k delete'
alias kdlf='kdl -f'

alias kg='k get'
alias kgr='kg rs'
alias kga='kg all'
alias kgs='kg svc'
alias kgp='kg pods'
alias kgn='kg nodes'
alias kgd='kg deploy'
alias kgi='kg ingress'
alias kgc='kg componentstatuses'

alias kc='k config'
alias kcg='kc get-contexts'
alias kcu='kc use-context'
alias kcc='kc current-context'

alias kx='kubectx'
alias kn='kubens'

```
