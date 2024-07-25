# Playground for `vim` Configurations
Too often, I find that I don't have a sufficiently configured `vim` for whatever file I'm editing. 
For the programming languages I use regularly (e.g. Python, `bash`), things are usually fine.
For stuff I occasionally use (e.g. Javascript), I find that I don't have some basic things 
For stuff I haven't used in a _long_ time (e.g. C, C++, Java), I might have configured things to work a long time ago, but have since gone through a _ton_ of revisions.
Often, I run into compatibility issues between plugins and/or non-plugin configuration.
Plugins are bad sometimes and don't listen to my configuration.

# TODO:
- [ ] Find documentation for vim configuration folder structure
- [ ] Figure out how I need to lay things out:
  - [ ] "Base" `vimrc`
  - [ ] Language-specific (file-extension determines) `vimrc` additions
  - [ ] File extension associations
      - [ ] How to not fuckup the builtin ones
      - [ ] How to un-fuckup the builtin ones
      - [ ] What's a good default?
  - [ ] Syntax files
  - [ ] Scripts
  - [ ] colorschemes
- [ ] Add my goto minimal `vimrc`
- [ ] Add whatever I figured out to make `:sh` with with my `.bash_profile` or `.bashrc`
- [ ] Add the all colorschemes I've accrued
- [ ] How to get around saving a file that I should've opened with `sudo`
    - [ ] At minimum: Write down copy-pastable instructions.
    - [ ] Can I make it a command?

## Configurations
### Programming Languages
- [ ] C
- [ ] C++
- [ ] Java
- [ ] `bash`
- [ ] Python
- [ ] Javascript
- [ ] Ruby
- [ ] Typescript
- [ ] Rust
- [ ] Prolog
- [ ] Lua
- [ ] Racket
- [ ] Haskell

### Configuration / Markup
- [ ] `vimrc`
- [ ] `json`
- [ ] `yaml`
- [ ] HTML
- [ ] lilypond

### Word Processing
- [ ] Markdown
- [ ] LaTeX
- [ ] Text

### Platforms
- [ ] macOS
- [ ] Linux
  - [ ] Debian
  - [ ] Raspbian
  - [ ] NixOS
  - [ ] Arch
  - [ ] Fedora
- [ ] Unix
  - [ ] FreeBSD
  - [ ] MINIX
- [ ] Windows
- [ ] Raspberry Pi

## Goals
- One `vim` configuration/something to rule them all that's easy to install on new machines
  - Should I just `git clone` the entire thing?
  - Should I make this a plugin? Will it recursively install the plugins I want?
  - Can we just symlink?
  - How will this change for each platform?
- Create copy-pastable segments for quick and dirty `vim` setups (e.g. _just_ a `vimrc`)
- Gather all the `colorschemes`
- For every language I care about:
  - How do I configure syntax highlighting?
  - Must be able to format a file:
    - Indentation
    - Bracket pairing
  - Lint a file
    - Error checking
    - Style checking
    - Type checking
  - What are the must-have plugins for that language?
- Plugins
  - How do I turn off/on plugins for specific languages?
  - How do I automatically install these once I have a new machine?
  - What plugin manager should I use going forward?
- Understand `vimrc` and `vim` plugin structure
  - Should I have a base config for all files and specific configs for each language?
  - Can I have a single base `.vimrc` and language-specific `vimrc`'s?
- Performance
  - Bootup
  - Preferences
  - Plugins
- For platforms I care about:
  - What's the "best" way install `vim`?
  - How do I install/compile `vim` with the configuration I need (e.g. Python support)?
  - What performance issues will I run across? What's a minimal/performant `vimrc` for that platform (e.g. Raspberry Pi, MINIX)?
- Airline
  - How do I get this to work everywhere?
  - Should I even care about this?
- What should I just make myself?
    - Scripts
    - Plugins
- What should I do about shitty colorschemes?
- What basic stuff can I port into IDEs for their `vim` plugins?
    - Overleaf/ShareLaTeX
    - VSCode
    - PyCharm
    - Eclipse

## Non-Goals
- Install `vim`
- Configure NeoVim
- Configure MacVim
- Make it turnkey for everyone else
- Create a "minimal" or "clean" `vimrc`
- Support every terminal emulator
- Solve all terminal encoding issues
- Configure other dotfiles (e.g. `bash`)
- Configure IDE `vim` plugins

## Resources
- Configuring `vim`
  - Syntax
  - Glossary
  - Folder Structure
- The Ultimate vimrc
  - [amix/vimrc](https://github.com/amix/vimrc)
  - [amix/vimrc | vimrcs/basic.vim](https://github.com/amix/vimrc/blob/ee7e06290982e91a55a631c32d8ba79466ce4c64/vimrcs/basic.vim)
