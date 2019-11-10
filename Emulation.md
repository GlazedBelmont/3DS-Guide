### Emulation
There is two usable emulators, Citra is 5 years old and works well, while Corgi3DS is a few months old and not so well.
Citra is a HLE (high level emulation) that emulates the k11 of the Nintendo 3DS, allowing for userland programs to run on PC, while Corgi3DS, a LLE (low level emulation) 3DS emulator (emulates both k11 and k9), that should only be used for testing Firms or other low level things

### Prerequisites 
- Have Internet on PC
- If on Linux, have flatpak installed
- Corgi3DS requires Qt5 and GMP installed

### Citra Instructions

#### Windows
1. Go [here](https://citra-emu.org/download/) and setup the .exe, now open GodMode9 on the 3DS and go HOME -> Scripts... -> GM9MegaScript -> Dump Options -> Dump CITRA files
2. Put SD in PC and Copy SD:/gm9/out/Citra/user to the Citra user folder

#### Linux
1. flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo
2. add either the nightly or the canary
  - flatpak install https://flatpak.citra-emu.org/citra-nightly.flatpakref
  - flatpak install https://flatpak.citra-emu.org/citra-canary.flatpakref

### Corgi3DS Instructions

#### Windows
Must be compiled on a Unix system, sorry Windows users

#### Unix
- git clone --recursive https://github.com/PSI-Rockin/Corgi3DS.git
- cd Corgi3DS
- qmake
- make
