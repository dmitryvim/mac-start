# Initial setup

## .bash_profile

```
# json pretty
alias jp="json_pp -json_opt pretty,canonical"

# K kubeconfig
alias kkdev="export KUBECONFIG=~/.kube/k-dev.yaml"
alias kkprod="export KUBECONFIG=~/.kube/k-prod.yaml"
```


## iTerm

https://iterm2.com/

Download - Unzip - Copy to application

## oh-my-zsh

https://ohmyz.sh/

```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

```
echo "
# load commands from bash
source ~/.bash_profile" >> ~/.zshrc
```

## homebrew

https://brew.sh/

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## .ssh

Do not forget setup ssh keys for git

## .asdf

https://asdf-vm.com/guide/getting-started.html#official-download

```
git clone https://github.com/asdf-vm/asdf.git ~/.asdf --branch v0.11.1
```

```
echo "
# asdf
. \"$HOME/.asdf/asdf.sh\"
. \"$HOME/.asdf/completions/asdf.bash\"" >> ~/.bash_profile
```

## java + kotlin + gradle

```
asdf plugin add java
asdf install java openjdk-17.0.2
asdf global java openjdk-17.0.2
. ~/.asdf/plugins/java/set-java-home.bash

asdf plugin add kotlin
asdf install kotlin latest
asdf global kotlin latest

asdf plugin add gradle
asdf install gradle latest
asdf global gradle latestt
```

## docker 
## vscode
## sublime
## jetbrains
