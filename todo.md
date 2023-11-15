# stuff to document on faq

- log location
- xivlauncher won't save password on KDE with flatpak
- (why/how?) using Rankyn's wine-ge-xiv build https://github.com/rankynbass/wine-ge-xiv/releases

> Those (custom proton-ge builds for Lutris, like protonup-qt) aren't designed to be run outside of their respective Proton or Lutris runtimes. They're also missing our patches.
> 
> You should not be using a Lutris build. If you want custom wine, that’s based off of something newer use one of Rankyn's builds that includes our patches.

[source](https://discord.com/channels/581875019861328007/850387047927250944/1174100247560069141)

> the next major release of xlcore will have some download options so you can switch between supported builds more easily instead of having to provide a custom path
> 
> Using Proton or Lutris builds are still not recommended, but it'll be easier to provide some options.
> 
> Otherwise, everyone gets the same Wine 7.10 build we provide because out 8.4 one had some issues for certain plugins. And we still use DXVK 1.10 for compatibility reasons, but DXVK 2.0 and later offer benefits for supported GPUs/Vulkan implementations
  
[source](https://discord.com/channels/581875019861328007/850387047927250944/1174106570418827414)

## Install options

### Debian-based

(need to get links)

- XIVLauncher flatpak (this is what you probably have)
- XIVLauncher PPA (Binary release without flatpak runtimes)
- XIVLauncher MPR build (like the AUR, but for Debian family. Builds from source)

### Arch-based

- XIVLauncher flatpak
- XIVLauncher AUR build
