---
weight: 1
---

# Getting Started

## Installation

The latest release is available as pre-compiled binaries on [github](https://github.com/aabalke/guac/releases).
Binaries are available for Windows x86/ARM, Linux x86/ARM, and Mac ARM.

## Building

Building from source is possible with go version >= 1.26, using:

```
go build .
```

### Debian / Ubuntu / Raspberry Pi

For building on Debian systems the following packages must be installed:
```
sudo apt install libx11-dev libxrandr-dev libxcursor-dev libxinerama-dev libxi-dev libasound2-plugins libgtk-3-dev pkg-config
```

On Ubuntu these packages should come installed; however, on Raspberry Pi OS these packages will not come pre-installed.
