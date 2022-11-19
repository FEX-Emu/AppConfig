# Additional application configuration files for FEX-Emu
## Quick start
- Clone this repository and copy the `AppConfig` folder in to the appropriate location.
  - `git clone https://github.com/FEX-Emu/AppConfig.git`

- Config directory can be one of the following folders
  - `$HOME/.fex-emu/`
    - For local install
  - `$XDG_DATA_HOME/.fex-emu/`
    - If using XDG
  - `/usr/share/fex-emu/`
    - For global install

## Documentation
Any game added to the repository should have reflected documentation on the [FEX-Emu wiki](https://wiki.fex-emu.com/index.php/Main_Page)

The wiki page should be created first before a PR is created.

## Required testing
### If enabling thunks in a configuration
- The thunk **MUST** have been tested on an AArch64 board running FEX. Due to behaviour differences it is not good enough to have tested thunks on an x86-64
host.

- The thunk **MUST** have a testing report on the wiki, and the appropriate page formatting to go along with it.
