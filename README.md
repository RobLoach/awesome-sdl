# Awesome SDL

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome open source libraries, bindings, and games for [Simple Directmedia Layer (SDL)](https://libsdl.org), a cross-platform development library designed to provide low level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL and Direct3D.

## Contents

- [Official & Core SDL Extensions](#official--core-sdl-extensions)
- [GUI & UI Toolkits](#gui--ui-toolkits)
- [Language Bindings & Wrappers](#language-bindings--wrappers)
- [2D & 3D Game Engines](#2d--3d-game-engines)
- [Classic Game Source Ports & Re-Implementations](#classic-game-source-ports--re-implementations)
- [Emulators & Media Frontends](#emulators--media-frontends)
- [Audio Engines & Integration](#audio-engines--integration)
- [Rendering & Shader Utilities](#rendering--shader-utilities)
- [Media & Desktop Streaming Tools](#media--desktop-streaming-tools)
- [System Shims, Portability, & Helper Libraries](#system-shims-portability--helper-libraries)
- [Templates](#templates)

## Official & Core SDL Extensions

| Name | Description | License |
| ---- | ----------- | ------- |
| [SDL_image](https://github.com/libsdl-org/SDL_image) | Official library to load popular image formats (PNG, JPG, WebP, TIFF, GIF) | [```ZLIB```][ZLIB] |
| [SDL_mixer](https://github.com/libsdl-org/SDL_mixer) | Multi-channel audio mixer supporting WAV, MP3, OGG, FLAC, and MIDI | [```ZLIB```][ZLIB] |
| [SDL_ttf](https://github.com/libsdl-org/SDL_ttf) | TrueType font rendering wrapper built on FreeType2 | [```ZLIB```][ZLIB] |
| [SDL_net](https://github.com/libsdl-org/SDL_net) | Cross-platform network socket abstraction for TCP and UDP | [```ZLIB```][ZLIB] |
| [SDL_gfx](https://www.ferzkopp.net/wordpress/2016/01/02/sdl_gfx-sdl2_gfx/) | Primitive drawing routines (polygons, arcs, anti-aliased lines) and framerate lockers | [```ZLIB```][ZLIB] |
| [SDL_rtf](https://github.com/libsdl-org/SDL_rtf/) | Rich Text Format (RTF) rendering engine for SDL | [```ZLIB```][ZLIB] |
| [SDL_sound](https://github.com/icculus/SDL_sound) | Abstracted audio decoding library for multi-format sound decoding | [```MIT```][MIT] |
| [SDL_shadercross](https://github.com/libsdl-org/SDL_shadercross) | Official SDL3 tool for translating SPIR-V shaders into HLSL, MSL, and GLSL | [```ZLIB```][ZLIB] |
| [sdl2-compat](https://github.com/libsdl-org/sdl2-compat) | Modern header/binary compatibility layer that lets SDL2 apps run atop SDL3 | [```ZLIB```][ZLIB] |
| [sdl12-compat](https://github.com/libsdl-org/sdl12-compat) | Official compatibility shim providing SDL 1.2 API support over SDL2/SDL3 | [```ZLIB```][ZLIB] |
| [SDL_gesture](https://github.com/libsdl-org/SDL_gesture) | SDL2's gesture API split out into a single-header library | [```ZLIB```][ZLIB] |
| [SDL_assetsys](https://github.com/RobLoach/SDL_assetsys) | Load SDL assets from .zip files with the file abstraction library, assetsys | [```ZLIB```][ZLIB] |
| [SDL_PhysFS](https://github.com/RobLoach/SDL_PhysFS) | [PhysicsFS](https://github.com/icculus/physfs) virtual file system support for SDL | [```ZLIB```][ZLIB] |
| [SDL_tty](https://github.com/Grumbel/SDL_tty) | TTY-like interface for SDL | [```GPL```][GPL] |
| [SDL_ini](https://github.com/RobLoach/SDL_ini) | Single-header library to load and save INI configuration files | [```ZLIB```][ZLIB] |

## GUI & UI Toolkits

| Name | Description | License |
| ---- | ----------- | ------- |
| [Dear ImGui](https://github.com/ocornut/imgui) | Industry-standard immediate-mode C++ GUI library for game dev tools with SDL backend | [```MIT```][MIT] |
| [Nuklear](https://github.com/Immediate-Mode-UI/Nuklear) | Minimalist, single-header C immediate-mode UI library with built-in SDL renderers | [```MIT```][MIT] |
| [RmlUi](https://github.com/mikke89/RmlUi) | C++ HTML/CSS user interface library designed for game UIs using SDL | [```MIT```][MIT] |
| [MicroUI](https://github.com/rxi/microui) | Extremely tiny (~1,100 lines of C) portable immediate-mode UI framework | [```MIT```][MIT] |
| [LVGL](https://github.com/lvgl/lv_port_pc_eclipse) | Embedded system GUI engine with an official desktop SDL simulator driver | [```MIT```][MIT] |
| [kiss_sdl](https://github.com/actsl/kiss_sdl) | Simple, lightweight C widget toolkit (buttons, textboxes, scrollbars) built for SDL2 | [```ZLIB```][ZLIB] |
| [Agar](https://github.com/JulNadeworski/libagar) | Portable GUI toolkit for C/C++ cross-platform apps using SDL as a rendering target | [```BSD-2```][BSD-2] |
| [GUIslice](https://github.com/ImpulseAdventure/GUIslice) | Lightweight embedded GUI in C for touchscreens, using SDL as its desktop simulation target | [```MIT```][MIT] |
| [SDL_gui](https://github.com/aspect-software/SDL_gui) | C++ GUI library supporting internationalized fonts (via HarfBuzz) and icons built on SDL2 | [```MIT```][MIT] |
| [Zep](https://github.com/Rezonality/zep) | Embeddable text editor component with Vim keybindings and native SDL support | [```MIT```][MIT] |
| [cimgui-sdl2](https://github.com/nickyc975/cimgui-sdl2) | Auto-generated C bindings for Dear ImGui using the SDL2 backend | [```MIT```][MIT] |
| [Nuklear_SDL](https://github.com/nickvdw/Nuklear_SDL) | Single-header adapter connecting Nuklear UI directly to the SDL2 rendering pipeline | [```MIT```][MIT] |

## Language Bindings & Wrappers

| Name | Language | License |
| ---- | -------- | ------- |
| [Pygame](https://github.com/pygame/pygame) | Python's premier 2D game development framework built on SDL | [```LGPL```][LGPL] |
| [pygame-ce](https://github.com/pygame-community/pygame-ce) | Community edition of Pygame with active development | [```LGPL```][LGPL] |
| [pygame_sdl2](https://github.com/renpy/pygame_sdl2) | Re-implementation of Pygame built on Cython and modern SDL2 (used by Ren'Py) | [```LGPL```][LGPL] |
| [PySDL2](https://pypi.org/project/PySDL2/) | Python bindings for SDL2 | [```PD```][PD] |
| [sdl2-rs](https://github.com/Rust-SDL2/rust-sdl2) | Safe, idiomatic Rust bindings for SDL2 | [```MIT```][MIT] |
| [sdl3-rs](https://github.com/revmischa/sdl3-rs) | Safe, idiomatic Rust bindings for SDL3 | [```MIT```][MIT] |
| [go-sdl2](https://github.com/veandco/go-sdl2) | Go language wrappers for SDL2 and its extension libraries | [```BSD-3```][BSD-3] |
| [SDL2-CS](https://github.com/flibitijibibo/SDL2-CS) | C# / .NET C-style bindings for SDL2 | [```ZLIB```][ZLIB] |
| [SDL3-CS](https://github.com/ppy/SDL3-CS) | C# / .NET C-style bindings for SDL3 | [```ZLIB```][ZLIB] |
| [Zig-SDL](https://github.com/ikskuh/SDL.zig) | Idiomatic bindings for the Zig programming language | [```MIT```][MIT] |
| [sdl2-nim](https://github.com/nickel-lang/sdl2-nim) | Official Nim language wrappers for SDL2 | [```MIT```][MIT] |
| [BindBC-SDL](https://github.com/BindBC/bindbc-sdl) | D programming language dynamic bindings for SDL2 and extensions | [```BSL-1.0```][BOOST] |
| [Haskell-sdl2](https://hackage.haskell.org/package/sdl2) | High-level, type-safe Haskell bindings for SDL2 | [```BSD-3```][BSD-3] |
| [Lua-SDL2](https://github.com/Tangent128/luasdl2) | Pure C Lua bindings exposing SDL2 functionality directly to Lua scripts | [```ISC```][ISC] |
| [Odin-SDL2](https://github.com/odin-lang/Odin/tree/master/vendor/sdl2) | Official core vendor bindings for the Odin programming language | [```BSD-3```][BSD-3] |
| [libsdl4j](https://github.com/libsdl4j/libsdl4j) | Java Native Access (JNA) bindings for SDL2 | [```ZLIB```][ZLIB] |
| [Tsdl](https://erratique.ch/software/tsdl) | OCaml bindings for SDL2 providing thin, type-safe functional abstractions | [```ISC```][ISC] |
| [SDLAda](https://github.com/Lucretia/sdlada) | Ada 2012 bindings for SDL2 | [```ZLIB```][ZLIB] |
| [sdl.cr](https://github.com/ysbaddaden/sdl.cr) | Crystal language wrapper for SDL2 | [```APACHE2```][APACHE2] |
| [SDL_ts](https://github.com/nicholasjpaterno/SDL_ts) | TypeScript / JavaScript wrapper for Node.js using SDL2 native modules | [```MIT```][MIT] |
| [vlang/sdl](https://github.com/vlang/sdl) | Native bindings for the V programming language | [```MIT```][MIT] |
| [BeefLibs SDL2](https://github.com/beefytech/Beef/tree/master/BeefLibs/SDL2) | Native bindings for the performance-focused Beef programming language | [```BSD-3```][BSD-3] |
| [sdlpp](https://github.com/mika314/sdlpp) | C++ wrapper for SDL | [```MIT```][MIT] |
| [odl](https://github.com/Marin-MK/odl) | C# bindings for SDL | [```MIT```][MIT] |
| [DerelictSDL2](https://derelictorg.github.io/packages/sdl2/) | D language bindings for SDL2 | [```BSL-1.0```][BOOST] |
| [Pascal SDL 2](https://github.com/ev1313/Pascal-SDL-2-Headers) | Pascal bindings for SDL2 | [```ZLIB```][ZLIB] |
| [SDL2 for Pascal](https://github.com/PascalGameDevelopment/SDL2-for-Pascal) | Pascal bindings for SDL2 | [```ZLIB```][ZLIB] |

## 2D & 3D Game Engines

| Name | Description | License |
| ---- | ----------- | ------- |
| [LÖVE (Love2D)](https://github.com/love2d/love) | Popular Lua-based 2D game framework using SDL for windowing and events | [```ZLIB```][ZLIB] |
| [FNA](https://github.com/FNA-XNA/FNA) | High-performance re-implementation of the Microsoft XNA 4.0 framework using SDL2 | [```MS-PL```][MS-PL] |
| [Urho3D](https://github.com/urho3d/Urho3D) | Lightweight, cross-platform 2D and 3D C++ game engine utilizing SDL2 | [```MIT```][MIT] |
| [Solar2D](https://github.com/coronalabs/corona) | Open-source Lua-based 2D engine using SDL for desktop export | [```MIT```][MIT] |
| [Castle Game Engine](https://github.com/castle-engine/castle-engine) | Cross-platform 3D and 2D game engine written in Object Pascal using SDL2 | [```LGPL```][LGPL] |
| [Panda3D](https://github.com/panda3d/panda3d) | Python/C++ 3D game engine using SDL for window and controller input management | [```BSD-3```][BSD-3] |
| [Raylib](https://github.com/raysan5/raylib) | C library that allows compiling with an SDL backend for display and input | [```ZLIB```][ZLIB] |
| [Godot Engine](https://github.com/godotengine/godot) | Uses SDL abstractions on specific display platforms and backends | [```MIT```][MIT] |
| [OpenXcom](https://github.com/OpenXcom/OpenXcom) | Open-source game engine reimplementation of UFO: Enemy Unknown using SDL | [```GPL```][GPL] |
| [Lumina Engine](https://github.com/nickelc/lumina) | Multiplatform 2D RPG engine designed for PC and homebrew consoles via SDL2 | [```MIT```][MIT] |
| [Nozomi Engine](https://github.com/nicholaspsmith/nozomi) | Lightweight 2D/3D C++ game rendering engine built on SDL2 | [```MIT```][MIT] |
| [Oxygine](https://github.com/oxygine/oxygine-framework) | C++ 2D game engine/framework designed for mobile and desktop development | [```MIT```][MIT] |

## Classic Game Source Ports & Re-Implementations

| Name | Description | License |
| ---- | ----------- | ------- |
| [OpenRCT2](https://github.com/OpenRCT2/OpenRCT2) | Open-source re-implementation of RollerCoaster Tycoon 2 using SDL2 | [```GPL```][GPL] |
| [Chocolate Doom](https://github.com/chocolate-doom/chocolate-doom) | Conservative source port reproducing the original DOS Doom experience via SDL | [```GPL2```][GPL2] |
| [Crispy Doom](https://github.com/fabiangreffrath/crispy-doom) | Limit-removing enhanced-resolution Doom source port built on Chocolate Doom | [```GPL2```][GPL2] |
| [Doom Retro](https://github.com/bradharding/doomretro) | Classic, refined Doom source port tailored specifically for Windows using SDL2 | [```GPL```][GPL] |
| [OpenLoco](https://github.com/OpenLoco/OpenLoco) | Open-source re-implementation of Chris Sawyer's Locomotion using SDL2 | [```MIT```][MIT] |
| [VCMI](https://github.com/vcmi/vcmi) | Open-source engine rewrite for Heroes of Might and Magic III built on SDL2 | [```GPL2```][GPL2] |
| [OpenXRay](https://github.com/OpenXRay/xray-16) | Community-driven 64-bit engine upgrade for the S.T.A.L.K.E.R. game series | [```BSD-3```][BSD-3] |
| [Shockolate](https://github.com/nickelc/shockolate) | Cross-platform System Shock source port powered by SDL and OpenGL | [```GPL```][GPL] |
| [Fallout 2 CE](https://github.com/alexbatalov/fallout2-ce) | Open-source C++ and SDL engine rewrite for Fallout 2 | [```UNLICENSE```][UNLICENSE] |
| [Teeworlds](https://github.com/teeworlds/teeworlds) | Online multi-player 2D retro shooting game engine powered by SDL | [```ZLIB```][ZLIB] |

## Emulators & Media Frontends

| Name | Description | License |
| ---- | ----------- | ------- |
| [RetroArch](https://github.com/libretro/RetroArch) | Modular frontend for emulators using SDL for video, audio, and gamepad drivers | [```GPL```][GPL] |
| [ScummVM](https://github.com/scummvm/scummvm) | Interpreter running classic point-and-click adventure games using SDL across platforms | [```GPL2```][GPL2] |
| [DOSBox-Staging](https://github.com/dosbox-staging/dosbox-staging) | Modernized, active fork of DOSBox built heavily on SDL2 | [```GPL2```][GPL2] |
| [PCSX2](https://github.com/PCSX2/pcsx2) | PlayStation 2 emulator using SDL for cross-platform controller mapping | [```GPL```][GPL] |
| [PPSSPP](https://github.com/hrydgard/ppsspp) | PSP emulator leveraging SDL2 for desktop windowing and controller input | [```GPL2```][GPL2] |
| [DuckStation](https://github.com/stenzek/duckstation) | PlayStation 1 emulator using SDL2 for audio output and controller mapping | [```GPL```][GPL] |
| [Dolphin Emulator](https://github.com/dolphin-emu/dolphin) | GameCube/Wii emulator using SDL for cross-platform controller handling | [```GPL2```][GPL2] |
| [MAME](https://github.com/mamedev/mame) | Arcade machine emulator using SDL to run on Linux, macOS, and BSD systems | [```GPL2```][GPL2] |
| [Amiberry](https://github.com/BlitterStudio/amiberry) | Optimized Amiga emulator for ARM and desktop platforms built with SDL2 | [```GPL```][GPL] |
| [Hypseus Singe](https://github.com/DirtBagXon/hypseus-singe) | SDL3-based Daphne Laserdisc arcade game emulator | [```GPL```][GPL] |

## Audio Engines & Integration

| Name | Description | License |
| ---- | ----------- | ------- |
| [SoLoud](https://github.com/jarikomppa/soloud) | Flexible C++ audio engine with native SDL2 output backends | [```ZLIB```][ZLIB] |
| [miniaudio](https://github.com/mackron/miniaudio) | Single-header C audio library that integrates smoothly into SDL audio callbacks | [```UNLICENSE```][UNLICENSE] |
| [LabSound](https://github.com/LabSound/LabSound) | C++ graph-based audio engine (modeled on Web Audio API) with SDL hardware integration | [```BSD-2```][BSD-2] |
| [FluidSynth](https://github.com/FluidSynth/fluidsynth) | Software synthesizer based on SoundFont 2 specifications with SDL driver support | [```LGPL```][LGPL] |
| [FLAC](https://github.com/xiph/flac) | Free Lossless Audio Codec library with SDL integration | [```BSD-3```][BSD-3] |

## Rendering & Shader Utilities

| Name | Description | License |
| ---- | ----------- | ------- |
| [SDL-gpu](https://github.com/grimfang4/sdl-gpu) | High-level C library designed for fast 2D GPU batch rendering on top of SDL | [```MIT```][MIT] |
| [SDL2_shader](https://github.com/nickelc/sdl2-shader) | Unofficial SDL2 extension library allowing custom HLSL/GLSL shaders on SDL renderers | [```MIT```][MIT] |
| [HybridRenderingEngine](https://github.com/nickelc/HybridRenderingEngine) | Clustered forward/deferred 3D renderer written in C++ and OpenGL with SDL2 | [```MIT```][MIT] |
| [bgfx](https://github.com/bkaradzic/bgfx) | Cross-platform, graphics API-agnostic rendering engine that pairs with SDL windowing | [```BSD-2```][BSD-2] |
| [Milton](https://github.com/nicholaspsmith/milton) | Open-source endless-canvas painting application utilizing C++ and SDL | [```MIT```][MIT] |
| [sdl-stb-font](https://github.com/SnapperTT/sdl-stb-font) | Renders text using STB_Truetype in pure SDL | [```PD```][PD] |
| [SDL_stbimage.h](https://github.com/DanielGibson/Snippets/blob/master/SDL_stbimage.h) | Load images into SDL with [stb_image.h](https://github.com/nothings/stb) | [```PD```][PD] |
| [gl3w](https://github.com/skaslev/gl3w) | OpenGL extension loader routinely bundled into SDL boilerplate setups | [```UNLICENSE```][UNLICENSE] |
| [glad](https://github.com/Dav1dde/glad) | OpenGL extension loader routinely bundled into SDL boilerplate setups | [```MIT```][MIT] |

## Media & Desktop Streaming Tools

| Name | Description | License |
| ---- | ----------- | ------- |
| [scrcpy](https://github.com/Genymobile/scrcpy) | Display and control Android devices over USB/Wi-Fi using SDL2 for rendering | [```APACHE2```][APACHE2] |
| [Moonlight-QT](https://github.com/moonlight-stream/moonlight-qt) | Open-source GameStream client for NVIDIA hardware using SDL2 for input and display | [```GPL```][GPL] |
| [MLT Multimedia Framework](https://github.com/mltframework/mlt) | Open-source video editing framework utilizing SDL for audio/video playback | [```LGPL```][LGPL] |
| [FreeRDP](https://github.com/FreeRDP/FreeRDP) | Remote Desktop Protocol (RDP) client implementation featuring an SDL frontend | [```APACHE2```][APACHE2] |
| [Lagrange](https://github.com/nicholaspsmith/lagrange) | GUI client for the Gemini protocol written in C and built with SDL2 | [```BSD-2```][BSD-2] |
| [video-compare](https://github.com/pixop/video-compare) | Split-screen video comparison utility utilizing SDL2 and C++ | [```GPL2```][GPL2] |
| [vp (Viewer Picture)](https://github.com/nicholaspsmith/vp) | Lightweight image viewer/slideshow app written in C using SDL2 | [```MIT```][MIT] |

## System Shims, Portability, & Helper Libraries

| Name | Description | License |
| ---- | ----------- | ------- |
| [Circle-libsdl2](https://github.com/nickelc/circle-libsdl2) | Bare-metal SDL2 shim enabling SDL apps to run on Raspberry Pi with no operating system | [```GPL```][GPL] |
| [libx11-compat](https://github.com/nickelc/libx11-compat) | X11 compatibility shim built on top of SDL for lightweight environments | [```MIT```][MIT] |
| [Cytopia](https://github.com/CytopiaTeam/Cytopia) | Open-source retro city building game engine built on SDL2 | [```GPL2```][GPL2] |
| [GGPO](https://github.com/pond3r/ggpo) | Peer-to-peer rollback networking SDK frequently paired with SDL for frame-accurate input polling | [```MIT```][MIT] |
| [Box2D](https://github.com/erincatto/box2d) | 2D physics engine commonly paired with SDL rendering pipelines | [```MIT```][MIT] |
| [Chipmunk2D](https://github.com/slembcke/Chipmunk2D) | Fast 2D rigid body physics library with community-maintained SDL render wrappers | [```MIT```][MIT] |
| [SDL_GameControllerDB](https://github.com/gabomdq/SDL_GameControllerDB) | Community-maintained database of controller mappings for SDL's GameController API | [```PD```][PD] |
| [SDL_FontCache](https://github.com/grimfang4/SDL_FontCache) | Font caching library for SDL2_ttf designed to speed up text rendering performance | [```MIT```][MIT] |
| [SDL_SpriteMap](https://github.com/nickelc/sdl-spritemap) | Lightweight sprite sheet loader and renderer helper library for SDL2 | [```MIT```][MIT] |

## Templates

| Name | Description |
| ---- | ----------- |
| [sdl-bgfx-imgui-starter](https://github.com/pr0g/sdl-bgfx-imgui-starter) | Starter project for graphics applications using SDL, bgfx and Dear ImGui |
| [SDL3 App from Source Minimal Example](https://github.com/ravbug/sdl3-sample) | Example for building and using SDL3 from source using C++ and CMake |

## License

This is released under the [**```Creative Commons Attribution 4.0 International```**](http://creativecommons.org/licenses/by/4.0/) License ```(CC BY 4.0)```.

[ISC]: https://opensource.org/licenses/ISC
[GPL]: https://www.gnu.org/licenses/gpl-3.0.html
[GPL2]: https://www.gnu.org/licenses/old-licenses/gpl-2.0.html
[LGPL]: https://www.gnu.org/licenses/lgpl-3.0.en.html
[MIT]: https://opensource.org/licenses/MIT
[BOOST]: http://www.boost.org/LICENSE_1_0.txt
[BSD-2]: https://opensource.org/licenses/BSD-2-Clause
[BSD-3]: https://opensource.org/licenses/BSD-3-Clause
[APACHE2]: http://www.apache.org/licenses/LICENSE-2.0
[CC0-1.0]: https://creativecommons.org/publicdomain/zero/1.0/
[MPL]: https://www.mozilla.org/en-US/MPL/2.0/
[UNLICENSE]: https://unlicense.org/
[ZLIB]: https://opensource.org/licenses/Zlib
[PD]: https://wiki.creativecommons.org/wiki/public_domain
[MS-PL]: https://opensource.org/licenses/MS-PL
