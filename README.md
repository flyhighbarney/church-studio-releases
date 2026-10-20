# Church Studio releases

This repo holds the installers and online updates for **Church Studio**. Church Studio adds the Church Control plugin and the Studio theme to OBS Studio 32.2.2, which runs with DistroAV (NDI).

Each release carries these files:
- `ChurchStudio-Update-<version>.exe`: the plugin and the theme. Church Studio downloads it by itself and installs it when OBS closes.
- `manifest.json`: what Church Studio reads to find out whether a newer version is out.
- `SHA256SUMS.txt`: checksums. Church Studio checks the update's SHA-256 before running it.
- `church-studio-<version>-source.zip`: the source code of the plugin, the theme and the installer (GPL-2.0-or-later).

To install a version by hand, close OBS and run its `ChurchStudio-Update-<version>.exe`. That also goes back to an older version. The first install on a new PC uses the full Church Studio setup, which isn't published here.

Church Studio builds on [OBS Studio](https://obsproject.com) and [DistroAV](https://github.com/DistroAV/DistroAV), which are both GPL-2.0. It is not made or endorsed by the OBS Project or NDI.
