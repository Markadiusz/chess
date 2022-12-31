# chess

A project for a Rust course at MiMUW.

A mostly functional chess engine.

The game lasts until one of the kings is captured.
There is no En Passant.

### Available game modes:

2 Players

1 Player (vs AI)

0 Players (2 AIs battling each other)

## Setup

### [Rust instalation](https://rustup.rs/)

### [Bevy instalation](https://github.com/bevyengine/bevy/blob/main/docs/linux_dependencies.md)

### Build

    cargo run --release -- x y

x - number of human players (optional, default = 1)

y - AI search depth (optional, default = 6)

![chess](https://user-images.githubusercontent.com/64140832/210140780-ce1bf7f5-472a-4626-bccc-ef5151333e0e.png)
