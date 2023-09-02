# Welcome 🤠

# Aliases
```
echo "
 
alias dps='docker ps --format "table {{.Names}}\t{{.Image}}\t{{.Status}}"' 
alias dpp='docker ps --format "table {{.Names}}\t{{.Status}}\t{{.Ports}}"'
alias gc='git commit -m'
alias gpo='git push origin'
alias gch='git checkout'
alias gchb='git checkout -b'
alias de='f() { docker exec -it "$@" bash; unset -f f; }; f'
alias deu='f() { docker exec -u root -it "$@" bash; unset -f f; }; f'
alias cal='echo "" > /var/log/apache2/error.log'
alias ..='cd ..'
alias ...='cd ../..'
alias ....='cd ../../../'
alias ~='cd ~'" >> ~/.bashrc

source ~/.bashrc
```
