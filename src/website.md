# The decompiler.wiki Website

## Development

- [install mdBook](https://rust-lang.github.io/mdBook/guide/installation.html)

## Architecture

- Use mdbook instead of wiki engines. Wiki engines requires a dedicated server. It's hard to maintain a server and keep it running stably.
- Use giscuz as the comment system.
- Deploy to the gh-pages branch.

## Writing

See [mdBook documentation](https://rust-lang.github.io/mdBook/index.html).

- [Inline equations](https://rust-lang.github.io/mdBook/format/mathjax.html#inline-equations) are delimited by `\\(` and `\\)`.
- [Block equations](https://rust-lang.github.io/mdBook/format/mathjax.html#block-equations) are delimited by `\\[` and `\\]`.
- [footnotes](https://rust-lang.github.io/mdBook/format/markdown.html#footnotes)
