### Satawired-Emu

Primary Contributor: Claude, Satawired.

Sata Wired is an experimental Xbox Series X-focused emulator project written in C# and C++. Its long-term goal is to explore the possibility of running Windows-compatible games, with Grand Theft Auto VI (GTA VI) as a primary target.

The project is currently in very early development.

Status
An executable provided by an unknown contributor may serve as a reference for researching shader translation, GPU behavior, and other emulation-related components.

Please do not open issues requesting builds, release dates, ETAs, or download links, it will be provided when its fully done and user-friendly.

Current State
x86-64 guest code execution with native support.
High-level emulation (HLE) for most kernel and system libraries.
Vulkan-based renderer with an experimental shader recompiler. Many opcodes still rely on slower fallback paths.
PFS filesystem mounting and basic save-data support.
Working audio output, with occasional underruns.
No online functionality. Network-related calls are currently stubbed.
Known Issues
Stuttering during shader compilation.
GPU hangs on certain draw calls.
High memory consumption.
Incomplete shader instruction support.
Occasional audio underruns.
Requirements (For Testing)
Windows 10 or Windows 11 (64-bit).
GPU supporting Vulkan 1.3 or later.
At least 16 GB of RAM.

These requirements are preliminary and may change as development progresses.

Legal

Sata Wired does not include, distribute, or provide any firmware, encryption keys, or game files.

Users are responsible for obtaining and dumping their own console firmware and game files.

Sata Wired is an independent experimental project and is not affiliated with, endorsed by, or associated with Microsoft, Xbox, Rockstar Games, or Take-Two Interactive.

All trademarks and copyrights belong to their respective owners.

This project is experimental and is not intended for everyday use. Features, compatibility, and requirements are subject to change.
