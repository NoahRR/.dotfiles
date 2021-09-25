###LINUX CONFIG FILES
Dependencies:
- stow (apt install stow)

Usage:
- in $HOME, clone this repo
- go into folder
- use "stow */" to apply all config directories
- use "stow {dir name}" to apply single config directory

###ADDING NEW FILES
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
git submodule add https://<USERNAME>:<ACCESS TOKEN>@github.com/NoahRR/nvim.git nvim/.config/nvim
```
