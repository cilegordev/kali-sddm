# Preview

![](preview.png)

# How to install

```zsh
git clone https://github.com/cilegordev/kali-sddm ~/kali-sddm
sudo mv ~/kali-sddm/30-touchpad.conf /etc/X11/xorg.conf.d/
sudo mv ~/kali-sddm /usr/share/sddm/themes/
sudo nano /etc/sddm.conf/10-theme.conf
# or
sudo nano /etc/sddm.conf.d/kde_settings.conf
# ---
[Theme]
Current=kali-sddm
```

# Credits

- Forked from [rototrash](https://github.com/rototrash/tokyo-night-sddm)

# License

[GNU Lesser General Public License v2.1](LICENSE)
