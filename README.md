# Dotfiles

## This Repository
```bash
cd ~
git clone git@github.com:avanu/dotfiles.git .dotfiles
```


## zsh
```sh
ln -fs ~/.dotfiles/zsh/zshrc ~/.zshrc
ln -fs ~/.dotfiles/zsh/zprofile ~/.zprofile
```

## Vim
- `vimrc` requires [Pathogen](https://github.com/tpope/vim-pathogen) and [Vim Markdown](https://github.com/plasticboy/vim-markdown)
- in addition, `gvimrc` requires , the **Hack** font and the [Base16](https://github.com/chriskempson/base16-vim) Vim theme
- optional vim packages: [Securemodelines](https://github.com/ciaranm/securemodelines), [Solarized](https://github.com/altercation/vim-colors-solarized), `vim-tomorrow-theme`, etc.

```bash
ln -fs ~/.dotfiles/vim/gvimrc ~/.gvimrc
ln -fs ~/.dotfiles/vim/vimrc ~/.vimrc
```

## Git
```bash
# https://help.github.com/articles/ignoring-files/
ln -fs ~/.dotfiles/git/gitconfig ~/.gitconfig
ln -fs ~/.dotfiles/git/gitignore_global ~/.gitignore_global
#git config --global core.excludesfile ~/.gitignore_global
ln -fs ~/.dotfiles/git/gitconfig-ryte ~/.gitconfig-ryte
```

## Obsolete

## bash
```bash
ln -fs ~/.dotfiles/bash/bash_profile ~/.bash_profile
ln -fs ~/.dotfiles/bash/bashrc_aliases ~/.bashrc_aliases
```

### tmux
```bash
ln -fs ~/.dotfiles/tmux/tmux.conf ~/.tmux.conf
ln -fs ~/.dotfiles/tmux/tmux-startup-session.conf ~/.tmux-startup-session.conf
```
