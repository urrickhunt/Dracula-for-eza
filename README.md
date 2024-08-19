# Dracula for [eza](https://github.com/eza-community/eza)

> A dark theme for [eza](https://github.com/eza-community/eza)
<img width="1495" alt="eza" src="https://github.com/user-attachments/assets/ddc606ac-f10b-4a35-8cf8-c0ffc9035a3d">

#### Usage

To activate the theme in **eza**, you need to modify your `.zshrc file`.

#### Installation

**Linux** & **macOS**

1. Add the desired `eza_colors` theme to the end of your `.zshrc`:

```zshrc
# ---------------------
# eza universal Dracula
# ---------------------
export EZA_COLORS="\
uu=36:\
uR=31:\
un=35:\
gu=37:\
da=2;34:\
ur=34:\
uw=95:\
ux=36:\
ue=36:\
gr=34:\
gw=35:\
gx=36:\
tr=34:\
tw=35:\
tx=36:\
xx=95:"
```
#### Suggested Aliases

For normal or larger displays include group (`-g flag`):

```zshrc
alias zl='eza -lagX --icons --color=always'
```

For smaller or limited displays no group:

```zshrc
alias zl='eza -laX --icons --color=always'
```

## Team

This theme is maintained by the following person(s).

| [![urrickhunt](https://github.com/urrickhunt.png?size=100)](https://github.com/urrickhunt)|
| ----------------------------------------------------------------------------------------- |
| [urrickhunt](https://github.com/urrickhunt)                                               |

## Community

- [Twitter](https://twitter.com/draculatheme) - Best for getting updates about themes and new stuff.
- [GitHub](https://github.com/dracula/dracula-theme/discussions) - Best for asking questions and discussing issues.
- [Discord](https://draculatheme.com/discord-invite) - Best for hanging out with the community.

## Dracula PRO

[![Dracula PRO](./.github/dracula-pro.png)](https://draculatheme.com/pro)

## License

[MIT License](./LICENSE)
