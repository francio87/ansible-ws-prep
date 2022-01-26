# Ansible Workstation Prep

Installs and configures common packages

```
pacman -S ansible
ansible-pull -U https://github.com/francio87/ansible-ws-prep.git --ask-become-pass
```

### Reset / Dump / Load - Gnome Terminal

```
dconf reset -f /org/gnome/terminal/

dconf dump /org/gnome/terminal/ > gnome_terminal_settings_backup.txt

dconf load /org/gnome/terminal/ < gnome_terminal_settings_backup.txt
```



### Theme


If you are running `arch` based distro go ahead and install `chrome-gnome-shell`

```
yay -S chrome-gnome-shell
```

Then get this extensions


- [User Theme](https://extensions.gnome.org/extension/19/user-themes/)
- [AppIndicator and KStatusNotifierItem Support](https://extensions.gnome.org/extension/615/appindicator-support/)

Suggested theme [Nordic Darker](https://www.gnome-look.org/p/1267246/) with [Qogir-dark](https://www.pling.com/p/1296407/) icons theme
