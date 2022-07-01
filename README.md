# Fizzbuzz in LOLCODE

An implementation of the 'fizzbuzz problem' (a common interview question apparently) in [LOLCODE](http://www.lolcode.org).

LOLCODE doesn't support reading arguments from `stdin`, so it runs interactively.

Asks for a number, and then returns:
- `FIZZ` if divisible by 3
- `BUZZ` if divisible by 5
- `FIZZBUZZ` if divisible by 3 and 5
- `LOL NO` if divisible by neither

## Installation

Requires a LOLCODE interpreter. The reference implementation is [lci](https://github.com/justinmeza/lci). Build from source or use a version provided by your package manager, e.g. for Homebrew `brew install lolcode`.

## Usage

`lci fizzbuzz.lol` from within the project directory.
