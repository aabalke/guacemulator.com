---
layout: "quesolayout"
---

# {{<quesologo>}} queso: an arm32 disassembler

Prioritizing historical accuracy for emulation and retro computing, I originally wrote queso to help debug [guac 🥑, my console emulator](https://guacemulator.com/). It allows for different arm32 versions, and when compared to binutils objdump and other disassemblers, tries to be historically accurate on older arm32 versions. 100% client side. Available as a [cli tool, and vendorable in golang and c as well](https://github.com/aabalke/queso).

{{< queso>}}
