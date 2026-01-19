# C3 Showcase

This repository keeps a list of various C3 resources and projects.

*NOTE* these are all in various levels of completion, from actively supported to just started or abandoned. The "bumped" date,
shows when this was last added or bumped. Consider this a "last updated" date.

If you have something you feel could be interesting to share with the rest of the community, do file a pull request!

***NOTE: These projects and resources are not officially endorsed by the C3 Project.***

### Learning resources

📖 [Ebn's C3 tutorials](https://ebn.codeberg.page/programming/c3/) - from Hello World to setting up OpenGL *[bumped 2025-04-17]*

### Tooling

🔨 [Bash completion script for c3c](https://github.com/BWindey/c3c-bash-completions/) - tab completions for the c3c command for bash (open for contributions for other platforms: zsh, fish, ...)

🔨 (WIP)[Fish completion script for c3c](https://github.com/fgsoftware1/c3-fish-completions) - tab completions for the c3c command for fish

🔨 [c3c version manager](https://github.com/BWindey/c3vm) - version manager for c3c written in bash, might get replaced by a more platform-independent solution some day

🔨 [c3fmt](https://github.com/lmichaudel/c3fmt) - code formatter for C3 *[bumped 2026-01-17]*

🔨 [c3build](https://github.com/lyranie/c3-build-file) - cmake-like buildscript

### Libraries

📁 [BC3 bindings generator library](https://github.com/vssukharev/bc3) - library to create bindings for C code to C3 *[bumped 2025-04-17]*

📁 [Minimal Argument Parser](https://github.com/lyranie/c3-argparser) - Minimal argument parser library for C3 *[bumped 2025-05-04]*

📁 [argparse](https://github.com/joshring/argparse) - Another, more full fledged argument parser library for C3 *[bumped 2025-04-26]*

📁 [getopt-style args parser](https://github.com/NotsoanoNimus/getopt.c3l) - Yet another args parser centered around GNU `getopt` with extras inspired by D-lang *[bumped 2025-07-25]*

📁 [Vulkan-C3](https://github.com/hucancode/vulkan-c3) - library that add vulkan support to C3 *[bumped 2025-11-06]*

📁 [Minimal Logger](https://github.com/lyranie/c3-logger) - A minimal logger library for C3 *[bumped 2025-04-19]*

📁 [json library](https://github.com/hwchen/json-c3) - json library for C3 *[bumped 2025-06-27]*

📁 [I18n library](https://github.com/tahadostifam/i18n-c3) - I18n library for C3 *[bumped 2025-04-28]*

📁 [TOML parser](https://github.com/konimarti/toml.c3l) - TOML config parser for C3 *[bumped 2025-08-06]*

📁 [xlsx Writer](https://github.com/radekm/xlsx-writer) - A C3 library for writing XLSX files in a streaming fashion *[bumped 2025-10-04]*

📁 [XML parser](https://github.com/tonis2/xml.c3) - XML parser for C3 *[bumped 2025-04-29]*

📁 [Inflate](https://github.com/konimarti/tinf.c3l) - C3 Inflate library (inflate, gzip, zlib) *[bumped 2025-04-29]*

📁 [AES](https://github.com/konimarti/aes.c3l) - AES implementation for C3 *[bumped 2025-04-29]*

📁 [HTTP Client](https://github.com/tclesius/http.c3) - HTTP Client Library *[bumped 2025-04-29]*

📁 [HTTP Server](https://github.com/velikoss/c3-api) - Simple C3 HTTP Server with routing *[bumped 2025-04-29]*

📁 [UEFI tools](https://github.com/NotsoanoNimus/uefi.c3l) - UEFI Definitions & Library for C3 *[bumped 2025-06-23]*

📁 [Assuan protocol](https://github.com/konimarti/assuan.c3l) - C3 implementation of the Assuan IPC protocol. *[bumped 2025-04-30]*

📁 [Tagged Unions](https://github.com/Book-reader/tagged_unions.c3l) - A simple library for mostly safe tagged unions *[bumped 2025-06-22]*

📁 [ChaCha20-Poly1305](https://github.com/NotsoanoNimus/chacha20_aead.c3l) - Zero-dependency crypto library for ChaCha20, Poly1305, and their combination. *[bumped 2025-06-23]*

📁 [PEM format](https://github.com/konimarti/pem.c3l) - PEM file format encoding and decoding *[bumped 2025-08-06]*

📁 [Zip Archives](https://github.com/konimarti/zip.c3l) - Read and write Zip archives (Zip64 format also supported) *[bumped 2025-08-17]*

📁 [LRU/LFU Caches](https://github.com/konimarti/cache.c3l) - LRU/LFU Cache implementations *[bumped 2025-08-18]*

📁 [libmpv.c3l](https://github.com/Book-reader/libmpv.c3l) - libmpv bindings for C3 *[bumped 2025-08-06]*

📁 [Const Map](https://github.com/Book-reader/const_map.c3l) - Compile-time constant hashmaps *[bumped 2025-08-17]*

📁 [Closures](https://github.com/Book-reader/closures.c3l) - Explicitly capturing function-pointer closures in C3 *[bumped 2025-08-28]*

📁 [Regexp9](https://github.com/konimarti/regexp9.c3l) - Thompson NFA regex engine with submatches ported from Plan9 *[bumped 2025-09-17]*

📁 [ECS](https://codeberg.org/m0tholith/c3-ecs) - Entity-Component-System module written in C3 *[bumped 2025-11-14]*

📁 [VT100 Parser](https://github.com/konimarti/vt100.c3l) - VT100 Parser for escape and control sequences (DEC/ANSI-compatible) *[bumped 2025-09-29]*

📁 [B-tree](https://github.com/radekm/btree) - B-tree that can serve as a map or set *[bumped 2025-10-04]*

📁 [sokol-c3](https://github.com/floooh/sokol-c3) - Auto-generated C3 bindings for the sokol headers *[bumped 2025-10-04]*

📁 [imgui-c3](https://github.com/radekm/imgui-c3) - Bindings for Dear ImGui, ImPlot and ImGuiFileDialog with sokol backend *[bumped 2025-09-25]*

📁 [Kotlin bindings](https://github.com/rtc11/c3kt) - call C3 from kotlin (dynamic libs) *[bumped 2025-10-10]*

📁 [C3 lexer](https://github.com/konimarti/lexer.c3l) - C3 lexer with contract and comment support, validated against the C3 standard library and all unit tests *[bumped 2025-12-24]*

📁 [Wren C3 bindings](https://github.com/konimarti/wren.c3l) - C3 bindings for the Wren scripting language (no external dependencies) *[bumped 2026-01-02]*

📁 [SoA - StructureOfArrays](https://github.com/nyr24/c3_soa_lib) - C3 library for operating on SoA (Structure Of Arrays) (no external dependencies) *[bumped 2026-01-20]*

### Applications

⭐ [Sam J Kennedy's Gameboy emulator](https://github.com/samjkennedy/gbc3) - a GameBoy emulator written in C3 *[bumped 2025-04-17]*

⭐ [fox33](https://github.com/Book-reader/fox33) - a fox32 emulator written in C3 *[bumped 2025-06-15]*

⭐ [mplay](https://github.com/Book-reader/mplay_c3) - a simple cli music player written in C3 using libmpv *[bumped 2025-08-06]*

⭐ [pwm](https://github.com/iwnlcern/pwm) - a simple cli password manager written in C3 with sqlcipher databases.

⭐ [OpenPNGStudio](https://github.com/openpngstudio) - create & stream PNGTuber models.

### Games

👾 [Boing](https://github.com/tekin-tontu/boing) - BOING (pong) port of python game to C3 *[bumped 2025-04-22]*

⭐ [Armadillo Madness](https://github.com/Ronin15/Armadillo_Madness_C3) - A complete 2D casual side scroller arcade style game written for my daughter about an Armadillo shooting poop at bad guys.

### Advent of Code solutions

🎅 [CLernö AoC 2022](https://github.com/lerno/aoc_2022_c3) - Complete solution to AoC 2022 *[bumped 2025-04-27]*

🎅 [CLernö AoC 2023](https://github.com/lerno/aoc_2023_c3) - Complete solution to AoC 2023 *[bumped 2025-04-27]*

🎅 [CLernö AoC 2024](https://github.com/lerno/aoc_2024_c3) - Solutions to AoC 2024 day 1-19 *[bumped 2025-04-27]*

### Other

🔤 [lucy](https://github.com/lucy-language/lucy) - a compiler for the lucy language written in c3 *[bumped 2025-06-25]*

🔤 [modulang](https://github.com/cubedium/modulang) - a (sort of) modular esolang made in c3 *[bumped 2025-06-28]*

🔤 [readline-fzf-hook.c3](https://github.com/shaobosong/readline-fzf-hook.c3) - Enhanced Readline with fzf-powered hooks. *[bumped 2025-07-10]*

🔤 [muon-kernel](https://github.com/rickyadastra/muon-kernel) - A minimalist x86-64 microkernel written in C3 *[bumped 2025-12-04]*

## Contribute!

Feel free to add pull requests to this repository to either bump a project that you know is active, or add more projects.
