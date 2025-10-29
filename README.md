# Ubuntu/Related Setup

## Install **gcc** & **G++**
`sudo apt install gcc`
`sudo apt install g++`

## Install rust
`curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh`

## Install `Git`
`sudo apt install git`

## Install fd-find for better search
`apt install fd-find`

## Install brew 
`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

## Install neovim
`brew install neovim`

## Install Lazygit
`brew install lazygit`

## Install Yazi 
```bash
git clone https://github.com/sxyazi/yazi.git
cd yazi
cargo build --release --locked
mv target/release/yazi target/release/ya /usr/local/bin/
```

## Install ripgrep
`sudo apt-get install ripgrep`

### Install nodejs
```bash
# Download and install nvm:
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.3/install.sh | bash

# in lieu of restarting the shell
\. "$HOME/.nvm/nvm.sh"

# Download and install Node.js:
nvm install 22

# Verify the Node.js version:
node -v # Should print "v22.18.0".
```

### Setup for bashrc 
- .bashrc
folder - ~/.bashrc
Install plugin -
`bash -c "$(curl -fsSL https://raw.githubusercontent.com/ohmybash/oh-my-bash/master/tools/install.sh)"`

### install imagick
`sudo apt install imagemagick`

### Install lua
`sudo apt install lua5.4 liblua5.4-dev`   


**note: ** Install alacritty and tmux.
