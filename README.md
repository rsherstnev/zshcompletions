# How to add completions for tools in my system?

- Have `zsh` as your command interpreter and `oh-my-zsh` installed
- Download completions files **(anywhere, but home directory is preferred)**

```bash
git clone https://github.com/rsherstnev/zshcompletions $HOME/zsh-custom-completions/
```

- Put at the end of zsh config file your custom completions directory in the beginning of `fpath` variable and `compinit` function:

```bash
fpath=(
    $HOME/zsh-custom-completions
    $fpath
)
autoload -Uz compinit
compinit
```

## Screencasts how my completion working looks like (with `fzf` tool installed and `fzf`, `fzf-tab` zsh plugins activated)
https://github.com/rsherstnev/zshcompletions/assets/26627142/1093e880-2182-416e-a729-e99f8518f873
