<img src="https://raw.githubusercontent.com/umin135/Polaris_TKDataModLoader/refs/heads/main/readme-res/banner_Loader.png" /><br>
# Polaris_TKDataModLoader
_We manage the source code in a private repository because we do not want this to be exploited for cheating._<br>
_So, this repository is simply for updating releases and game addresses._

## Introduction
This is a mod loader designed to mod the tkdata.bin file located at the following path in TEKKEN 8:<br>
TEKKEN 8\Polaris\Content\Binary\pak\tkdata.bin

This file contains a large amount of data that cannot be modified through regular Unreal Engine modding.
It includes very important data such as character movesets, the character list, and the list of customization items. We created this tool in order to make modding this data possible.

Extracting the entire contents of tkdata.bin and repackaging it again is a very heavy and unstable process. With this tool, only the modified files can be injected at runtime.

We will try to prepare more documentation and tutorials as soon as possible.

## Features
- Custom moveset injection
- !!!WIP - Custom item slots injection

## Requirements
[Ultimate ASI Loader](https://github.com/umin135/Polaris_TKDataModLoader/blob/main/dinput8.dll)

## Installation
After extracting, place the asi file, dinput8.dll (see above) and PolarisTkdataModLoader folders in the following path:<br>
TEKKEN 8\Polaris\Binaries\Win64

## How to use
[English](https://github.com/umin135/Polaris_TKDataModLoader/blob/main/documents/en_001.md) [Korean](https://github.com/umin135/Polaris_TKDataModLoader/blob/main/documents/kr_001.md)

## Project support
Do you have sufficient knowledge of binary files and reverse engineering?<br>
If so, please come to our Discord server and help us!

[Modding Zaibatsu Discord](https://discord.gg/nCAeJE4z5U)

## Credits
UMIN - Tool development<br>
Ali - Game reversing<br>
dawc17 - Game reversing / Tool development<br><br>
