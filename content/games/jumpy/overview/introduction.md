---
title: Introduction
template: docs/page.html
weight: 10

extra:
    toc: true
---

![Fish Folk: Jumpy Preview](https://user-images.githubusercontent.com/24392180/151969075-399e9fea-e2de-4340-96a4-0a0e5b79c281.gif)

## Overview

Fish Folk: Jumpy is a tactical 2D shooter, played by up to 4 players online or on a shared screen. Aim either left or right; the rest is up to clever movement and positioning in this fish-on-fish brawler! For more information about our origin story (Duck Game et.al.) and big-picture plans, see our [design document](https://www.notion.so/erlendsh/Fish-Fight-1647ed74217e4e38a59bd28f4f5bc81a).

## Web Demo

Jumpy runs in the browser! You can play [web demo][web_demo] to try out the game, without needing to install anything on your computer.

We recommend using the Chrome browser or other derivatives for the best performance, or if you have issues with other browsers.

[web_demo]: https://fishfolk.github.io/jumpy/player/latest/

### Key Features (WIP)

- 2 to 4 players in either Local Multiplayer or Online Play
- Easy to pick up, emphasizing strategy over twitch reaction
- Customize characters with hats, saving them to your cross-platform profile
- Create & explore user-made weapons, levels, audio and other scripted extensions
- Smart-level creation tools
- Tournaments & matchmaking built-in

### Status

The game is currently under reconstruction as it is being rewritten to use the [Bevy] game engine. There are now 4 stable maps and 4 items in the new version, and the game is nearly ready for another release.

[Bevy]: https://bevyengine.org

## Community

### Contributing

Anyone involved in the Fish Folk community must follow our [code of conduct](https://github.com/fishfolk/jumpy/blob/main/CODE_OF_CONDUCT.md).

If you'd like to make something for Fish Folk, check out our [help-wanted](https://github.com/fishfolk/jumpy/labels/help%20wanted) issues or just ask us on [Discord](https://discord.gg/4smxjcheE5). We'll soon post an updated roadmap for the next month or two of work ahead.

Before committing and opening a PR, please run the following commands and follow their instructions:

1. `cargo clippy -- -W clippy::correctness -D warnings`
2. `cargo fmt`

### Learning Materials

#### Rust

- [Rusty Engine Tutorial](https://cleancut.github.io/rusty_engine/)
- [Rust sokoban](https://sokoban.iolivia.me/)
- <https://pragprog.com/titles/hwrust/hands-on-rust/>

#### Bevy

- [Unofficial Bevy Cheat Book](https://bevy-cheatbook.github.io/)

## Download & play

1. Download the latest version from the [releases](https://github.com/fishfolk/jumpy/releases) page.
2. Extract the archive and run the executable. (e.g. `./jumpy` or `jumpy.exe`)

### Launcher

[A cross-platform launcher](https://github.com/spicylobstergames/SpicyLauncher) is also available for downloading and launching the game easily.

### Distro Packages

#### Arch Linux

```sh
pacman -S jumpy
```

## Building

1. Install Rust with [rustup.rs](https://rustup.rs/)
2. Clone this repository: `git clone https://github.com/fishfolk/jumpy.git`
3. `cd jumpy`
4. `cargo run`

## Credits

- [Fish Folk: Jumpy Credits](./CREDITS.md)
- Input Icons: [Kadith's Icons](https://kadith.itch.io/kadiths-free-icons) by Kadith
