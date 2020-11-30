# useful-shell-stuff
Useful shell utilities and decorations

## installing pk10
clone the pk10k github repo
```
brew install romkatv/powerlevel10k/powerlevel10k
cd ${HOME}/src/github/datwiz/useful-shell-stuff
cp ./zsh/p10k.zsh ${HOME}/.p10k.zsh
cp ./zsh/zshrc ${HOME}/.zshrc
cp ./zsh/git-flow-completion.zsh ${HOME}/.git-flow-completion.zsh
```

If on zsh startup, zsh complains about insecure directories, run `compaudit` to identify the
offending dirs.
```
# the fix on MacOS as of 2020-12-01
sudo chmod g-w /usr/local/share/zsh
sudo chmod g-w /usr/local/share/zsh/site-functions
```

Install the MesloLGS fonts following the instructions in the p10k github repo.  https://github.com/romkatv/powerlevel10k#fonts
Summary:
* download and install ther 4 MesloLSG font packages
* update iTerm2 to use the new fonts
* update VSCode to use the new fonts

## zsh stuff
zsh prompt

## bash stuff
bash prompt
