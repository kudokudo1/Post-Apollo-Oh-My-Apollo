# Post-Apollo Zsh

Live Zsh configuration for the Post-Apollo environment.

## Live configuration

Primary Zsh configuration directory:

    ~/.config/zsh

The initial baseline preserves:

- `.zshrc`
- `.zshenv`
- `.p10k.zsh`

The `.p10k.zsh` file in this repository is an exact snapshot of the live:

    ~/.p10k.zsh

The live shell still sources the home-directory copy at this baseline.

A later cleanup may move Powerlevel10k configuration fully under `$ZDOTDIR`
so the repository itself becomes the single live source.

## Generated files

Zsh completion caches such as `.zcompdump*` and compiled `.zwc` files are
intentionally not tracked.

## Development policy

Preserve first, clean later.
