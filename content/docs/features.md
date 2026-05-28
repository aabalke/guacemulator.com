---
weight: 2
---

# Features

## Emulation out of the box 

guac does not require any bios or firmware files (but you can provide!), just
the roms you are interested in using. It also has full controller support even
in menus, with on screen keyboards.

## Jit Compiler

Nintendo DS emulation on guac comes with a one-of-a-kind jit compiler. This
allows cpu emulation to be 2-5x faster depending on workloads. This is the first
jit compiler that can interop with (more like confuse) the golang runtime to
allow calls to go functions from jit code. Additionally, this is the first arm64
jit compiler written in golang. For more information please see [aabalke/gojit](https://github.com/aabalke/gojit/).

## Customizable

guac comes with a TON of customizable options. The ui has customizable colors, hotkeys, and localization in english or spanish. All consoles have customizable
inputs. Nintendo DS has customizable screen layouts, Real-Time Clock, and Firmware.

## 3D Export

guac comes with a 3D Scene Export, allowing the current 3d scene to be exported 
as a .obj file. This allow the 3D scene to be imported into 3D software such as
Blender, Maya etc for debugging, artistic expression and more.
