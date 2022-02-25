# macEnv

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
<user>
echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> /Users/psanchez/.zprofile                  
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

# https://tuataras.net/blog-es/tutoriales/como-instalar-postgresql-en-macos-con-brew/
    
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

brew install --cask slack

mkdir ~/.nvm

export NVM_DIR="$HOME/.nvm"
  [ -s "/opt/homebrew/opt/nvm/nvm.sh" ] && . "/opt/homebrew/opt/nvm/nvm.sh"  # This loads nvm
  [ -s "/opt/homebrew/opt/nvm/etc/bash_completion.d/nvm" ] && . "/opt/homebrew/opt/nvm/etc/bash_completion.d/nvm"  # This loads nvm bash_completion
  
  ```
