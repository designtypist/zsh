# Setup

1) ZSH Setup (Ubuntu and MacOS)
Installating zsh
[Ubuntu]
```
sudo apt install zsh
```
or
[MacOS]
```
brew install zsh
```
Checking if it is installed
```
zsh --version
```
Changing from bash to zsh
```
sh -s $(which zsh)
```
Logout and login
```
echo $SHELL
```

2) Oh-My-ZSH Setup - Configuration Manager
Installation of oh-my-zsh (Oh-My-ZSH)
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)/"
```
or
```
sh -c "$(wget -O- https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

Editing the configuration

In your favourite editor, open `.zshrc` configuration file found in the home directory 
1) ZSH plugins
- Go to the `plugins` section (line 71)
```
plugins=(bundler docker dotenv git node npm ssh-agent)
```
- Load the configuration file
```
source ~/.zshrc
```

2) ZSH themes
- Go to the `zsh_themes' section (line 11)
```
ZSH_THEME="apple"
```
