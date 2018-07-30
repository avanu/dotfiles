# Dotfiles

### [tmux](./tmux)
```bash
ln -fs /Users/${USER}/.dotfiles/tmux/tmux.conf /Users/${USER}/.tmux.conf
ln -fs /Users/${USER}/.dotfiles/tmux/tmux-startup-session.conf /Users/${USER}/.tmux-startup-session.conf
```

### [Vim](./vim)
- `vimrc` requires [Pathogen](https://github.com/tpope/vim-pathogen) and [Vim Markdown](https://github.com/plasticboy/vim-markdown)
- in addition, `gvimrc` requires , the **Hack** font and the [Base16](https://github.com/chriskempson/base16-vim) Vim theme
- optional vim packages: [Securemodelines](https://github.com/ciaranm/securemodelines), [Solarized](https://github.com/altercation/vim-colors-solarized), `vim-tomorrow-theme`, etc.

```bash
ln -fs /Users/${USER}/.dotfiles/vim/gvimrc /Users/${USER}/.gvimrc
ln -fs /Users/${USER}/.dotfiles/vim/vimrc /Users/${USER}/.vimrc
```
