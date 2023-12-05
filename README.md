# Usefull Aliases
Simple records of useful bash aliases

## kubernetes aliases

>### General Aliases
```
alias k='kubectl'
alias ks='kubectl -n kube-system'
alias kdesc='kubectl describe'
```

>### Create Resources
```
alias kcf='kubectl create -f'
alias kaf='kubectl apply -f'
```

>### Get Resources
```
alias kgn='kubectl get nodes'
alias kgp='kubectl get pods'
alias kgpa='kubectl get pods --all-namespaces'
alias kgs='kubectl get services'
alias kgd='kubectl get deployments'
```

>### Delete Resources
```
alias kd='kubectl delete'
alias kdp='kubectl delete pods'
alias kds='kubectl delete service'
alias kdd='kubectl delete deployment'
alias kdn='kubectl delete namespace'
```