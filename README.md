✦︎✦︎✦︎ Meta Apollo Logos //

# ⚒ ZSH // OH MY APOLLO

![](BUILD/assets/design/chassis/focus-rail.svg)

![Zsh // Oh My Apollo](./BUILD/assets/design/oh-my-apollo-banner.svg)

> **STATE //** active \~\~ **VIEW //** interactive shell configuration

The interactive shell layer of the Post-Apollo Family — shaping the relationship between operator, terminal, commands, context, history, and machine, so working through the terminal feels continuous, legible, and increasingly adapted to the person using it.

**FAMILY //** [META APOLLO LOGOS](https://github.com/kudokudo1/Meta-Apollo-Logos) · [DEV EXP](https://github.com/kudokudo1/The-Post-Apollo-Dev-Exp) · [FOREST](https://github.com/kudokudo1/The-Post-Apollo-Forest-Project) · [TASKBARS](https://github.com/kudokudo1/taskbars-post-apollo)

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
