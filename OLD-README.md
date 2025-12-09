# crackme collection

bunch of crackmes i cook up to get better at coding and reverse engineering. still fresh rn so not much inside yet.

## whats this

i mess with game security a lot. wanted my own crackmes cuz i can tune the pain level and check my work. c++ output is messy as fuck so its good practice. this is basically my playground to break my own stuff and see where i fucked up.

## about me

game dev into cheats, re, anti cheat shit. wanna end up doing game pentesting and anti cheat work. this repo is my gym.

## structure

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

each one has builds for x32 x64 etc with their own readmes.

## build variations

u might see:
- different opt levels O0 to O3
- debug or release
- stripped or not
- x86 x64 arm whatever
- gcc clang msvc

## challenge types

stuff will range from:
- basic password checks
- license key logic
- anti debug tricks
- anti tamper shit
- obfuscation
- tiny vm stuff
- packers
- game specific cheat detection patterns

## getting started

pick one  
read its readme  
open it in whatever tools u like ghidra ida x64dbg etc  
try solve it blind  
check source after to see what u missed

## tools i use

- disasm: ida ghidra binary ninja  
- debuggers: x64dbg gdb windbg  
- decompilers: hex rays ghidra dec  
- misc: die strings objdump pe explorer

## learning stuff

good places:
- yurichev reverse engineering for beginners  
- opensecuritytraining  
- malware unicorn re101  
- nightmare intro to binexp

## contributing

if u see broken binaries or wanna drop ideas or writeups cool. just dont spoil shit without warning.

## disclaimer

this is for learning. dont use this crap to go break legit software.

## license

mit. go wild for edu stuff.
