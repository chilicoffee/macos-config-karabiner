# Overview

This configuration includes complex modifications such as
- Change Right Control + Insert to Play-Pause Media key
- Change Right Control + Delete to Previous Media key
- Change Right Control + End to Next Media key
- Change Right Control + Home to Mute volume
- Change Right Control + Page Up to Increase Volume
- Change Right Control + Page Up to Decrease Volume

Note: This also includes couple of simple modifications that
- Assigns Right Control to right most key, before <- arrow
- And others.. such as tilde key placement (specific to one of my keyboards)

## Installation

Option 1: Clone this repo and symlink the config file
```
$ cd ~
$ git clone git@gitlab.com:janis.puris/karabiner-config.git
$ cd karabiner-config
$ mv ~/.config/karabiner/karabiner.json ~/.config/karabiner/karabiner.json.bak && ln -s $(pwd)/karabiner-config/karabiner.json ~/.config/karabiner/karabiner.json
```
Option 2: Download the config file without cloning git repo
```
TODO
```

## Dependencies
- Karabiner https://pqrs.org/osx/karabiner/, also available on brew cask https://github.com/Homebrew/homebrew-cask/blob/master/Casks/karabiner.rb