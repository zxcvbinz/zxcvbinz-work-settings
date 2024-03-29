# zxcvbinz-work-settings
A custom themes for terminal and vim.
## Installation
### [Oh My zsh]

Oh My Zsh is installed by running one of the following commands in your terminal. You can install this via the command-line with either `curl`, `wget` or another similar tool.

| Method    | Command                                                                                           |
|:----------|:--------------------------------------------------------------------------------------------------|
| **curl**  | `sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"` |
| **wget**  | `sh -c "$(wget -O- https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`   |
| **fetch** | `sh -c "$(fetch -o - https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"` |

#### Manual inspection

It's a good idea to inspect the install script from projects you don't yet know. You can do
that by downloading the install script first, looking through it so everything looks normal,
then running it:
```shell
wget https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh
sh install.sh
```
### [Sublivim]
#### Installation 
1.  `curl -L http://install.ohmyz.sh | sh`
2.	`curl https://raw.githubusercontent.com/reversTeam/Sublivim/master/installer.sh | sh`
## INSTALL CUSTOM THEME FILES 
```shell
chmod 755 install_custom.sh
./install_custom.sh 
```
copy "profile_zxcvbinz.json" to iTerm2 profile
### [powerlevel10k]
1. `git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k`
2. Set `ZSH_THEME="powerlevel10k/powerlevel10k"` in `~/.zshrc`. ## Not if you use `.zshrc` file from this repo.

#### For VSCode install custom power10k font

### [zsh-autosuggestions] - Plugins

1. `git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions`.
2. add `plugins=(zsh-autosuggestions)` to `./.zshrc`. ## Not if you use `.zshrc` file from this repo.

# Result

### VSCode

![VSCode](https://i.imgur.com/dWHiFPn.png)

### iTerm2

![iTerm2](https://i.imgur.com/cY09eJ4.png)

