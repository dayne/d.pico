# d.pico

Dayne's Raspberry Pi Pico / MCU 

The enchilada that works now is focused on [picoruby](https://github.com/picoruby/picoruby) helper scripts.

> _warning: the intention behind d.pico is to collect the tools that help me setup &  remember how to do things for Raspberry Pi / MCU hacking on Ubuntu/Linux and Raspberry Pi boxes. Not intended as broadly useful tools for others and not likely relevant for windows/mac/wsl/chrome environments._

```
bin
├── picoruby-install # Install cached PicoRuby to RPI PICO
├── picoruby-latest  # Check GitHub & download for latest
# Supported by:
lib
├── env.sh           # Environment vairables for the bin tools
├── helpers.sh       # Helper functions for the bin tools
└── insanity_check   # Sanity checker for dependancies 
```

## Usage

### Clone sanity check
  Try to avoid unleashing insane clones into the world.

  ```bash
  git clone https://github.com/dayne/d.pico
  cd d.pico
  ./lib/insanity_check
  ```
  Fix missing dependancies until you have a satisfied cow.

### Download and cache latest [picoruby](https://github.com/picoruby/picoruby) 
  `bin/picoruby-latest`

### Install picoruby on a pico

- Press and hold the BOOT button and plugin the pico
- Run `bin/picoruby-install`
- Attach to the pico with you favorite serial connection tool
  - Recommended: `gtkterm --port /dev/ttyACM0`

## Metabrain

### Releases

1. Update CHANGELOG.MD version
2. Commit changes
3. Tag: `git tag -a v?.?.? -m "version message"`
4. Push & push tags: `git push origin --tags`

### TODO or NOTDO List

_The `d.pico` is a half baked collection of rusty tools to help reduce the barrier of entry for me (and hopefully others) to get hacking on the RPI Pico microcontrollers. No grand schemes to take over the world or become tools so the TODOs are many and none._

- [x] picoruby-latest
- [x] picoruby-install
- [ ] picoruby-build
- [ ] tinygo-install
- [ ] tinygo-latest
- [ ] micropython-install
- [ ] micropython-latest
