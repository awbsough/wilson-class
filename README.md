# Setting up your Development Environment 

## Install WSL:

Run Powershell as Administrator and run the following command:

`wsl --install`

## Install Ubuntu

Install Ubuntu 20.04 LTS from the Microsoft Store.

## Install a programming friendly font

Install a programming friendly font like Fira Code. You can find it here:

https://fonts.google.com/specimen/Fira+Code

## Install Visual Studio Code

Download and install Visual Studio Code from here:

https://code.visualstudio.com/download

## Change your terminal to a programmer friendly font

Open Visual Studio Code and open the settings. You can do this by pressing `Ctrl + ,` or by clicking on the gear icon in the bottom left corner.

Once you are in the settings, search for `terminal.integrated.fontFamily` and change it to `Fira Code`.

## Change shell to zsh and install oh-my-zsh

Open a terminal and run the following commands:

`sudo apt update`

`sudo apt install zsh`

`sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`

`chsh -s $(which zsh)`

## Install Powerlevel10k

Open a terminal and run the following commands:

`git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k`
