# Dotfiles

```bash
cd ~
git clone git@github.com:avanu/dotfiles.git .dotfiles
```

## bash
```bash
ln -fs /Users/${USER}/.dotfiles/bash/bash_profile /Users/${USER}/.bash_profile
ln -fs /Users/${USER}/.dotfiles/bash/bashrc_aliases /Users/${USER}/.bashrc_aliases
```

## tmux
```bash
ln -fs /Users/${USER}/.dotfiles/tmux/tmux.conf /Users/${USER}/.tmux.conf
ln -fs /Users/${USER}/.dotfiles/tmux/tmux-startup-session.conf /Users/${USER}/.tmux-startup-session.conf
```

## Vim
- `vimrc` requires [Pathogen](https://github.com/tpope/vim-pathogen) and [Vim Markdown](https://github.com/plasticboy/vim-markdown)
- in addition, `gvimrc` requires , the **Hack** font and the [Base16](https://github.com/chriskempson/base16-vim) Vim theme
- optional vim packages: [Securemodelines](https://github.com/ciaranm/securemodelines), [Solarized](https://github.com/altercation/vim-colors-solarized), `vim-tomorrow-theme`, etc.

```bash
ln -fs /Users/${USER}/.dotfiles/vim/gvimrc /Users/${USER}/.gvimrc
ln -fs /Users/${USER}/.dotfiles/vim/vimrc /Users/${USER}/.vimrc
```

## Git
```bash
# https://help.github.com/articles/ignoring-files/
ln -fs /Users/${USER}/.dotfiles/git/gitignore_global /Users/${USER}/.gitignore_global
git config --global core.excludesfile ~/.gitignore_global
```
