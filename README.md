# dotfiles

## using dotbot

see https://github.com/anishathalye/dotbot

local operations
```
cd dotfiles
mkdir tmux
cp ~/.tmux.conf tmux/tmux.conf
vi install.conf.yaml
git add -A
git commit -m "added more dots"
git push
```

new machine operations
```
git clone git@github.com:raymatthes/dotfiles.git --recursive
cd dotfiles && ./install
```

new changes can be retrieved and installed
```
git pull
./install
```

