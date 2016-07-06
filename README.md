# Dotfiles
My terminal configuration contains Tmux and custom OSX terminal theme.

## Installation
1. Install tmux
2. Clone repository `git clone https://github.com/phardyn/dotfiles.git ~/Documents`
3. Install theme
4. Symlink .tmux.conf `ln -s ~/Documents/dotfiles/.tmux.conf ~/.tmux.conf`
5. Symlink .profile `ln -s ~/Documents/dotfiles/.profile ~/.profile`

## Key bindings
- Windows
  - `Ctrl + k 3` - split screen vertically
  - `Ctrl + k 2` - split screen horizontally

- Sessions
  - `Ctrl + k $` - change session name

- Other
  - `Ctrl + k :` - enter command
