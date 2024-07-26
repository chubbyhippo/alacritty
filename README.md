# alacritty
## curl
```
[ -d "${XDG_CONFIG_HOME:-$HOME/.config}/alacritty" ] && rm -rf "${XDG_CONFIG_HOME:-$HOME/.config}/alacritty"; mkdir -p "${XDG_CONFIG_HOME:-$HOME/.config}"/alacritty && curl https://raw.githubusercontent.com/chubbyhippo/alacritty/main/alacritty.toml -o "${XDG_CONFIG_HOME:-$HOME/.config}"/alacritty/alacritty.toml
```
## win
```
if(!(Test-Path -Path "$env:appdata\alacritty\")){New-Item -ItemType Directory -Force -Path "$env:appdata\alacritty\"}; Invoke-WebRequest -Uri "https://raw.githubusercontent.com/chubbyhippo/alacritty/main/alacritty-win.toml" -OutFile "$env:appdata\alacritty\alacritty.toml"
```
