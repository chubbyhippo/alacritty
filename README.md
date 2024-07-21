# alacritty
## curl
```
[ -d "${XDG_CONFIG_HOME:-$HOME/.config}/alacritty" ] && rm -rf "${XDG_CONFIG_HOME:-$HOME/.config}/alacritty"; mkdir -p "${XDG_CONFIG_HOME:-$HOME/.config}"/alacritty && curl https://raw.githubusercontent.com/chubbyhippo/alacritty/main/alacritty.toml -o "${XDG_CONFIG_HOME:-$HOME/.config}"/alacritty/alacritty.toml
```
