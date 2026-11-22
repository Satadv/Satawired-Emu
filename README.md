# Satawired-Emu
Experimental PS5 emulator for Windows. Early development, not publicly released.

-
Sata Wired is an experimental PlayStation 5 emulator for Windows, written in C# and C++.

It is in very early development. Some titles reach the menus or get partway into
gameplay, but nothing is playable yet and crashes are expected.

## Status

There are no public builds, and the source is not available at the moment.
I don't plan to release anything to the public for now. If that changes, it will be posted here.

Please don't open issues asking for builds, ETAs or download links.

## Current state

- x86-64 guest code runs natively, with HLE for most kernel and system libraries
- Vulkan renderer with a shader recompiler (many opcodes still use slow paths)
- PFS mounting and basic save data
- Audio output works, with occasional underruns
- No online features (network calls are stubbed)

Known issues: shader compilation stutter, GPU hangs on some draw calls, and high memory use.

## Requirements (for testing)

- Windows 10/11 x64
- A GPU with Vulkan 1.3 support
- 16 GB RAM

## Legal

Sata Wired does not include any firmware, keys or game files, and none will be provided.
You need to dump your own console and games. This project is not affiliated with
or endorsed by Sony Interactive Entertainment.
