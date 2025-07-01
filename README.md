# XPipe PTB

Here you will find XPipe PTB (Public Test Build) releases. These builds are published prior to full releases to see whether everything is production ready and contain the latest new features.

In case you're interested in trying out the PTB versions, you can easily do so without any limitations.
The regular releases and PTB releases are designed to not interfere with each other and can therefore be installed and used side by side.
They have different IDs/package names/bundle names/installation directories/configuration directories and do not interfere with each other in any way.

The primary goal of the PTB is to gather early feedback for new features and fixes before they hit the main releases.
These builds are not as thoroughly tested yet, so they will be more unstable than the regular releases.
There is no fixed timeline on when the PTB branch will be merged, it will be promoted once sufficient testing has been done.

PTB builds do not import your existing connections from the normal releases as the goal is to achieve a good testing coverage.
An import functionality would result in some workflows, e.g. the creation of new connections, not being commonly tested.

## Installation

Installing the PTB release works just as with the regular releases. You can also use the built-in updating functionality to upgrade a PTB build to the next one if you are using the installer distribution.
Since there will be frequent updates, using the installers is therefore recommended.

### Installers

- [Windows .msi Installer (x86-64)](https://github.com/xpipe-io/xpipe-ptb/releases/latest/download/xpipe-installer-windows-x86_64.msi)
- [Windows .msi Installer (ARM 64)](https://github.com/xpipe-io/xpipe-ptb/releases/latest/download/xpipe-installer-windows-arm64.msi)
- [Linux .deb Installer (x86-64)](https://github.com/xpipe-io/xpipe-ptb/releases/latest/download/xpipe-installer-linux-x86_64.deb)
- [Linux .rpm Installer (x86-64)](https://github.com/xpipe-io/xpipe-ptb/releases/latest/download/xpipe-installer-linux-x86_64.rpm)
- [MacOS .pkg Installer (x86-64)](https://github.com/xpipe-io/xpipe-ptb/releases/latest/download/xpipe-installer-macos-x86_64.pkg)
- [MacOS .pkg Installer (ARM 64)](https://github.com/xpipe-io/xpipe-ptb/releases/latest/download/xpipe-installer-macos-arm64.pkg)

### Portable

- [Windows .zip Portable (x86-64)](https://github.com/xpipe-io/xpipe-ptb/releases/latest/download/xpipe-portable-windows-x86_64.zip)
- [Windows .zip Portable (ARM 64)](https://github.com/xpipe-io/xpipe-ptb/releases/latest/download/xpipe-portable-windows-arm64.zip)
- [Linux .tar.gz Portable (x86-64)](https://github.com/xpipe-io/xpipe-ptb/releases/latest/download/xpipe-portable-linux-x86_64.tar.gz)
- [Linux .AppImage Portable (x86-64)](https://github.com/xpipe-io/xpipe-ptb/releases/latest/download/xpipe-portable-linux-x86_64.AppImage)
- [MacOS .dmg Portable (x86-64)](https://github.com/xpipe-io/xpipe-ptb/releases/latest/download/xpipe-portable-macos-x86_64.dmg)
- [MacOS .dmg Portable (ARM 64)](https://github.com/xpipe-io/xpipe-ptb/releases/latest/download/xpipe-portable-macos-arm64.dmg)

### Arch

There is an official [AUR package](https://aur.archlinux.org/packages/xpipe-ptb) available that you can either install manually or via an AUR helper such as with `yay -S xpipe-ptb`.

### Homebrew

You can also use [Homebrew](https://github.com/xpipe-io/homebrew-tap) to install the PTB with `brew install --cask xpipe-io/tap/xpipe-ptb`.

### Install Script

For a quick and convenient installation, you can use these scripts.

#####  Linux / MacOS

The script supports installation via `apt`, `rpm`, and `pacman` on Linux, plus a `.pkg` install on macOS:

```
bash <(curl -sL https://github.com/xpipe-io/xpipe/raw/master/get-xpipe.sh) -s
```

##### Windows

```
powershell -ExecutionPolicy Bypass -Command iwr "https://github.com/xpipe-io/xpipe/raw/master/get-xpipe.ps1" -OutFile "$env:TEMP\get-xpipe.ps1" ";"  "&" "$env:TEMP\get-xpipe.ps1" -UseStageDownloads
```
