## ranger

- Available addtional commands:
   `:paste_as_root` `:toggleVCS` `:mkcd` `:fzf_select` `:compress` `:extracthere`

- Copy ranger config files into $HOME/.config/ranger

```bash
cp -R ./ranger $HOME/.config/
```

- Compress and extract archives: <br>
    `:compress` `:extracthere` depends on atool

**Atool installation**

  Arch Linux:
  
  ```bash
  sudo pacman -S atool
  ```
  
  Ubuntu:
  
  ```bash
  sudo apt install atool
  ```
