# RetroArch-Settings

**Dolphin:**

User: saves/dolphin-emu/User

Sys: system/dolphin-emu/Sys

## Load SDCard:

**RSBE01 - GameSettings**

Rex Zero Half Mod: https://youtu.be/xkctlNo5YlM

ID-REX Offline Launcher.ini

[Core]

DefaultISO = ./assets/Games/Super Smash Bros. Brawl (USA) (Rev 2).rvz

WiiSDCard = True

WiiSDCardAllowWrites = True/False

**Dolphin.ini**

[General]

Dump Path = ./saves/dolphin-emu/User/Dump

Load Path = ./saves/dolphin-emu/User/Load

NANDRootPath = ./saves/dolphin-emu/User/Wii

WiiSDCardPath = ./saves/dolphin-emu/User/Wii/sd.raw

## Winlauncher:

dll: cores

info: info

Core: https://drive.google.com/drive/folders/11Oi0AX1HNDfmyfgICRupL-1TlCAA1E-5?usp=drive_link

## Riivolution

Use Standalone Dolphin to create a json file to load a Riivolution mod

**XML**

Tutorial: https://gamebanana.com/tuts/14789

**Json Example**

{
  "base-file": ".assets/Games/game.rvz",
  "display-name": "Riivolution-RetroArch-Example",
  "riivolution": {
    "patches": [
      {
        "options": [
          {
            "choice": 1,
            "option-name": "\\/Mod Option",
            "section-name": "Mod Test"
          }
        ],
        "root": "./saves/dolphin-emu/User/Load/Riivolution",
        "xml": "./saves/dolphin-emu/User/Load/Riivolution/(folder)/test.xml"
      }
    ]
  },
  "type": "dolphin-game-mod-descriptor",
  "version": 1
}
