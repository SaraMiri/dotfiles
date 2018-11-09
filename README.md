# My DotFiles

## 0. Generate `ssh` keys

Check out [Generating a new SSH key and adding it to the ssh-agent](https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/)

### Steps

```sh
❯ ssh-keygen -t rsa -b 4096 -C " saramiragaya@gmail.com"
❯ bash
❯ eval "$(ssh-agent -s)"
❯ fish
❯ ssh-add ~/.ssh/id_rsa
❯ sudo apt-get install xclip
❯ xclip -sel clip < ~/.ssh/id_rsa.pub
```

Finally, we need to perform the steps from step 2 👉 [Add the SSH key to your GitHub account](https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account)

## How to install

Follow these steps

```sh
❯ cd ~/projects
❯ git clone git@github.com:SaraMiri/calculator.git
❯ cd dotfiles/
❯cp ./gitconfig ~/.gitconfig
```
