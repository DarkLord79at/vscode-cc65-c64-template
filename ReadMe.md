# VS Code Template for C64 Assembly Programming Using CC65 1.0.0

This VS Code template is intended to be used with the [ca65 Macro Assembler Language Support (6502/65816)](https://marketplace.visualstudio.com/items?itemName=tlgkccampbell.code-ca65) extension by [Cole Campbell](https://marketplace.visualstudio.com/publishers/tlgkccampbell).

With an `.asm` file tab focused use `Ctrl+Shift+P` then `Tasks: Run Test Task` to automatically build and launch VICE based on the current source file. Use `Ctrl+Shift+B` to build a `.prg` in the `build` directory only.

See `.vscode/tasks.json` for setting your OS' path to the VICE binary.

Source code should go into the `src` directory for structuring purposes.

(C) 2022-2023 by [DarkLord79at](https://github.com/DarkLord79at) ([prof79](https://github.com/prof79)) of [VCC](https://logiker.com/vcc). The template itself is "unlicensed" 🙂.
