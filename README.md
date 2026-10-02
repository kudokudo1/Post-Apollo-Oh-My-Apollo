✦︎✦︎✦︎ Meta Apollo Logos //

# ⚒ POST-APOLLO // ZSH

![](BUILD/assets/design/chassis/focus-rail.svg)

> **STATE //** active \~\~ **VIEW //** interactive shell configuration

> **Post-Apollo Zsh contains the live shell configuration and prompt layer for the development environment.**

### 🧭 MAP // REPOSITORY

![](BUILD/assets/design/chassis/nav-rail.svg)

// [🧭 ATLAS](./ATLAS/) \~\~ // [✮˙๋࣭⭑ MODEL](./MODEL/) \~\~ // [🖨 BUILD](./BUILD/) \~\~ // [⚒ DEV](./DEV/) \~\~ // [🖳 OPERATE](./OPERATE/) \~\~ // [⊹ ࣪ℼ˖ EVIDENCE](./EVIDENCE/) \~\~ // [࣪⋅˚🕮‧₊˚ ARCHIVE](./ARCHIVE/)

---

### ★⋆˙ CORE // RUNTIME LAYOUT

The live shell files stay in their current root paths. Meta Apollo rooms describe the system without changing how Zsh sources configuration.

---

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
