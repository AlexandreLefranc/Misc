# System update

GUI:

- Open Software
- Updates

CLI:

```bash
sudo dnf clean all
sudo dnf upgrade
```

# Add RPM Fusion

https://rpmfusion.org/

RPM Fusion provides software that the Fedora Project or Red Hat doesn't want to ship.

CLI:

Enable repository

```bash
sudo dnf install https://mirrors.rpmfusion.org/free/fedora/rpmfusion-free-release-$(rpm -E %fedora).noarch.rpm https://mirrors.rpmfusion.org/nonfree/fedora/rpmfusion-nonfree-release-$(rpm -E %fedora).noarch.rpm
```

To be able to install packages from GNOME Software

```bash
sudo dnf groupupdate core
```

# Add GNOME Tweaks

GUI:

- Open Software
- Search and install Tweaks

CLI:

```bash
sudo dnf install gnome-tweaks
```

Tweaks > Windows > Disable Attach Modal Dialogues
Tweaks > Clavier et souris > Comportement de la touche Verr. Maj > Verr. Maj bascule le blocage majuscule

# Add GNOME Extension

GUI:

- Open Software
- Search and install Extensions

CLI:

```bash
sudo dnf install gnome-extensions-app
```

- Go to https://extensions.gnome.org
- Install browser extension
- Dash to Dock / Dash to Panel
- Caffeine
- Desktop Icons NG (DING)
- Gnome 4x UI Improvements
- Workspace Indicator
- GNOME Fuzzy App Search
- ArcMenu
