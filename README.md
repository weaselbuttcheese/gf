# TF2 patcher for full-colored decals

## Summary

This tool allows you to remove various restrictions when equipping cosmetic items.

In short, now you can equip any cosmetic items you'd like, even if they're conflicting!

This is a modification of [tf2patcher](https://github.com/default-username-was-already-taken/tf2patcher).


## Is it safe?

It is completely safe to use. However:

- Beware this software still patches TF2 memory. After the patching is done the program closes all open handles to TF2 (which is how VAC detects cheats). It is extremely unlikely this will be detected as it is not a cheat.

## How to use

1. Download the latest release [here](https://github.com/ill5-com/tf2-equip-region-patcher/releases/latest);

2. Run tf2patcher.exe and launch TF2

3. After the software says it's done, press any key to exit it, or click the X button.

3. Equip any items you'd like!


## Building from source

Run `make TARGET=32` or `make TARGET=64`, depending on which architecture you want to build for.

C11-aware compiler is required.


## Linux support?
Currently this project can only be built for Windows (both x86 and x86-64).

If you really need Linux binaries, create an issue and I'll take it from there.


## License

See UNLICENSE file.
