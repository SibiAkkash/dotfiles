Install gnome-tweaks

### Extensions
* Download and extract the extension to `~/.local/share/gnome-shell/extensions`
* [User themes](https://extensions.gnome.org/extension/19/user-themes/)
* [Sound Input-Output chooser](https://extensions.gnome.org/extension/906/sound-output-device-chooser/)


---
## Terminal setup
I'm installing all config stuff to `$HOME/.config`, so all below installs will follow that (Terminator follows this by default, zsh doesn't)

### Terminator 
- `apt install terminator`
- Load config if needed - `cp ./terminator-config $HOME/.config/terminator/config`
- Install [Terminator themes](https://github.com/EliverLara/terminator-themes)
   

### zsh
Add `ZDOTDIR=$HOME/.config/zsh` to top of `$HOME/.zshenv` ([How to set ZDOTDIR](https://www.reddit.com/r/zsh/comments/3ubrdr/proper_way_to_set_zdotdir/))

#### oh-my-zsh
`ZSH="$ZDOTDIR/.oh-my-zsh" sh install.sh` ([Install to custom path](https://github.com/ohmyzsh/ohmyzsh#custom-directory)) 

#### Plugins
- zsh-syntax-highlighting
- zsh-autosuggestions

#### Powerlevel10k theme
- [Install powerline10k zsh theme](https://github.com/romkatv/powerlevel10k#oh-my-zsh)
- [Install MesloLGS NF font](https://github.com/romkatv/powerlevel10k#manual-font-installation) - This font works best with p10k
    - While `p10k configure` you can tell it to download this font
    - If we're using a pre-existing `p10k.zsh` file, the fonts many not be downloaded on the machine yet, so download them in that case.
- Run `p10k configure` if you want to configure from scratch, else source it from an existing file
---

#### Colour themes
https://mayccoll.github.io/Gogh/ 

#### Dircolors
* How does it work: https://askubuntu.com/questions/466198/how-do-i-change-the-color-for-directories-with-ls-in-the-console
* Download a dircolors file and store it in `~/.dircolors`
* Run `dircolors path-to-file -b >> ~/.zshrc`
* The above command generates the `LS_COLORS` variable and writes it to the `.zshrc` file
* Files with execute permission override the colour, EXEC files have separate colour in the dircolors file - https://unix.stackexchange.com/questions/174538/ls-color-auto-dir-colors-not-working-in-one-directory


#### Tilix
* What is a login shell ?
* add few lines in .zshrc for tilix to work properly

### Audio
* Pavucontol
* Pipewire to detect bluetooth profile - https://atish3604.medium.com/solved-bluetooth-headset-mic-not-working-detected-in-ubuntu-20-04-86a5236444d0

### Apps
[ ] Brave
[ ] VSCode
[ ] Discord
[ ] VLC
[ ] Postman
[ ] Okular reader
[ ] Spotify
[ ] Anydesk
[ ] Chromium
[ ] Insync
[ ] Teams
[ ] Obsidian
[ ] Virtual box
[ ] qbittorent
[ ] proton vpn
[ ] SimpleScreenRecorder
[ ] Slack
[ ] Steam
[ ] Telegram

### dev
[ ] miniconda
[ ] matlab
[ ] cuda toolkit 11.3
[ ] nvm

### Browser extensions
[ ] Onetab
[ ] privacy badger
[ ] ublock origin
[ ] decentraleyes
[ ] https everwhere
[ ] lastpass
[ ] clean twitter
[ ] userstyles
[ ] darkreader

