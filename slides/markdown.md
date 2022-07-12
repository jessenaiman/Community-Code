# Community Code

Anyone can code

---
## Hubble Presents

Episode 1: Everything you need to get started

Note: This will only appear in the speaker notes window.



## Prerequisites: Windows 10/11

1. **Visual Code** (Microsoft : https://code.visualstudio.com/
2. **[Github Account]** (https://github.com/)
3. **Linux** Referred to as WSL: *Windows Subsystem for Linux*
   1. Right click on start menu and select “Windows Terminal (Admin)”
   2. Type `wsl --install`
   3. Reboot the machine (Careful, turning it on and off is not the same)
   4. Make sure you can find the Ubuntu app in the start menu. If it is missing install manually using: `wsl --install -d ubuntu`
   


## Prerequisites: Mac Setup

1. Install homebrew: [Homebrew](https://treehouse.github.io/installation-guides/mac/homebrew):

        ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

2. Type: `brew` and verify that it is a recognized command

3. Verify that you have node installed by typing: `node -v`

* *Use this [guide](https://tecadmin.net/install-nvm-macos-with-homebrew/) if you do not see a version number after inputing node -v*

* *Use this [guide](https://dev.to/nickgarfield/how-to-install-solana-dev-tools-on-an-m1-mac-kfn) if you encounter an error installing homebrew*



## Install Solana

>[Official Docs](https://docs.solana.com/cli/install-solana-cli-tools)

1. Open Ubuntu or Terminal
2. Type: `sh -c "$(curl -sSfL https://release.solana.com/v1.10.29/install)"`
3. Close and reopen
4. Type `solana –version` to make sure it’s installed
5. Type `solana-keygen new`
- Hit enter for the passphrase 
- This creates a wallet you can use for development, you don't need to save any of this



## Install Rust Windows:

1. `curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh`
2. A list of options appears, select #1 and hit enter (Windows)
3. Restart Terminal
4. Type `rustup` to ensure it's installed


## Install Rust Mac:

1. `brew install rustup`
In case of an error reference: https://stackoverflow.com/questions/18039029/mac-can-t-install-homebrew
2. Type `rustup` to ensure it’s installed
3. Press enter again



## Install NVM (Node Version Manager)

[Official Guide]: 
(https://book.anchor-lang.com/getting_started/installation.html)

1. Install node package manager: nvm
   
        curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash

2. Close and reopen

        nvm install node

3. Install Yarn:
   
        corepack enable



## Installing Anchor (Using Anchor Version Manager)

1. Make sure you have the latest software: 
   
        sudo apt-get update
        sudo apt-get upgrade
        sudo apt-get install pkg-config libssl-dev
        sudo apt-get update && sudo apt-get upgrade && sudo apt-get install -y pkg-config build-essential libudev-dev

2. Install avm:
   
        cargo install --git https://github.com/project-serum/anchor avm --locked --force

3. Upgrade to latest version: 
   
        avm install latest



## Final Steps: Download, Compile, Run

1. Copy the Solana example code:
   
        git clone https://github.com/solana-developers/solana-dapp-next.git
2. Move to the directory of the copied code:
   
        cd solana-dapp-next (tip: press tab once you’ve typed cd sol.. and it will autocomplete)
3. Install all code needed to run this application:
   
        yarn install
4. Fire it up:
   
        yarn dev

5. Open your brave browser and navigate to localhost:8000



## Congratulations 
