# DBJ RattleNIX - Linux Edition

Modern COFDM acoustic text communicator and CW repeater ID decoder for Linux.
Supports Ribbit & Rattlegram acoustic audio packets, 3-way color theming (Dark, Charcoal, Light), OTA self-updating, and real-time vectorized Morse code decoding with a glassmorphic web UI.

## Releases & Packages
- **Debian / Ubuntu (.deb):** Available under [Releases](https://github.com/jaenulton/DBJ-RattleNIX-Linux/releases) or direct download at `https://devbyjae.com/dbj-rattlenix.deb`
- **Arch Linux (PKGBUILD):** Available in `arch/PKGBUILD` and under Releases.

## Installation
### Debian / Ubuntu (.deb)
```bash
sudo dpkg -i dbj-rattlenix_1.12_amd64.deb
sudo apt-get install -f # resolve any runtime dependencies
```

### Arch Linux
```bash
cd arch && makepkg -si
```
