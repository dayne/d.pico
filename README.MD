# d.pico

Dayne's Raspberry Pi Pico / MCU 

The enchilada that works now is focused on [picoruby](https://github.com/picoruby/picoruby) helper scripts.
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

### Releases

1. Update CHANGELOG.MD version
2. Commit changes
3. Tag: `git tag -a v?.?.? -m "version message"`
4. Push & push tags: `git push origin --tags`

## TODO or NOTDO List

_The `d.pico` is a half baked collection of rusty tools to help reduce the barrier of entry for me (and hopefully others) to get hacking on the RPI Pico microcontrollers. No grand schemes to take over the world or become tools so the TODOs are many and none._

- [x] picoruby-latest
- [x] picoruby-install
- [ ] picoruby-build
- [ ] tinygo-install
- [ ] tinygo-latest
- [ ] micropython-install
- [ ] micropython-latest
