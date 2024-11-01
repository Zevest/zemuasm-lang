# ZEMUASM README

This is a simple syntax highlighting extension for ZEMUASM.

ZEMUASM (Z Emulator Assembly) is a tiny assembly language used to run on my custom computer emulator.
It uses a custom architecture inspired by the Gameboy.

![Preview](https://github.com/Zevest/zemuasm-lang/blob/master/images/preview.png?raw=true)

## Features
Syntax highlighting for zemuasm lang
- comments
- strings
- numbers
- registers
- opcodes
- labels
- db keyword
- sizeof macro '#'

Region folding
    - empty label with comment on same line to make a region (like `#region` in some languages)

    label: ; my region
    
## Release Notes

### 0.0.1
    Initial release of the extension (experimental)
