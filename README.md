# iterm-setup
This is how Xavian sets up his iTerm. Drop him a tweet @xavianaxw if you have any questions ;)

## Installing iTerm2
`brew cask install iterm2`

or [Download](http://www.iterm2.com/downloads.html) and install it manually

## Setting up colors
1. Download themes from [iterm2colorschemes.com](https://github.com/mbadolato/iTerm2-Color-Schemes/zipball/master)
2. Navigate to `Preferences > Profiles > Colors > Import (dropdown)` and select **Afterglow**

## Install and setup Oh My Zsh
`sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`

When the installation is done, edit `~/.zshrc` and set `ZSH_THEME="agnoster"`

Add `DEFAULT_USER={$yourUsernameHere}` after `ZSH_THEME`

Copy the `agnoster.zsh-theme` and place it in `~/.oh-my-zsh/themes`

## Patching Font (I use Meslo)
Click [here](https://github.com/powerline/fonts/blob/master/Meslo%20Slashed/Meslo%20LG%20M%20Regular%20for%20Powerline.ttf) then "view raw" to download the font.

[More here](https://github.com/powerline/fonts)

## Autosuggestion
Just follow these steps: https://github.com/tarruda/zsh-autosuggestions#oh-my-zsh

If the auto suggestions do not appear to show, it could be a problem with your color scheme. Under "iTerm -> Preferences -> Colors tab", check the value of Black Bright, that is the color your auto suggestions will have. It will be displayed on top of the Background color. If there is not enough contrast between the two, you won't see the suggestions even if they're actually there..
