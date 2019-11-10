### devkitARM & libctru
devkitARM and libctru are tools used for developing 3DS homebrew in C/C++, the installation of these tools varies depending on your OS.

### Prerequisites
- Know C/C++

### What you need
- On Windows, you need the [graphical installer](https://github.com/devkitPro/installer/releases/tag/v3.0.3), on Linux/Mac OS, there's the terminal

### Instructions
- Windows
  - Open the graphical installer, and follow it's instructions
- Unix
  - Follow the instructions [here](https://github.com/devkitPro/pacman/releases/tag/devkitpro-pacman-1.0.1) to install dkp-pacman
  - In the terminal, enter (dkp-)pacman -S 3ds-dev (it's either dkp-pacman, or pacman depending on your OS)
  - Type in (dkp-)pacman -Sl | grep devkit-env to make sure devkitpro is installed
  - Reboot PC
 
