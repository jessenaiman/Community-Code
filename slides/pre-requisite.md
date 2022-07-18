## Prerequisites: 

1. **Visual Code** (Microsoft : https://code.visualstudio.com/
2. **[Github Account]** (https://github.com/)



### Windows 10/11

**Linux** Referred to as WSL: *Windows Subsystem for Linux*
1. Right click on start menu and select “Windows Terminal (Admin)”
2. Type 

        wsl --install

3. Reboot the machine (Careful, turning it on and off is not the same)
4. Make sure you can find the Ubuntu app in the start menu. If it is missing install manually using: 

        wsl --install -d ubuntu
   


### Mac Setup

The official website is https://brew.sh/

[Homebrew](https://treehouse.github.io/installation-guides/mac/homebrew):
  
    ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

> Use this [guide](https://dev.to/nickgarfield/how-to-install-solana-dev-tools-on-an-m1-mac-kfn) if you encounter an error

Verify that you have node installed by typing: `node -v`

> Use this [guide](https://tecadmin.net/install-nvm-macos-with-homebrew/) if you do not see a version number after inputing the command
