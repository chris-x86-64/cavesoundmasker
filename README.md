# Cave Sound Remover

A resource pack designed to remove the spooky cave noises from Minecraft 1.12.2.

## Usage

Just clone this into your resourcepack directory to test it out.
No packaged releases available yet.

## Supported Minecraft versions

I've only tested it on 1.12.2 but the same principle should work on later versions as well.
There are other resource packs with the exact same purpose readily available on CurseForge. I made this myself because I wanted the one made for 1.12.2.

## How it's made

I besically followed [the tutorial](https://minecraft.fandom.com/wiki/Tutorials/Creating_a_resource_pack).

1. I generated an ogg audio consisting of 1 second of silence using Audacity (Material not subject to copyright)
1. I duplicated the file and batch-numbered them from `cave1.ogg` to `cave18.ogg`, then placed in the directory `assets/minecraft/sounds/ambient/cave` to override the vanilla oggs.
1. That's basically it!
