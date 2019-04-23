# Installation
- Install [Neovim](https://neovim.io/)
- Install Python support:
```
sudo apt install python3-neovim
```
or
```
sudo pip3 install --upgrade neovim
```
- Create backup:
```
mv .config/nvim .config/nvim.bak
```
- Clone this project:
```
git clone https://github.com/jacktinhsau/chatt-vim/ ~/.config/nvim
```
- Install plugins:
```
vim +PlugInstall +qall
```
