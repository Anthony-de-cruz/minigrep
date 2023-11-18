# minigrep
Minigrep from the Rust Book excersize

## Usage
To build:
```shell
cargo build --release
```
Syntax:
```shell
minigrep {search term} {file} -> {Lines with the search term}
```
To use with example poem.txt:
```shell
./target/release/minigrep are poem.txt
I'm nobody! Who are you?
```
Case sensitivity is controlled via the $IGNORE_CASE enviornment variable
