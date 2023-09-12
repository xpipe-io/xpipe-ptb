# XPipe PTB

Here you will find XPipe PTB (Public Test Build) releases. These builds are published prior to full releases to see whether everything is production ready and contain the latest new features.

In case you're interested in trying out the PTB versions, you can easily do so without any limitations.
The regular releases and PTB releases are designed to not interfere with each other and can therefore be installed and used side by side.
They have different IDs/package names/bundle names/installation directories/configuration directories and do not interfere with each other in any way.

## Installation

Installing the PTB release works just as with the regular releases:

### Installers

Installers are the easiest way to get started and come with an optional automatic update functionality. The following installers are available:

- [Windows .msi Installer (x86-64)](https://github.com/xpipe-io/xpipe/releases/latest/download/xpipe-installer-windows-x86_64.msi)
- [Linux .deb Installer (x86-64)](https://github.com/xpipe-io/xpipe/releases/latest/download/xpipe-installer-linux-x86_64.deb)
- [Linux .rpm Installer (x86-64)](https://github.com/xpipe-io/xpipe/releases/latest/download/xpipe-installer-linux-x86_64.rpm)
- [MacOS .pkg Installer (x86-64)](https://github.com/xpipe-io/xpipe/releases/latest/download/xpipe-installer-macos-x86_64.pkg)

### Portable

If you don't like installers, you can also use portable versions that are packaged as an archive. The following portable versions are available:

- [Windows .zip Portable (x86-64)](https://github.com/xpipe-io/xpipe/releases/latest/download/xpipe-portable-windows-x86_64.zip)
- [Linux .tar.gz Portable (x86-64)](https://github.com/xpipe-io/xpipe/releases/latest/download/xpipe-portable-linux-x86_64.tar.gz)
- [MacOS .dmg Portable (x86-64)](https://github.com/xpipe-io/xpipe/releases/latest/download/xpipe-portable-macos-x86_64.dmg)

### Install Script

You can also install XPipe by pasting the installation command into your terminal. This will perform the full setup automatically.

#####  Linux / MacOS

The script supports installation via `apt`, `rpm`, and `pacman` on Linux, plus a `.pkg` install on macOS:

```
bash <(curl -sL https://raw.githubusercontent.com/xpipe-io/xpipe/master/get-xpipe.sh) -s
```

##### Windows

```
powershell -ExecutionPolicy Bypass -Command iwr "https://raw.githubusercontent.com/xpipe-io/xpipe/master/get-xpipe.ps1" -OutFile "$env:TEMP\get-xpipe.ps1" ";"  "&" "$env:TEMP\get-xpipe.ps1" -UseStageDownloads
```

You can also use the built-in updating functionality to upgrade a PTB build to the next in case you are using the installer distribution.
