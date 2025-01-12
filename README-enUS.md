<p align="center">
<img width="800px" src="https://github.com/eddiecsilva/nixos-dotfilles/blob/main/project_nixos_thumb.png" align="center" alt="white" /><br><br>

<!-- (website for icons: https://shields.io/ ) -->

<img alt="Maintained" src="https://img.shields.io/badge/Maintained%3F-Yes-green">
<img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/eddiecsilva/nixos-dotfilles">
<img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/eddiecsilva/nixos-dotfilles">
<img alt="GitHub commit activity (branch)" src="https://img.shields.io/github/commit-activity/y/eddiecsilva/nixos-dotfilles">

</p>

# IMPORTANT NOTICES
By using this script you assume that you understand the risks and take full responsibility for your actions. All files that are part of this repository are freely distributed to be adapted. However, there is no implicit or explicit guarantee of its operation.

- When customizing the settings, only use spaces to adjust the paragraphs.
- All comments in English came from examples taken from the official NixOS documentation.
- You can customize partitioning using the hardware-configuration.nix file. However, the distro's official method recommends using the configuration.nix file for this.
- Remember to create a **user** and I suggest leaving **root** active with a strong password.
- BE CAREFUL when testing configurations, not all changes can be ignored when going to a previous generation.

## Objectives
These are my first tests with the NixOS parameterization file, the objective is to reproduce a result similar to my [FrankenDebian](https://github.com/eddiecsilva/debian-post-install) setup, however, using Nixos OS as a base.

The primary use of this setup is for video content creation, desktop publishing and vector art.

Hardware used
- Processor: AMD Ryzen 5700x
- GPU: Nvidia 3060ti Galax
- Motherboard: MSI MPG B550 Gaming Plus

---

# Active options in configuration.nix file
* Activation of non-free packages.
* Install proprietary Nvidia drivers (stable) + CUDA.
* Plasma 6 + Wayland graphical environment (with minimal apps).
* Distro's default kernel.
* Boot less verbose.
* Modeset active by default.
* Optimizations for AMD processors.
* Package update service on NixOS (without automatic boot).
*Bluetooth.

## Program installation*
* **Graphic tools:** Gimp, Inskcape, Shotcut.
* **Web browsers:** Google Chrome, Microsoft Edge, Firefox and Chromium.
* **Edition:** OBS Studio, Davinci Resolve Free, Onedrive, MPV, flameshot.
* **Extras:** fastfetch, aria2, fish, btop, vim, git.
* **Utilities:** onlyoffice-desktopeditors, obsidian, video-trimmer, warpinator, bottles, gparted.
* **KDE Apps:** kcalc, dragon, partitionmanager, plasma-browser-integration, kdeconnect-kde, kate.

## Recommendations
According to the official documentation, all customization must be done in the "configuration.nix" file, including options for boot parameters, services, installed packages, users and partitioning. Customizing the "hardware-configuration.nix" file is possible, but it may be overwritten by the system in some situations.

* /etc/nixos/configuration.nix - system configurations and packages being installed
* /etc/nixos/hardware-configuration.nix - optimizations for processors, partitions and boot

## Useful websites
- Official website of the NixOS project - [https://nixos.org/](https://nixos.org/)
- Package search tool - [https://search.nixos.org/packages](https://nixos.org/)
- Official Forum - [https://discourse.nixos.org/](https://nixos.org/)
- [Source of the logo art used on the cover](https://github.com/NixOS/nixos-artwork/issues/50)

---

## Future updates to this roadmap
* Enabled flatpak support.
* Adjustments for games.