# IDS721 PJ1: minigrep
This is a minigrep command line tool that takes the txt input file and search a specific word in the input and store the output.

## Get Started
To try my code, first
```
git clone https://github.com/Mushroom-Wang/IDS721-PJ1-Final
```
Change to the minigrep directory
```
cd minigrep
```
Run the program
```
cargo run <query> <filename>
```
Run the test
```
cargo test
```
## Config

To set environment variable and make the search case insensitive, use `export CASE_INSENSITIVE=true`.
To unset environment variable and make the search case sensitive, use `unset CASE_INSENSITIVE`.

## References

* [rust-cli-template](https://github.com/kbknapp/rust-cli-template)
