# d.pico

Dayne's Raspberry Pi Pico / MCU 

The whole enchilada as of now!
```
bin
├── cl-picoruby-install # Install latest cached PicoRuby on the RPI PICO
├── cl-picoruby-latest  # Check GitHub for latest PicoRuby and download it to cache
lib
├── env.sh              # Environment vairables for the bin tools
├── helpers.sh          # Helper functions for the bin tools
└── insanity_check      # Sanity checker for dependancies 
```

### Releases

1. Update CHANGELOG.MD version
2. Commit changes
3. Tag: `git tag -a v?.?.? -m "version message"`
4. Push & push tags: `git push origin --tags`
