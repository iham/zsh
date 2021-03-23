# zsh
zsh setup and configs

on my mac(s) i use zsh with oh my zsh and powerlevel10k.

<img width="566" alt="Screenshot 2021-03-23 at 15 38 04" src="https://user-images.githubusercontent.com/36721/112163928-c5625d00-8bed-11eb-9c37-bbab79aa0532.png">

## this setup includes:
- path shortening on deeper levels
- context of user
- python version and venv name if "inside" one
- autosuggestions
- git pipenv pyenv zsh-autosuggestions
- start pipenv when entering a folder with a pythin virtual env
- neat icons and font ;)

## installation

### install home brew
```sh -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"```
you might need to run xcode installer or alike, but home brew guides you through that.

### install pyenv (install multiple python versions and set them up system wide or local)
```brew install pyenv```

### install pipenv (makes use of pyenv and for clean separation of python modules and a nice cli)
```brew install pipenv```

### install fonts
https://github.com/romkatv/powerlevel10k#manual-font-installation
and change your terminals font to the "MesloLGS NF" family.

### install oh my zsh
```sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"```

### install zsh autosuggestions
```git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions```

### install powerlevel10k
make sure ```$ZSH_CUSTOM``` exists; if not: ```source ~/.zshrc``` and then:
```git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k```

### update zsh
replace configs in ~/.zshrc with those here in <.zshrc>

### update powerlevel10k
replace configs in ~/.p10k.zsh with those here in <.p10k.zsh>
