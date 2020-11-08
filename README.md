# powerlevel10k

```
cd ~
git clone git@github.com:pghalliday-dotfiles/.p10k.git
cp -f .p10k/dotfiles/.* .
```

## Fonts

Install all 4 fonts from the fonts folder by double clicking them and selecting install

```
fonts/MesloLGS NF Bold.ttf
fonts/MesloLGS NF Bold Italic.ttf
fonts/MesloLGS NF Italic.ttf
fonts/MesloLGS NF Regular.ttf
```

and follow the instructions here for your terminal:

https://github.com/romkatv/powerlevel10k#manual-font-installation

## Updating config

If you run:

```
p10k configure
```

Then a new configuration will be generated at `~/.p10k.zsh`.

Then to update this repository you should do the following:

```
cp -f ~/.p10k.zsh ~/.p10k/dotfiles/
cp -f ~/.p10k/dotfiles/.* ~/
```

Alternatively just call the helper script at

```
~/.p10k/scripts/import-configuration
```

after running `p10k configure` to do the copiies

Then add, commit and push.

