# Extensive Morphe Builder
[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/morphe_modules_apks)
[![CI](https://github.com/sixstrings/morphe-builder/actions/workflows/ci.yml/badge.svg?event=schedule)](https://github.com/sixstrings/morphe-builder/actions/workflows/ci.yml)
[![GitHub License](https://img.shields.io/github/license/sixstrings/morphe-builder?logo=gnu&label=License&link=https%3A%2F%2Fgithub.com%2Fsixstrings%2Fmorphe-builder%2Fblob%2Fmain%2FLICENSE)](https://github.com/sixstrings/morphe-builder/blob/main/LICENSE)
[![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/sixstrings/morphe-builder/total?logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjI0IiBoZWlnaHQ9IjI0Ij48cGF0aCBkPSJNNC43NSAxNy4yNWEuNzUuNzUgMCAwIDEgLjc1Ljc1djIuMjVjMCAuMTM4LjExMi4yNS4yNS4yNWgxMi41YS4yNS4yNSAwIDAgMCAuMjUtLjI1VjE4YS43NS43NSAwIDAgMSAxLjUgMHYyLjI1QTEuNzUgMS43NSAwIDAgMSAxOC4yNSAyMkg1Ljc1QTEuNzUgMS43NSAwIDAgMSA0IDIwLjI1VjE4YS43NS43NSAwIDAgMSAuNzUtLjc1WiIgZmlsbD0iI0ZGRkZGRiI+PC9wYXRoPjxwYXRoIGQ9Ik01LjIyIDkuOTdhLjc0OS43NDkgMCAwIDEgMS4wNiAwbDQuOTcgNC45NjlWMi43NWEuNzUuNzUgMCAwIDEgMS41IDB2MTIuMTg5bDQuOTctNC45NjlhLjc0OS43NDkgMCAxIDEgMS4wNiAxLjA2bC02LjI1IDYuMjVhLjc0OS43NDkgMCAwIDEtMS4wNiAwbC02LjI1LTYuMjVhLjc0OS43NDkgMCAwIDEgMC0xLjA2WiIgZmlsbD0iI0ZGRkZGRiI+PC9wYXRoPjwvc3ZnPg==&label=Downloads&link=https%3A%2F%2Fgithub.com%2Fsixstrings%2Fmorphe-revanced-builder%2Freleases)](https://github.com/sixstrings/morphe-builder/releases)

This Morphe builder creates [Magisk](https://github.com/topjohnwu/Magisk)/[KernelSU](https://github.com/tiann/KernelSU) modules and also APKs for [Morphe](https://github.com/MorpheApp) versions of YouTube, YouTube Music and Reddit.

#### **Get the latest CI release [here](https://github.com/sixstrings/morphe-builder/releases/latest).**

## Installation
### Non-root users
- Install [Morphe MicroG-RE](https://github.com/MorpheApp/MicroG-RE/releases).
- Download the APK files you want to install from the [releases page](https://github.com/sixstrings/morphe-builder/releases/latest).

### Install and update APKs with Obtainium

Use [Obtainium](https://github.com/ImranR98/Obtainium) to install and update APKs directly from the source and get notified when new versions are released.
A configuration file is provided for quick and easy setup.

- Install the latest [Obtainium](https://github.com/ImranR98/Obtainium) version.
- Import [obtanium-sixstrings-config.json](https://xdaforums.com/attachments/obtainium-sixstrings-config-json.6342022/?hash=50c4f2b0596df8194076054649dba330).
- Install or update your APKs.

### Root users
- Download the ZIP files you want to flash from the [releases page](https://github.com/sixstrings/morphe-builder/releases/latest).
  
- Use [zygisk-detach](https://github.com/j-hc/zygisk-detach) to detach YouTube, YouTube Music and other apps from the Play Store.


## Building Locally
### On Termux
```bash
bash <(curl -sSf https://raw.githubusercontent.com/sixstrings/morphe-builder/main/build-termux.sh)
```
### On Desktop
```bash
git clone https://github.com/sixstrings/morphe-builder
cd morphe-revanced-builder
./build.sh
```

## Credits
- [j-hc](https://github.com/j-hc) for creating this builder and for zygisk-detach.
- [Morphe](https://github.com/MorpheApp) team for their amazing Morphe-patches.
- [ImranR98](https://github.com/ImranR98) for Obtainium.
- [peternmuller](https://github.com/peternmuller/revanced-morphe-builder) for the fork.

## License
    Copyright (C) 2024-2026 Holger Richard S.

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program. If not, see <https://www.gnu.org/licenses/>.

    
