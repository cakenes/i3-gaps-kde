![Logo](docs/logo-30.png) i3: A tiling window manager
=====================================================

[![Build Status](https://travis-ci.org/i3/i3.svg?branch=next)](https://travis-ci.org/i3/i3)
[![Issue Stats](https://img.shields.io/github/issues/i3/i3.svg)](https://github.com/i3/i3/issues)
[![Pull Request Stats](https://img.shields.io/github/issues-pr/i3/i3.svg)](https://github.com/i3/i3/pulls)

i3 is a tiling window manager for X11.

For more information about i3, please see [the project's website](https://i3wm.org/) and [online documentation](https://i3wm.org/docs/).

For information about contributing to i3, please see [CONTRIBUTING.md](.github/CONTRIBUTING.md).

## Purpose of this repo (by sLite, upstream maintainer)

Vanilla i3 doesn't play that well with KDE/Plasma, and I love KDE, that's why I'm maintaining this repo.

Up until now I just added code and haven't modified vanilla i3 code. I will try to stick to this in the future ensuring simple merges.

### Branches

* **master, next**: those will stay vanilla for easy fast-forward merges of the official i3 repo

* **kde-master**: that's what you want if you want to use i3 with KDE/Plasma from https://github.com/sLite/i3 maintained by me (sLite from upstream and PJK136 here)

* **kde-wm-icons-master**: PJK136's personal branch with some extra stuff merged like window-icons patch from https://github.com/mickael9/i3-window-icons or a PKGBUILD for Arch packaging

I won't maintain an up-to-date **next** branch with KDE/Plasma patches included, if you need that, feel free to clone :)

I (PJK136) will sometimes rebase **kde-wm-icons-master** to include lastest commits from different repos

### Features

* Proper handling of KDE/Plasma desktop (_NET_WM_WINDOW_TYPE_DESKTOP)
* Proper handling of KDE/Plasma popups and floating panels (mostly widget stuff) (_NET_WM_STATE_STAYS_ON_TOP)

### i3-config

No special settings needed.

If you want kmix, kcalc and those other small tools floating, those are settings you still have to do with your i3 config.

You can check https://github.com/sLite/i3-config for an example config and instructions to set up KDE integration.

### Credits

* Michael Stapelberg for this awesome project, and all the contributors for their work.
* Marius Muja for his KDE fixes on earlier versions of i3.
* sLite for his KDE patches on current versions of i3.
* Mickaël Thomas for his window icons patch.
