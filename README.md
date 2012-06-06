## my_vim

My Vim Files, Using Pathogen (Organizing my plugins on bundle dir)


Clone it into ~/.vim using:

```cmd
git clone https://github.com/manfe/my_vim.git ~/.vim
```

After it need load the .vimconfig inside your .vimrc, inside your .vimrc type:

```cmd
source ~/.vim/.vimconfig
```

The Vim Color Solarized didn't work perfectly on my Gnome Terminal so a run these
lines on my terminal and it's working now and no need more the vim-color-solarized inside the bundle dir

```cmd
gconftool-2 --set "/apps/gnome-terminal/profiles/Default/use_theme_background" --type bool false
gconftool-2 --set "/apps/gnome-terminal/profiles/Default/use_theme_colors" --type bool false
gconftool-2 --set "/apps/gnome-terminal/profiles/Default/palette" --type string "#070736364242:#D3D301010202:#858599990000:#B5B589890000:#26268B8BD2D2:#D3D336368282:#2A2AA1A19898:#EEEEE8E8D5D5:#00002B2B3636:#CBCB4B4B1616:#58586E6E7575:#65657B7B8383:#838394949696:#6C6C7171C4C4:#9393A1A1A1A1:#FDFDF6F6E3E3"
gconftool-2 --set "/apps/gnome-terminal/profiles/Default/background_color" --type string "#00002B2B3636"
gconftool-2 --set "/apps/gnome-terminal/profiles/Default/foreground_color" --type string "#65657B7B8383"
```


Using:

* Fugitive Vim (Best way to use git inside vim)
* Zencoding (HTML, CSS fast editing)
* Vim Color Solarized (A good colorscheme for vim, but using terminal color scheme)

