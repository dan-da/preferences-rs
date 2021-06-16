# preferences-ron
Read and write user-specific Rust application data in [RON format](https://github.com/ron-rs/ron).

RON stands for `Rusty Object Notation` and looks similar to JSON but
fully encodes Rust type information.

This crate is a fork of [preferences-rs](https://github.com/AndyBarron/preferences-rs), which uses JSON.  Unfortunately some application data structures cannot be written in JSON.  Particularly
those that use structs as map keys.  Also that library seems unmaintained since 2017 and does 
not yet support Serde 1.0+.  Hence this fork.

## Documentation
https://docs.rs/preferences-ron

## Installation

```
$ cargo add preferences-ron
```