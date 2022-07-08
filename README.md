# ezsh
A simple script to setup an awesome shell environment.
Quickly install and setup zsh and oh-my-zsh (https://github.com/robbyrussell/oh-my-zsh) with
* powerlevel10k theme (https://github.com/romkatv/powerlevel10k)
* Nerd-Fonts (https://github.com/ryanoasis/nerd-fonts)
* zsh-completions (https://github.com/zsh-users/zsh-completions)
* zsh-autosuggestions (https://github.com/zsh-users/zsh-autosuggestions)
* zsh-syntax-highlighting (https://github.com/zsh-users/zsh-syntax-highlighting)
* history-substring-search (https://github.com/zsh-users/zsh-history-substring-search)
* fzf (https://github.com/junegunn/fzf)

## Installation
Requirements:
* `git` to clone it.

``` bash
git clone https://github.com/jotyGill/ezsh
cd ezsh
./install.sh 
```
This will install the setup under `~/.config/ezsh/`
Change your terminal's fonts to either "RobotoMono Nerd Font" or "Hack Nerd Font" or "DejaVu Sans Mono Nerd Fonts".
You can also manually install Nerd Fonts of your choice.

## Notes
* If you are already using zsh, your zsh config will be backed up to .zshrc-backup-date

* If the text/icons look broken, make sure your terminal is using one of the Nerd fonts. [discussion](https://github.com/powerline/fonts/issues/185). I recommend "RobotoMono Nerd Font"

* All oh-my-zsh plugins are installed under ~/.config/ezsh/oh-my-zsh/plugin, Other tools (fzf,marker,todo) are installed in ~/.config/ezsh/

* The look of the shell can be very easily customised[https://github.com/bhilburn/powerlevel9k#prompt-customization] by overwriting POWERLEVEL10K settings
in your personal config file under ~/.config/ezsh/zshrc/ . See my setup under example/personal_rc.zsh
