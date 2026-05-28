---
weight: 4
params:
  bookFlatSection: true
---

# Configuration

guac uses a few different methods to configure and update settings. All 
configurable settings are loaded and saved in a "./config.toml" file available
in the root directory of guac. If a "./config.toml" file is not present, default
settings are used and a new config.toml file is created. If at any time you want
to return to the default config, just delete the config.toml file.

In addition to the config file, there are command line arguments and flags.
Command line arguments and flags always take precident over the config file values.
For example, if the config file requests target_fps=180, and the cli requrest -fps=60,
the emulator will run at 60 fps.

All configurable settings can be changed directly on the config file, and most can be changed from the settings ui.
