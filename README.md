# Zero to Production in Rust

## What is this?

This is my implementation of the [Zero to Production in Rust](https://www.zero2prod.com/) book by Luca Palmieri.

## Dependencies

Currently uses lld or zld for linking. May experiment with [mold](https://github.com/rui314/mold) in the future.k

### Windows

```
cargo install -f cargo-binutils
rustup component add llvm-tools-preview
```

### Linux:

 - Ubuntu, `sudo apt-get install lld clang`
 - Arch, `sudo pacman -S lld clang`

### MacOS

`brew install michaeleisel/zld/zld`