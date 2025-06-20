# About

This repository contains cover art to be used with [Retro-Go](https://github.com/ducalex/retro-go).

Download this repository and place its content in the romart folder on your sd card.


# Format

The preferred format is paletted PNG with dimensions of 160x160. Dimensions may vary but try to be consistent in any given system.


# Naming

File names are 8 digit uppercase hexadecimal numbers used as unique game identifiers.
See table below to learn how they are calculated.

| System | Folder | Algorithm |
|--------|--------|-----------|
| Colecovision | col | CRC32 of the entire game rom |
| DOOM | doom | Name of the WAD file |
| Gameboy | gb | CRC32 of the entire game rom |
| Gameboy Color | gbc | CRC32 of the entire game rom |
| Gamegear | gg | CRC32 of the entire game rom |
| Game & Watch | gw | CRC32 of the entire game rom |
| Lynx | lnx | CRC32 of the entire game rom excluding the first 64 bytes |
| MSX | msx | CRC32 of the entire game rom |
| NES | nes | CRC32 of the entire game rom excluding the first 16 bytes |
| PC-Engine | pce | CRC32 of the entire game rom |
| Sega Master System | sms | CRC32 of the entire game rom |
| Sega Megadrive | md | CRC32 of the entire game rom |
| SNES | snes | CRC32 of the entire game rom |
