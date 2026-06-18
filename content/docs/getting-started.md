---
weight: 1
---

# Getting Started

## Installation

The latest release is available as pre-compiled binaries on [github](https://github.com/aabalke/guac/releases).
Binaries are available for Windows amd64, and Linux amd64/arm64.

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

Audio drivers/hardware is a requirement for using guac, even if muted.
On Raspberry Pi and other systems you may need to adjust ALSA defaults.pcm.card and defaults.pcm.card settings if you receive error 524.
