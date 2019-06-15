# seahorse-nautilus-ext

This is seahorse-nautilus from upstream with one feature added: the file extension for encrypted files is configurable via a gsetting.

![pic](https://snag.gy/HjWFvq.jpg)

## Installation
**Arch-Linux:** `pakku -S seahorse-nautilus-ext`

## Configuration
**GUI:** dconf-editor

**CLI:** `gsettings set org.gnome.seahorse.nautilus encryption-extension ".gpg"`