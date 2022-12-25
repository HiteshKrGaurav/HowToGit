# HowToGit


### Main Command:

    git clone repo_link
    git add .
    git commit -a -m "message"
    git push

### how to create ssh keys:

    ssh-keygen -t ed25519 -C "your_email@example.com"
    
or
    
    ssh-keygen -t rsa -b 4096 -C "your_email@example.com"


### how to add ssh keys to github:

> [Profile > settings > SSH and GPG keys > Add ssh key](https://github.com/settings/ssh/new)

> copy contents of "/c/Users/YOU/.ssh/sshKey.pub" or "/home/YOU/.ssh/sshKey.pub"

> Paste it to "**Key**" text area

> click on "**Add SSH key**"
