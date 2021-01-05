# myzsh

Just a script which setups my zsh environment.


## Requirement
ZSH version is greater than 5.2

For CentOS user, the version of ZSH package on yum is too low, you build your own version.

https://jdhao.github.io/2018/10/13/centos_zsh_install_use/


## Usage

Via curl:

```shell
sh -c "$(curl -fsSL https://raw.githubusercontent.com/kerwenwwer/myzsh/master/install.sh)"
```

Via wget:

```shell
sh -c "$(wget https://raw.githubusercontent.com/kerwenwwer/myzsh/master/install.sh -O -)"
```

**NOTE**: The provided one-click installation script will install myzsh to `~/.myzsh`. DO NOT remove this directory because the file `~/.zshrc` is just a symbolic link.

## Plugin list
* [zim](https://github.com/zimfw/zimfw)
* [powelevel10k](https://github.com/romkatv/powerlevel10k)
* [zsh-completion](https://github.com/zsh-users/zsh-completions)
* [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions)
* [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting)
* [zsh-history-substring-search](https://github.com/zsh-users/zsh-history-substring-search)