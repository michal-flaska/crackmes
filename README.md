# CrackMe Collection

A personal collection of reverse engineering challenges (crackmes) that I create to improve both my programming and reverse engineering skills.

> [!IMPORTANT]
> 🚧 Project just started - challenges coming soon!

> [!NOTE]
> If you're looking for the non-ai-generated version of the readme, you can find it [here](./OLD-README.md)

## About This Project?

I've always been passionate about reverse engineering, particularly in the context of game security. While there are plenty of existing crackmes out there, I decided to create my own for several reasons:

- **Dual Learning**: By creating crackmes, I learn both coding and reverse engineering simultaneously
- **Controlled Difficulty**: I can gradually increase complexity as I improve
- **Verification**: Knowing the source code allows me to verify my reverse engineering work and understand where I went wrong
- **Messy Reality**: Especially with C++, the compiled output is messy and realistic, providing genuine RE practice with name mangling, vtables, optimizations, and more

This approach gives me the "answer key" while still providing challenging practice, similar to solving math problems with solutions available for checking your work.

## About Me

I'm a game developer with a strong interest in game security, specifically game cheats and reverse engineering. My goal is to work as a game penetration tester and anti-cheat developer in the future. This project serves as a practical training ground for building both offensive and defensive security skills in game development contexts.

## Project Structure

```
crackmes/
├── README.md
├── LICENSE
├── ...
│
├── cpp/
│   ├── crackme01
│   │   ├── x32/
│   │   │   ├── src/
│   │   │   ├── build/
│   │   │   └── README.md
│   │   │
│   │   └── x64/
│   │       └── ...
│   └── ...
│
├── c/
│   └── ...
│
├── rust/
│   └── ...
│
├── go/
│   └── ...
│
└── mixed/
    └── ...
```

- **Language Folders**: Organized by programming language (C++, C, Rust, Go, etc.)

### Build Variations

Each crackme may include multiple builds:
- Different optimization levels (-O0, -O1, -O2, -O3)
- Debug vs Release builds
- Stripped vs unstripped symbols
- Different architectures (x86, x64, ARM, etc.)
- Different compilers (GCC, Clang, MSVC)

## Challenge Categories

Challenges will cover various topics relevant to software security:
- Basic password/serial validation
- License key verification systems
- Anti-debugging techniques
- Anti-tampering mechanisms
- Code obfuscation
- Virtual machines
- Packing/unpacking
- Games will have game-specific patterns (cheat detection, integrity checks)

## Getting Started

1. Choose a challenge from the appropriate difficulty level
2. Read the challenge's README for objectives
3. Use your favorite reverse engineering tools (IDA, Ghidra, x64dbg, Binary Ninja, etc.)
4. Try to solve it without looking at the source!
5. Check your solution against the source code afterward

## Tools I Use

- **Disassemblers**: IDA Pro, Ghidra, Binary Ninja
- **Debuggers**: x64dbg, GDB, WinDbg
- **Decompilers**: Hex-Rays, Ghidra Decompiler
- **Other**: PE Explorer, Detect It Easy, strings, objdump

## Learning Resources

If you're also learning reverse engineering, here are some resources I find helpful:
- [Reverse Engineering for Beginners](https://beginners.re/) by Dennis Yurichev
- [OpenSecurityTraining](https://opensecuritytraining.info/)
- [Malware Unicorn's Reverse Engineering 101](https://malwareunicorn.org/workshops/re101.html)
- [Nightmare - Intro to Binary Exploitation](https://guyinatuxedo.github.io/)

## Contributing

While this is primarily a personal learning project, I welcome:
- Bug reports if binaries don't work as intended
- Suggestions for challenge ideas
- Writeups of your solutions (spoiler tag them!)
- Improvements to existing challenges

## Disclaimer

These crackmes are created purely for educational purposes to learn reverse engineering and software security. Do not use techniques learned here for malicious purposes or to circumvent legitimate software protections.

## License

This project is open source and available under the MIT License. Feel free to use these challenges for learning and educational purposes.
