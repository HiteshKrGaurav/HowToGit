# HowToGit


## Main Commands

```bash
git clone https://github.com/HiteshKrGaurav/HowToGit.git
```
```
git add .
```
```bash
git commit -a -m "message"
```
```bash
git push
```

## To create ssh keys

```bash
    ssh-keygen -t ed25519 -C "your_email@example.com"
```
or

```bash
    ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
```

## how to add ssh keys to github

> [Profile > settings > SSH and GPG keys > Add ssh key](https://github.com/settings/ssh/new)

> copy contents of "/c/Users/YOU/.ssh/sshKey.pub" or "/home/YOU/.ssh/sshKey.pub"

> Paste it to "**Key**" text area

> click on "**Add SSH key**"


## Check SSH agent and key passphrase:

```bash
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_ed25519
```
