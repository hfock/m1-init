# m1-init

Fresh M1 Setup

### iTerm2 - Terminal

https://iterm2.com/

### ohmyz.sh

https://ohmyz.sh/

```
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

### powerlevel10k

https://github.com/romkatv/powerlevel10k

```
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ~/powerlevel10k
echo 'source ~/powerlevel10k/powerlevel10k.zsh-theme' >>~/.zshrc
```

### Visual Studio Code

https://code.visualstudio.com/

cmd + shift + p 

and execute 

```
Shell Command: Install 'code' command in PATH
```

### Miniconda and Miniforge

Inspired by Jeff Heaton's YouTube Video https://www.youtube.com/watch?v=w2qlou7n7MA

#### Miniforge

https://developer.apple.com/metal/tensorflow-plugin/

```
chmod +x ~/Downloads/Miniforge3-MacOSX-arm64.sh
sh ~/Downloads/Miniforge3-MacOSX-arm64.sh
```

Export the block that was appended due to _conda init_ to the .zshrc into a ./.start_miniforge.sh file.

#### Miniconda

https://docs.conda.io/en/latest/miniconda.html

install miniconda bash version.

```
chmod +x ~/Downloads/Miniconda3-latest-MacOSX-x86_64.sh
sh ~/Downloads/Miniconda3-latest-MacOSX-x86_64.sh
```

Export the block that was appended due to _conda init_ to the .zshrc into a ./.start_miniconda.sh file.

So now I am possible to easily change between miniforge and miniconda just by 

```
source .start_miniconda.sh
```

or

```
source .start_miniforge.sh
```
