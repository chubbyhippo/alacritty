# alacritty
## curl
```
[ -d "${XDG_CONFIG_HOME:-$HOME/.config}/alacritty" ] && rm -rf "${XDG_CONFIG_HOME:-$HOME/.config}/alacritty"; mkdir -p "${XDG_CONFIG_HOME:-$HOME/.config}"/alacritty && curl https://raw.githubusercontent.com/chubbyhippo/alacritty/main/alacritty.toml -o "${XDG_CONFIG_HOME:-$HOME/.config}"/alacritty/alacritty.toml
```
## win
```
if(!(Test-Path -Path "$env:USERPROFILE\AppData\Local\alacritty\")){New-Item -ItemType Directory -Force -Path "$env:USERPROFILE\AppData\Local\alacritty\"}; Invoke-WebRequest -Uri "https://raw.githubusercontent.com/chubbyhippo/alacritty/main/alacritty.toml" -OutFile "$env:USERPROFILE\AppData\Local\alacritty\alacritty.toml"
```
