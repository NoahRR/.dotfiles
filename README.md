![alt text](https://github.com/NoahRR/.dotfiles/blob/master/SAVED_DOWNLOADS/SAVED_DOWNLOADS/DeepinScreenshot_select-area_20211005220005.png?raw=true)

### LINUX CONFIG FILES
Dependencies:
- stow

Usage:
- in $HOME, clone this repo
- install submodules
```
git submodule update --init --recursive
git submodule update --recursive --remote
```
- go into folder
- use "stow */" to apply all config directories
- use "stow {dir name}" to apply single config directory

### INCLUDED
- i3 config >> archcraft-i3/
- nvim config >> nvim/
- zsh config >> zsh-config/
- fonts >> fonts/
- alacritty >> alacritty/
- desktop images >> SAVED_DOWNLOADS/

### ADDING NEW FILES
Default
- add new folder for grouping (or add to existing folder)
- once in folder, pretend you are in your home (~) directory
- so typically, from there, add a .config/ and then add files there

Existing git repo:
- use git submodules
```
git submodule add <git http link remote url> <dir>
```
Example:
```
git submodule add https://github.com/NoahRR/nvim.git nvim/.config/nvim
```
