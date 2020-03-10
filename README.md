# Fedora RPM Package For transgui Application

`transgui` is a feature-rich cross platform Transmission BitTorrent
client. It is faster and has more functionality than the built-in web GUI.
See its [home page](https://github.com/transmission-remote-gui/transgui)
for details.

This repository contains a `transgui.spec` file that helps me build
an installation RPM file for `transgui` for my Fedora desktop.

I have created a Fedora COPR repository to support the installation of
the RPMs I created.  To install transgui from this reposditory do:
```
$ sudo dnf copr enable dlk/rpms
$ sudo dnf install transgui
```
