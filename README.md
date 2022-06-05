# zsh-myincr

A plugin for zsh to automatic prompt and completion. 

After the installation is completed, you do not need to use it manually. It will automatically prompt and complete when you enter.

Zsh-myincr works with zsh or [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh). It is recommended that you use oh-my-zsh.

## Installation

git clone our repo:

```
git clone https://github.com/gaojunbin/zsh-myincr.git
```

If you use oh-my-zsh, please put our code to `$ZSH_CUSTOM/plugins/`and add to plugins in zsh profile like:

```
plugins=(zsh-myincr git autojump)
```

Of course, you can also use our plugin directly in zsh by adding belows to `$HOME/.zshrc` file:

```
source $zsh-myincr/zsh-myincr.plugin.zsh
```

## Meta

Thanks to the contribution from https://mimosa-pudica.net/zsh-incremental.html. We found some inconvenient operations in the original version 0.2 (e.g., Paste will be slow, Annoyingly complete when there is only one option). We made some adjustments to modify it.

## Feedback

Any comments/suggestions/feedback is truly welcome. Please open an issue to discuss something (anything!) about the project ;).

## Plugins and Alternatives

The [awesome-zsh-plugins](https://github.com/unixorn/awesome-zsh-plugins) list is a directory of plugins, themes and alternatives that you may find useful.

The [GCR](https://github.com/gaojunbin/GCR) present a one click deployment scheme for local and remote servers Zsh and Bash. Welcome to experience.