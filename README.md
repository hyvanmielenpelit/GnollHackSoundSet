# GnollHack Sound Set

GnollHack FMOD project file and assets.

## Building Sound Banks

1. Clone GnollHackSoundSet repository.
2. Install [FMOD Studio](https://www.fmod.com/) **2.02.15**. *(Please use this exact version.)*
3. Open **GnollHackSoundset.fspro** project in the main directory of the GnollHackSoundSet repository using **FMOD Studio**.
4. Select **File → Build All Platforms...**
5. Built sound banks will appear in the `Build` directory of the GnollHackSoundSet repository.

There are two flavors of sound banks: **desktop** and **mobile**. They will be in their respective subdirectories `Desktop` and `Mobile` under the `Build` directory. There are 6 sound banks in each directory:

- Master.bank
- Master.strings.bank
- Intro.bank
- Auxiliary.bank
- Music.bank
- Preliminary.bank

The **desktop banks** are meant for the **desktop version** of GnollHack (Windows) and the **mobile banks** are meant for the **Android and iOS versions** of the game.

## Copying Sound Banks to GnollHack Repository

 After building the banks, you should copy them to the `win\win32\bank` directory of the [GnollHack](https://github.com/hyvanmielenpelit/GnollHack) repository so that on the first level are `Desktop` and `Mobile` subdirectories.

