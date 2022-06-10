# macEnv

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
<user>
echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> ~/.zprofile                  
    eval "$(/opt/homebrew/bin/brew shellenv)"
    
brew install --cask iterm2

 sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

brew install --cask google-chrome

brew install --cask chromedriver

brew install --cask android-studio

brew install --cask intellij-idea-ce

brew install --cask pycharm-ce

brew install --cask charles

brew install cask docker

brew install postgresql

brew install sqlmap

brew install --cask tableplus

brew install --cask postico

brew install --cask vnc-viewer

brew install p7zip # 7z x filename.rar

brew install --cask microsoft-teams

brew install --cask github

brew install --cask slack

# python
brew install pyenv
echo 'export PYENV_ROOT="$HOME/.pyenv"' >> ~/.zshrc
echo 'export PATH="$PYENV_ROOT/bin:$PATH"' >> ~/.zshrc
echo -e 'if command -v pyenv 1>/dev/null 2>&1; then\n  eval "$(pyenv init -)"\nfi' >> ~/.zshrc

brew install --cask appium

brew install --cask visual-studio-code
    
brew install --cask vysor
    
brew install --cask postman

brew install --cask vlc

brew install maven    

brew install --cask firefox

brew install geckodriver

brew install gh

curl -s "https://get.sdkman.io" | bash

brew install --cask burp-suite

brew install --cask owasp-zap

brew install mitmproxy

brew install tmux

brew install nvm

brew install cowsay fortune figlet lolcat

# sudo gem install lolcat


mkdir ~/.nvm

export NVM_DIR="$HOME/.nvm"
  [ -s "/opt/homebrew/opt/nvm/nvm.sh" ] && . "/opt/homebrew/opt/nvm/nvm.sh"  # This loads nvm
  [ -s "/opt/homebrew/opt/nvm/etc/bash_completion.d/nvm" ] && . "/opt/homebrew/opt/nvm/etc/bash_completion.d/nvm"  # This loads nvm bash_completion
  
  ```
  
  
  ## Ubuntu setup 

Pyenv ubuntu installation 
[Pyenv](https://www.liquidweb.com/kb/how-to-install-pyenv-on-ubuntu-18-04/)

```
apt install -y make build-essential libssl-dev zlib1g-dev libbz2-dev libreadline-dev libsqlite3-dev wget curl llvm libncurses5-dev libncursesw5-dev xz-utils tk-dev libffi-dev liblzma-dev python-openssl git
```

How to pyenv [intro-to-pyenv](https://realpython.com/intro-to-pyenv/)

```
export PATH="$HOME/.pyenv/bin:$PATH"
eval "$(pyenv init -)"
eval "$(pyenv virtualenv-init -)"
eval "$(pyenv init --path)"
```

To configure oh my zsh [oh-my-zsh](https://www.tecmint.com/install-oh-my-zsh-in-ubuntu/)

To fix `Zsh not installed! Install zsh first.` [here](https://askubuntu.com/questions/1032567/install-zsh-in-ubuntu-18-04)

Swith to zsh [here](https://askubuntu.com/questions/131823/how-to-make-zsh-the-default-shell)

## sudo install 

`
apt-get update && apt-get -y install sudo
`

## Useful Python links


## Git 

Git reset [como-deshacer-el-ultimo-commit-git/](https://midu.dev/como-deshacer-el-ultimo-commit-git/)

# WSL 2 installation 

https://www.omgubuntu.co.uk/how-to-install-wsl2-on-windows-10

https://docs.microsoft.com/es-es/windows/wsl/install

https://docs.microsoft.com/en-us/windows/wsl/install-manual#step-4---download-the-linux-kernel-update-package
