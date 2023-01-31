# seahorse-nautilus-ext

This is seahorse-nautilus from upstream with one feature added: the file extension for encrypted files is configurable via a gsetting.

![pic](https://snag.gy/HjWFvq.jpg)

# Installation
**arch linux:** `yay -S seahorse-nautilus-ext`

# Configuration
**GUI:** dconf-editor

**CLI:** `gsettings set org.gnome.seahorse.nautilus encryption-extension ".gpg"`

# arch linux user respository
The source code to build the AUR package lives in: `ssh://aur@aur.archlinux.org/seahorse-nautilus-ext.git` and is mirrored to the `master` branch in this GitHub respository

# Copyright
Copyright (C) 2019-2023 Ralph Plawetzki
