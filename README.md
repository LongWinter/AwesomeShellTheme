# AwesomeShellTheme
![alt text](https://user-images.githubusercontent.com/10003885/41795622-02b91348-7629-11e8-855b-321ddc2f8387.png)

## Here I am using Iterm2, Zsh, powerlevel9k(this is my theme). Check each of them in google for more details!

## Here are my settings in:  ```~/.zshrc```
```
ZSH_THEME="powerlevel9k/powerlevel9k"

# The following are the settings for powerlevel9k
POWERLEVEL9K_LEFT_PROMPT_ELEMENTS=(context dir dir_writable vcs)
POWERLEVEL9K_RIGHT_PROMPT_ELEMENTS=(status battery history time)
# set your default user account
DEFAULT_USER="ye"
# by using nerd font, you can show a lot more icons than you think. check powerlevel9k wiki for more details
POWERLEVEL9K_MODE='nerdfont-complete'
```

## Here are some useful plugins for zsh:

```
plugins=(
  git
  zsh-syntax-highlighting
  zsh-autosuggestions
)
```