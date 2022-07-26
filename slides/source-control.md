## Episode 2 - Building and Contributing

* Learn how to save, revise, and contribute to open source projects.

* We will create our very own clone of a project. 

* We will make changes, and learn how revision control can allow contributions, and save yourself from overwriting your own success.



# Configure and Install

        $ git config --global user.name "Your Name"

        $ git config --global user.email "youremail@domain.com"

[reference link](https://docs.microsoft.com/en-us/windows/wsl/tutorials/wsl-git)



# Basic Commands

[Command list](https://docs.microsoft.com/en-us/windows/wsl/tutorials/wsl-git): 
        
        $ git status
        $ git clone



# Make some changes

1. Add the files to this revision 

        $ git add .

    *If you want to add a specific file you can replace the . with a filename like index.html*

2. Commit all the changes and include a message

        $ git commit -m your_message_here



# Research for later

[Official Guide](https://docs.github.com/en/get-started)



# Open Source 

This is more than just opening the door, because if everyone could just walk in and rearange the furniture it would just be chaos.

Github is an version control tool, it does not make your code open source.

When you save your work to a github repository you can choose to expose that code to the public. Doing this creates the beginning of an open source project.

You should pick a license model, but for the purpose of todays lesson this is something you should look into.

Our own writings and code can benefit from version control.

Version control allows for experimentation without the risk of permanently altering a working version.

We can even create multiple branches, allowing for multiple versions of the same project to exist.

Today we're going to work with the basics. We want to make sure our own projects are configured. 

Plan:

1. Configure Github
2. Clone
3. Run locally 
4. Make a change to your local copy
5. Push that change to your Github
6. I make a change to the master source 
7. Studends pull most recent copy
8. Push change
