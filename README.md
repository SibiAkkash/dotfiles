Install gnome-tweaks

### Extensions
* Download and extract the extension to `~/.local/share/gnome-shell/extensions`
* [User themes](https://extensions.gnome.org/extension/19/user-themes/)
* [Sound Input-Output chooser](https://extensions.gnome.org/extension/906/sound-output-device-chooser/)
* Papirus icons


### Terminal setup
* zsh
* oh-my-zsh
* Plugins
    * zsh-syntax-highlighting
    * zsh-autosuggestions
* powerline10k zsh theme
* Colour themes: https://mayccoll.github.io/Gogh/ 

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
* Pipewire to detect bluetooth profil