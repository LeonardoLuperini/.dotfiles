# How to set-up

Create in $HOME a file named "./zshenv" open it and write:

    ZDOTDIR=$HOME/.dotfiles/zsh
    ZPLUGINS=$ZDOTDIR/Plugins

Stay in $HOME and write:

    git clone https://github.com/LeonardoLuperini/.dotfiles
    cd .dotfiles/zsh
    mkdir Plugins

Install all following the plugin in the Plugins folder:

- [Auto suggesions](https://github.com/zsh-users/zsh-autosuggestions)
- [Syntax highlighting](https://github.com/zsh-users/zsh-syntax-highlighting)
- [You should use](https://github.com/MichaelAquilina/zsh-you-should-use)
- [History substring search](https://github.com/zsh-users/zsh-history-substring-search/blob/master/zsh-history-substring-search.zsh)

Install [Starship](https://starship.rs/guide/#%F0%9F%9A%80-installation)
