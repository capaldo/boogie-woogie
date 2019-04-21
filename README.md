![boogiewoogie](/media/boogiewoogieheader.png)

# Description
This is a theme/configuration/dotfile that I'm currently using for iTerm, vim, and cmus is inspired by the colors seen on Piet Mondrian's *Broadway Boogie Woogie* and *Victory Boogie Woogie*. It's
currently only is available in a dark mode variant. 

## vim
A powerful and easy to use text editor.
![vim](/media/vim.png)
The vim theme currently supports the following:

### Syntaxes/Filetypes
* eRuby
* Ruby
* Javascript
* YAML
* CSS
* Python
* Markdown (plastic-boy)
* zsh configuration

### Plug-Ins
* Startify

### Installation (macOS)
After cloning the repo:
* go to the repositories folder
```bash
cd ./boogiewoogie
```
* move the theme to the default location for vim
```bash
mv ./boogiewoogie.vim ~/.vim/colors/
```
* add the following to your `.vimrc`
```bash
colorscheme boogiewoogie
```
## cmus
Simple and extensible terminal music player.
![cmus](/media/cmus.png)

### Installation (macOS)
After cloning the repo:
* go to the repositories folder
  ```bash
  cd ./boogiewoogie
  ```
* move the theme to the default location for the cmus theme
  ```bash
  mv ./boogiewoogie.theme ~/.config/cmus/
  ```
* then set the theme after starting cmus 
  ```bash
  :colorscheme boogiewoogie
  ```

## TODO
- [ ] add vim light variant
- [ ] add more syntaxes to vim colorscheme
- [ ] add airline theme
- [x] add cmus theme
    - [x] installation instructions for cmus
    - [ ] easy-install script
