[![Build Status](https://travis-ci.org/jmacdonald/scribe.svg?branch=master)](https://travis-ci.org/jmacdonald/scribe)

# Scribe: A text editor toolkit

## NOTE: This is a fork of https://github.com/jmacdonald/scribe.

Scribe was extracted from [Amp](https://amp.rs), a text editor written in Rust.
It provides a layered set of types for dealing with text documents.

* `GapBuffer` - Data structure optimized for successive, close-proximity edits.
* `Buffer` - Wrapper that provides bounds-checked cursor management, file
  persistence, undo/redo (with grouping), lexing (scope-qualified tokens),
  search, and more.
* `Workspace` - Collection of buffers with type detection, and buffer selection
  and lexer management.

More documentation can be found [here](https://docs.rs/scribe).
