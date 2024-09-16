
A template project with a Makefile that supports sub-directories.

The Makefile will automatically detect and compile new source files
when they are added to the "src" and "res" directories.

Project directories
  - src: Main program source files (.c, .h, .s) can go here
  - res: Program graphics and audio source files (.c, .h, .s) can go here
  - obj: Compiled ROM (.gb) and debug files go in this directory


== Sprite and Background tiles from: ==

https://sondanielson.itch.io/gameboy-simple-rpg-tileset
"Licence is under CCA so you can use these assets both privately and commercially"
"You are free to use them as is or modify them to your liking. All i ask is you credit me if you do use them please :)"

---

  The template is just coppied from the gbdk template_subfolder example.
  It is setup to use [clangd](https://clangd.llvm.org/) as a lsp and be beside [gbdk2020](https://github.com/gbdk-2020/gbdk-2020)
  e.g.: ```
          GameBoy
            - gbdk
            - tetris
        ```
  Additionally [bgb](https://bgb.bircd.org/) is used for running the .gb file.
