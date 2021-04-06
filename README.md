# My config files for Linux

**My Configuration as a Linux User**

Take a look -> Understand what means -> Copy what you want to your folder

### zsh

- **Install `zsh` `curl` `git` first**

*Ubuntu/Debian*
```bash
sudo apt-get install zsh curl git
```
*Arch Linux*
```bash
sudo pacman -S zsh curl git
```

- Install oh-my-zsh

```bash
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```
OR
```bash
sh -c "$(wget https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh -O -)"
```

### ranger

- Compress and extract archives: <br>
`:compress` `:extracthere` depends on atool

**Atool installation**

*Arch Linux*:

```bash
sudo pacman -S atool
```

*Ubuntu*:

```bash
sudo apt install atool
```
