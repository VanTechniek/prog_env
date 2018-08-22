# Custom Programming Environment Setup
1. Install zsh with Homebrew

   `brew install zsh zsh-completions`

2. Add zsh-completions to .zshrc file

   `fpath=(/usr/local/share/zsh-completions $fpath)`

1. Install Oh My Zsh

   `sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`

2. Make zsh the default shell

   `chsh -s $(which zsh)`

3. Next command refreshes the terminal

   `source ~/.zshrc`

4. Download powerline fonts

   `https://github.com/powerline/fonts`

5. Run `install.sh` from the download file

6. Dowload the powerline9k theme

   `git clone https://github.com/bhilburn/powerlevel9k.git ~/.oh-my-zsh/custom/themes/powerlevel9k`

7. Select the theme in zshrc

   `ZSH_THEME="powerlevel9k/powerlevel9k"`


