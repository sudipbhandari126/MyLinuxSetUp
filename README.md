# MyLinuxSetUp
This repo contains various configurations that I use for my linux system for productivity and ease. Feel free to tinker around and give suggestions

Markdown editor used: [Remarkable (Markdown Editor)](https://remarkableapp.github.io/) 

## Terminator
This is a multiwindowing terminal system for linux based on GNOME. It's highly configurable. [configuring terminator](https://www.linuxnov.com/the-complete-guide-to-configure-terminator-terminal-emulator-layouts/) 

My favorite layout (2X2 with AtomLight theme)
![ ](https://github.com/sudipbhandari126/MyLinuxSetUp/blob/master/resources/terminator.png  "2X2 terminator view")


#### Configuration:
Install terminator: 
`sudo add-apt-repository ppa:gnome-terminator`
`sudo apt-get install terminator`
`sudo apt-get update`
`sudo apt-get install terminator`

[Copy this file](https://github.com/sudipbhandari126/MyLinuxSetUp/blob/master/terminator/config) to `~/.config/terminator/`

### Zsh
Zshell is my shell of choice. It's also used as default shell in macOS.
#### installation:
`sudo apt-get install zsh`
Make zsh default shell: `chsh -s $(which zsh)`
[Oh My Zsh](https://github.com/robbyrussell/oh-my-zsh) has tons of configurations for zsh including interesting themes and so on.

