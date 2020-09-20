# Maintenance Tool

This is a simple tool for freeing up KOOMPI OS root file system and user home directory
for difference caches. This will help prevent user for bootup failure for not having enough
storage to boot. This usually affect SDDM to start.

# Build

```bash
git clone https://github.com/koompi/os-maintenance-tool.git
cd os-maintenance-tool
makepkg
```

# Install

```bash
sudo pacman -U koompi-maintenance-0.1-1-any.pkg.tar.zst
```
