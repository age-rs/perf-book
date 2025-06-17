# perf-book

The Rust Performance Book.

## Viewing

The rendered (HTML) book is [here](https://nnethercote.github.io/perf-book/).

<!-- EPUB
Currently disabled due to
https://github.com/nnethercote/perf-book/actions/runs/6358429874/job/17270643057

An ePub version is available
[here](https://nnethercote.github.io/perf-book/The%20Rust%20Performance%20Book.epub).
experimental. The ePub file is generated with
[mdbook-epub](https://crates.io/crates/mdbook-epub), which is experimental. It
has excessive whitespace and is not as nice to read as the HTML version.
Nonetheless, it is usable if you really want to read the book on an e-reader.
-->

## Building

The book is built with [`mdbook`](https://github.com/rust-lang/mdBook), which
can be installed with this command:
```
cargo install mdbook
```
To build the book, run this command:
```
mdbook build
```
The generated files are put in the `book/` directory.

## Development

To view the built book, run this command:
```
mdbook serve
```
This will launch a local web server to serve the book. View the built book by
navigating to `localhost:3000` in a web browser. While the web server is
running, the rendered book will automatically update if the book's files
change.

To test the code within the book, run this command:
```
mdbook test
```

## Improvements

Suggestions for improvements are welcome, but I prefer them to be filed as
issues rather than pull requests. This is because I am very particular about
the wording used in the book. When pull requests are made, I typically take the
underlying idea of a pull request and rewrite it into my own words anyway.

This book contains no material produced by generative AI, and none will be
accepted.

## License

Licensed under either of
* Apache License, Version 2.0 ([LICENSE-APACHE](LICENSE-APACHE) or
  http://www.apache.org/licenses/LICENSE-2.0)
* MIT license ([LICENSE-MIT](LICENSE-MIT) or
  http://opensource.org/licenses/MIT)

at your option.

## Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Apache-2.0 license, shall
be dual licensed as above, without any additional terms or conditions.
