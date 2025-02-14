## Basic Config

1. Open Terminal.

2. Set a Git username:

        $ git config --global user.name "Your Name"

        $ git config --global user.email "youremail@domain.com"

3. Confirm that you have set the Git username correctly:

        $ git config --global user.name


## Authentication

Install the [github cli](https://github.com/cli/cli#installation)

It's easy to confuse this with the core git cli which we access when we type `git [command]`

#### Mac Users

        $ brew install gh

#### Linux Users 

Follow the steps in this [document](https://github.com/cli/cli/blob/trunk/docs/install_linux.md)

        $ curl -fsSL https://cli.github.com/packages/githubcli-archive-keyring.gpg | sudo dd of=/usr/share/keyrings/githubcli-archive-keyring.gpg
        $ sudo chmod go+r /usr/share/keyrings/githubcli-archive-keyring.gpg
        $ echo "deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/githubcli-archive-keyring.gpg] https://cli.github.com/packages stable main" | sudo tee /etc/apt/sources.list.d/github-cli.list > /dev/null
        $ sudo apt update
        $ sudo apt install gh

*Friendly reminder to confirm that you are installing official code, and not malware*

#### Everyone

1.

        $ gh auth login

2. Select Github.com 

3. Choose second option and head to github to generate a new ssh key


3. https://github.com/settings/tokens


## Terminal Github Commit

*These are the typical steps for a single use save to github*

                git status
                git add .
                git commit -m 'your commit message'
                git push
