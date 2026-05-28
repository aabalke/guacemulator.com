---
weight: 1
params:
  bookFlatSection: true
---

# Command Line

The command line acts as an configuration override for some important settings.

## Rom Path (-r="...")

Rom Path (-r) will override the configuration file and immediately load a rom
without using the gui to choose a file. This should be a string value of a valid
path.

## Target Fps (-fps=...)

Target Fps (-fps) will override the configuration file and attempt to run the
emulator at the provided fps. This should be a valid positive integer.

## Show Fps (-show-fps)

Show Fps (-show-fps) will override the configuration file and display the
emulators actual fps and tps in the top right corner. This is a boolean value,
only provide it if you desire to show the fps.

## Mute (-m)

Mute (-m) will override the configuration file and mute all audio. This is a
boolean value, only provide it if you desire to mute the emulator.

## Profile (-p)

Profile (-p) will override the configuration file and run the profiler. This is a
boolean value, only provide it if you desire to run the profiler.

## Logger (-l)

Logger (-l) will override the configuration file and run the logger. This is a
boolean value, only provide it if you desire to run the logger.
