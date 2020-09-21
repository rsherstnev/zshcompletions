## How to add completion for tool in my system?
- Have zsh as your command interpreter and oh-my-zsh installed
- Download completion file
- Put it in `/usr/share/zsh/functions/Completion/Unix/`
- Source your zsh config file

You can do it by one command like that:
```
sudo wget https://github.com/rsherstnev/configs/raw/master/zsh_completions/_gobuster -O /usr/share/zsh/functions/Completion/Unix/_gobuster && source ~/.zshrc
```
## Screencasts how my completion working looks like (with fzf and fzf-tab plugins for zsh)

### Gobuster
[![asciicast](https://asciinema.org/a/335775.svg)](https://asciinema.org/a/335775)

### Wfuzz
[![asciicast](https://asciinema.org/a/338885.svg)](https://asciinema.org/a/338885)

### Hashcat
[![asciicast](https://asciinema.org/a/336061.svg)](https://asciinema.org/a/336061)

### Sqlmap
[![asciicast](https://asciinema.org/a/336070.svg)](https://asciinema.org/a/336070)

### Msfvenom (payload options must be set last or completion will not work)
[![asciicast](https://asciinema.org/a/336071.svg)](https://asciinema.org/a/336071)