# Zsh completion for nix commands

## Installation

Put the path to the `_nix*` files into the `fpath` variable and enable the
completion system, e.g.

    fpath=(~/nixos-zsh-completion $fpath)
    autoload -U compinit && compinit

## Testing

To reload the completion files just open a new zsh session.
