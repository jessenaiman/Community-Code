# Community Code

Anyone can code

---
## Hubble Presents

Episode 1: Everything you need to get started



## Install NVM (Node Version Manager)

1. Install nvm (node package manager)
   
        curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash

2. Close and reopen

        nvm install node

3. Install Yarn:
   
        corepack enable 

[Official Guide](https://book.anchor-lang.com/getting_started/installation.html)



## Install Solana

1. Open Ubuntu or Terminal
2. Type: 
        
                sh -c "$(curl -sSfL https://release.solana.com/v1.10.29/install)"

3. Close and reopen
4. Type `solana --version` to make sure it’s installed
5. Type `solana-keygen new`

    a. Hit enter for the passphrase when prompted

    b. This creates a wallet you can use for development, you don't need to save any of this

[Official Solana Document](https://docs.solana.com/cli/install-solana-cli-tools)

Note: 
* discuss solana-keygen new 
* Discuss how there are 3 solana environments
* add commands in slide below



## Install Rust Windows:

1. Open terminal and type:

                curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh

2. A list of options appears, select #1 and hit enter

![External Image](assets/rust-install.png)

3. Restart Terminal
4. Type `rustup` to ensure it's installed


## Install Rust Mac:

1. `brew install rustup`
In case of an error reference: https://stackoverflow.com/questions/18039029/mac-can-t-install-homebrew
2. Type `rustup` to ensure it’s installed
3. Press enter again


## Installing Anchor (Using Anchor Version Manager)

1. Make sure you have the latest software (Only for Linux - WSL): 
   
        sudo apt-get update
        sudo apt-get upgrade
        sudo apt-get install pkg-config libssl-dev
        sudo apt-get update && sudo apt-get upgrade && sudo apt-get install -y pkg-config build-essential libudev-dev

2. Install avm (Mac and WSL):
   
        cargo install --git https://github.com/project-serum/anchor avm --locked --force

3. Upgrade to latest version: 
   
        avm install latest

Notes: Follow up questions
1 - Interesting Projects
2 - Requests
3 - Dream projects



## Download

1. Navigate to https://github.com/solana-developers/solana-dapp-next.git

2. Click the 'Fork' button in the top right

    ![External Image](assets/fork-sample.png)

3. Create a new fork and keep the name the same

3. Copy your Solana example code by copying the url and then type:
   
        git clone https://github.com/your-github-name/solana-dapp-next.git



## Compile

1. In your terminal type:
   
        cd solana-dapp-next 

2. Install all code needed to run this application:
   
        yarn install



## Run

1. Fire it up:
   
        yarn dev

2. Open a browser navigate to http://localhost:8000



## Congratulations 
