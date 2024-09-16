# Welcome 🤠

# Aliases
```
echo "
 
alias dps='docker ps --format "table {{.Names}}\t{{.Image}}\t{{.Status}}"' 
alias dpp='docker ps --format "table {{.Names}}\t{{.Status}}\t{{.Ports}}"'
alias de='f() { docker exec -it "$@" bash; unset -f f; }; f'
alias deu='f() { docker exec -u root -it "$@" bash; unset -f f; }; f'" >> ~/.bashrc

source ~/.bashrc
```
