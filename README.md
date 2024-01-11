# Things to Setup
This section includes the tools needed to setup a simple development workspace

## Brew

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
Once the installation is completed run these two in the terminal

```
(echo; echo 'eval "$(/opt/homebrew/bin/brew shellenv)"') >> /Users/<user-name>/.zshrc

eval "$(/opt/homebrew/bin/brew shellenv)"

source ~/.zshrc
```
<br />

## ZSH (If not already installed)

```
brew install zsh
```
<br />

## Iterm2

```
brew install iterm2 
```
<br />

## oh-my-zsh

```
sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

source ~/.zshrc
```
<br />

## zsh-autosuggestions

```
cd ~/.oh-my-zsh/custom/plugins

git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```
Add `zsh-autosuggestions` to the .zshrc plugins list

```
plugins=(
    <other-plugins>
	zsh-autosuggestions
)
```

Source the config file: `source ~/.zshrc`
<br />

## zsh-syntax-highlighting

```
cd ~/.oh-my-zsh/custom/plugins

git clone https://github.com/zsh-users/zsh-syntax-highlighting.git

echo "source ${(q-)PWD}/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh" >> ${ZDOTDIR:-$HOME}/.zshrc

source ~/.zshrc
```
<br />

## NVM - Node Version Manager
```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash

source ~/.zshrc
```

<br/>

## Node 
```
brew install node
```

<br />

## Watchman
```
brew install watchman
```

<br/>

## Yarn
```
brew install yarn
```
<br />

## Visual Studio Code (VS Code)

[Download](https://code.visualstudio.com/download) the latest vscode package 

<br/>

---
