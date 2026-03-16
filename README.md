# Polaris_TKDataModLoader
_We manage the source code in a private repository because we do not want this to be exploited for cheating._
_So, this repository is simply for updating releases and game addresses._

## Introduction
This is a mod loader designed to mod the tkdata.bin file located at the following path in TEKKEN 8:
TEKKEN 8\Polaris\Content\Binary\pak\tkdata.bin

This file contains a large amount of data that cannot be modified through regular Unreal Engine modding.
It includes very important data such as character movesets, the character list, and the list of customization items. We created this tool in order to make modding this data possible.

Extracting the entire contents of tkdata.bin and repackaging it again is a very heavy and unstable process. With this tool, only the modified files can be injected at runtime.
Currently, only moveset data can be injected, and there are still many things we need to discover and research.

We will try to prepare more documentation and tutorials as soon as possible.



## Requirements
[Ultimate ASI Loader](https://github.com/ThirteenAG/Ultimate-ASI-Loader/releases)

## Installation
After extracting, place the asi and PolarisTkdataModLoader folders in the following path:
TEKKEN 8\Polaris\Binaries\Win64

## How to use
Press Ctrl + P to display the overlay menu.

## Project support
Do you have sufficient knowledge of binary files and reverse engineering?
If so, please come to our Discord server and help us!

[Modding Zaibatsu Discord](https://discord.gg/nCAeJE4z5U)
