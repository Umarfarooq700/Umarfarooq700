English
&nbsp;&nbsp;| &nbsp;&nbsp;
<a
href="https://github.com/Umarfarooq700/mobox/blob/main/README-ru.md">Русский</a>
&nbsp;&nbsp;| &nbsp;&nbsp;
<a href="https://github.com/Umarfarooq700/mobox/blob/main/README-ua.md">Українська</a>
&nbsp;&nbsp;| &nbsp;&nbsp;
<a href="https://github.com/Umarfarooq700/mobox/blob/main/README-pt_BR.md">Português Brasileiro</a>
&nbsp;&nbsp;| &nbsp;&nbsp;
<a href="https://github.com/Umarfarooq700/mobox/blob/main/README-pl.md">Polski</a>
&nbsp;&nbsp;| &nbsp;&nbsp;
<a href="https://github.com/Umarfarooq700/mobox/blob/main/README-ja.md">日本語</a>

##

`Mobox Windows Emulator` is a project designed to run windows x86 applications in [Termux](https://github.com/termux/termux-app) using [Box64](https://github.com/ptitSeb/box64) and [Wine](https://www.winehq.org/).

# Installation
1. Install
[Termux](Termux_0.118.1_apkcombo.com.apk),
[Termux-X11](https://raw.githubusercontent.com/olegos2/mobox/main/components/termux-x11.apk) and
[Input Bridge](https://raw.githubusercontent.com/olegos2/mobox/main/components/inputbridge.apk).

2. Open Termux And Paste Command

```bash
curl -s -o ~/x https://raw.githubusercontent.com/Umarfarooq700/moboxwindowsemu/main/install && . ~/x
```

3. Type `Mobox Windows Emulator` in Termux.

 # Configuration
 ## Wine
Wine Can Be Installed Or Uninstalled In `Manage Packages` Menu.
To Select Wine Container, Use Option 4 In Main Menu.
Mesa VirGL, Turnip, Wine Mono And Gecko Can Be Installed In Wine Start Menu.
## Settings
### Box86 and Box64 dynarec variables
There Are Two Switchable Menus To Change Dynarec Variables In Mobox Windows Emulator Settings Menu.
For More Information About Dynarec Variables See [Box64 Usage](https://github.com/ptitSeb/box64/blob/main/docs/USAGE.md) And [Box86 usage](https://github.com/ptitSeb/box86/blob/master/docs/USAGE.md)
### System settings
To Change Wine Locale, Dxvk Hud Preset Or Turnip Settings, Use `System Settings` Menu In Mobox Windows Emulator.
Fallback Resolution Is Used Only When X11 Resolution Couldn't Be Detected Automatically.
If you have Snapdragon 6 Gen 1, 8+ Gen 1, 7+ Gen 2, Enable The Second Option In `Select A7xx Flickering Fix (TU_DEBUG)` In `System Settings` Menu.
### Root settings
* `Display Resolution Mode` Rxact
* `Display Resolution` 1280x720
* `Reseed Screen While Soft Keyboard Is Open` OFF
* `Fullscreen On Device Display` ON
* `Force Landscape Orientation` ON
* `Hide display Cutout` ON
* `Show Additional Keyboard` OFF
* `Prefer Scancodes When Possible` ON
## Controls
For Touch Controls Input Bridge App Is Required
## Uninstall
To Uninstall Mobox, Use `Backup And Restore` Menu.
## Debugging
To Enable Logging - Select Option 2 In Mobox Windows Emulator -> Settings -> Debug Settings Menu. Path To The Log Is /Devicestorage/mobox_log.txt

## Support Status
### Android
* `Android 11` or Higher Is Recommended.
### Device
* Most Android Cellphones Can Run `Mobox Windows Emulator` And DirectX 9 Games Using Mesa VirGL.
 * Snapdragon Device With Adreno 6xx or Adreno 710-740 Is Recommended To Achieve Best Performance And Compatibility With Turnip+DXVK.
### Root
* Root is not required.

  ## Known issues
* If Termux App Crashes When Trying To Enter Mobox Windows Emulator Menu, Then Remove custom Theme Scripts:
  ```bash
  rm -rf $PREFIX/glibc/opt/termux-style

* Some Devices May Have Prefix Creation Freeze Issues When Installing PhysX, In This Case Change Settings In `Compatibility Settings` Menu
* For SD845 Device, Disable Dri3 In `Compatibility Settings` Menu



## Third party applications

[glibc-packages](https://github.com/termux-pacman/glibc-packages)

[Box64](https://github.com/ptitSeb/box64)

[Box86](https://github.com/ptitSeb/box86)

[DXVK](https://github.com/doitsujin/dxvk)

[DXVK-ASYNC](https://github.com/Sporif/dxvk-async)

[DXVK-GPLASYNC](https://gitlab.com/Ph42oN/dxvk-gplasync)

[VKD3D](https://github.com/lutris/vkd3d)

[D8VK](https://github.com/AlpyneDreams/d8vk)

[Termux-app](https://github.com/termux/termux-app)

[Termux-x11](https://github.com/termux/termux-x11)

[Wine](https://wiki.winehq.org/Licensing)

[wine-ge-custom](https://github.com/GloriousEggroll/wine-ge-custom)

[Mesa](https://docs.mesa3d.org/license.html)

[mesa-zink-11.06.22](https://github.com/alexvorxx/mesa-zink-11.06.22)

[Mesa-VirGL](https://github.com/alexvorxx/Mesa-VirGL)

