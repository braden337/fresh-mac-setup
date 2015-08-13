# fresh-mac-setup
After a clean install of Mac OS X, here are the things you should do :cat2:

- Install any pending OS updates from the App Store
- Install Xcode from the App Store so you have certain commandline tools that are needed when installing other things listed below
- Install Homebrew (the missing package manager for OS X) from http://brew.sh
- Run `brew update`
- Run `brew install caskroom/cask/brew-cask`
- Run `brew tap caskroom/versions`
- Run `brew update`
- Run `brew install zsh python python3 ruby node ffmpeg youtube-dl`
Make `npm -g ls` list on one line and stop docs from being installed with gems with:
```
echo 'depth=0' >> ~/.npmrc; echo 'gem: --no-ri --no-rdoc' >> ~/.gemrc;
```
- Install Oh-My-Zsh with `sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`
- Run `brew cask install iterm2 sublime-text3 google-chrome firefoxdeveloperedition adium;`
- Run `npm install -g gulp castnow nodetree`
- Run `

INPUT MONO FONT http://input.fontbureau.com/download/


- Install OS X updates from App Store
- Install Xcode
- Install Homebrew from http://brew.sh
- Run `brew update`
- Run `brew install caskroom/cask/brew-cask`
- Run `brew tap caskroom/versions`
- Run:
```Shell
brew cask install iterm2 sublime-text3 vlc transmission adium skype google-chrome firefoxdeveloperedition`
```
- Download dracula them from github into ~/github

load the dracula theme into iterm2

brew install git zsh

brew install vim ruby python python3 node

install input mono font

and set iterm2 font as 18pt input mono thin
