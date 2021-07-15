# Switchboard Desktop Plug
[![Translation status](https://l10n.elementary.io/widgets/switchboard/-/switchboard-plug-pantheon-shell/svg-badge.svg)](https://l10n.elementary.io/engage/switchboard/?utm_source=widget)

![screenshot](data/screenshot-wallpaper.png?raw=true)

## Building and Installation

You'll need the following dependencies:

* gnome-settings-daemon-dev
* libswitchboard-2.0-dev
* libgnome-desktop-3-dev
* libgee-0.8-dev
* libgexiv2-dev
* libgtk-3-dev (>= 3.22)
* libplank-dev
* libgranite-dev
* meson
* valac

Run `meson` to configure the build environment and then `ninja` to build

    meson build --prefix=/usr
    cd build
    ninja

To install, use `ninja install`

    sudo ninja install
