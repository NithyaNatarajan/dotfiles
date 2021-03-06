# dotfiles
Repository to hold my Mac OS X configurations.

## Setup

1. Install xcode-select

    ```shell
    $xcode-select --install
    ```
1. Install [brew](https://brew.sh/)

1. Configure ssh keys and gpg keys

1. Clone this repo to `$HOME`

   ```shell
   $git clone git@github.com:nithyanatarajan/dotfiles.git ${HOME}/dotfiles
   ```

## Usage

1. To install brew packages

   ```shell
   $make brew
   ```

1. To link all dotfiles

   ```shell
   $make install
   ```

1. Configure iterm2

   1. Refer [here](https://stackoverflow.com/a/23356086) (or)
   2. `cp iterm/com.googlecode.iterm2.plist $HOME/Library/Preferences`

1. Configure [tmux](https://github.com/gpakosz/.tmux)

   ```shell
   $git submodule init
   $git submodule update
   $make tmuxc
   ```

1. Other apps
   1. [meeter](https://trymeeter.com/)
   2. [clocker](https://github.com/n0shake/Clocker)
   3. [hidden bar](https://apps.apple.com/us/app/hidden-bar/id1452453066?mt=12)
   4. [fanny](https://github.com/DanielStormApps/Fanny)
