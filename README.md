# tui-input

[![Crate Status](https://img.shields.io/crates/v/tui-input.svg)](https://crates.io/crates/tui-input)
[![Docs Status](https://docs.rs/tui-input/badge.svg)](https://docs.rs/tui-input/)

[![tui-input.gif](https://s10.gifyu.com/images/tui-input.gif)](https://github.com/sayanarijit/tui-input/blob/main/examples/tui-rs-input/src/main.rs)

> **WARNING:** Most of the functionality is only human tested.

A TUI input library supporting multiple backends.

This crate can be used with [tui-rs](https://github.com/fdehau/tui-rs).

## Install

Cargo.toml

```toml
# crossterm
tui-input = "*"

# termion
tui-input = { version = "*", features = ["termion"], default-features = false }
```

## Features

- crossterm (default)
- termion
- serde

## Demo

See [examples](https://github.com/sayanarijit/tui-input/tree/main/examples).

## Used in

- [xplr](https://github.com/sayanarijit/xplr)

## TODO

- [x] [crossterm](https://github.com/crossterm-rs/crossterm) backend
- [x] [termion](https://github.com/ticki/termion) backend
- [ ] [rustbox](https://github.com/gchp/rustbox) backend
- [ ] [pancurses](https://github.com/ihalila/pancurses) backend
