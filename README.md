# useful-shell-stuff
Useful shell utilities and decorations

## installing pk10  
clone the pk10k github repo
```
brew install romkatv/powerlevel10k/powerlevel10k
cd ${HOME}/src/github/datwiz/useful-shell-stuff
cp ./zsh/p10k.zsh ${HOME}/.p10k.zsh
cp ./zsh/zshrc ${HOME}/.zshrc
# cp ./zsh/git-flow-completion.zsh ${HOME}/.git-flow-completion.zsh
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

## App setup
Favorite apps
- Rosetta
- Amethyst
- autopkg
- brew
- iTerm2
- Rancher Desktop - with builtkit enabled
- Slack (App Store)
- VSCode


### VSCode setup
Favorite extensions
- C/C++
- Data Preview
- Docker
- GitHub Copilot
- GraphQL
- Hashicorp Terraform
- Hex Editor
- Kubernetes
- IntelliCode
- Makefile Tools
- Pico-Go
- PlantUML
- Python - brings in Pylance and Jupyter extensions
- Ranbow CSV
- Remote - Containers
- Vim
- YAML

### brew installed apps
Apps installed via brew
- gpg
- jq
- k9s
- poetry
- powerlevel10k
- pyenv
- tree