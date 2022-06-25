# Setup

1) ZSH Setup (Ubuntu and MacOS)
Installating zsh
```
$ sudo apt install zsh //Ubuntu
 or 
$ brew install zsh //MacOS
```
Checking if it is installed
```
$ zsh --version
```
Changing from bash to zsh
```
$ sh -s $(which zsh)
```
Logout and login
```
$ echo $SHELL
```

2) Oh-My-ZSH Setup - Package Manager
Installation of oh-my-zsh (Oh-My-ZSH)
```
$ sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
or 
$ sh -c "$(wget -O- https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```
   
Editing configuration
- editing the .zshrc configuration file in the user directory using your favourite editor
    - go to the `plugins` section
Load the configuration file
```
$ source ~/.zshrc
```
