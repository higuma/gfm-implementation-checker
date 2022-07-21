# Github Flabored Markdown implementation checker

[Table of Contents](index.md) →
[1. Introduction](introduction.md)

------------------------------------------------------------------------

## About this document (English | [日本語](README.ja.md))

This documentation is a helper for Markdown prosessing environments to determine how they render code examples of [Github Flabored Markdown (GFM) Specification (Version 0.29-gfm)](https://higuma.github.io/gfm-implementation-checker/).

The documentation copy all GFM examples 1 to 673 and embed them to markdown files as the same structure as GFM specification. On embedding, all charcters `→` which represents tab (U+0009) are substituted to the real tab characters.

Some code examples are rendered to other output pages as the following cases:

* Examples which contain [link reference definitions](https://higuma.github.io/gfm-implementation-checker/#link-reference-definitions).
* Examples which contain [HTML blocks](https://higuma.github.io/gfm-implementation-checker/#html-blocks) or [raw HTML](https://higuma.github.io/gfm-implementation-checker/#raw-html).
* Examples which contain unclosed blocks, or have possibilities to be recognized as unclosed.
* Examples which have possibilities to affect owner documents or other examples by other reasons.

## Table of contents

* About this document (English | [日本語](README.ja.md))
* [1 Introduction](introduction.md)
* [2 Preliminaries](preliminaries.md)
* [3 Blocks and inlines](blocks-and-inlines.md)
* [4 Leaf blocks](leaf-blocks.md)
* [5 Container blocks](container-blocks.md)
* [6 Inlines](inlines.md)
* [Appendix: A parsing strategy](appendix-a-parsing-strategy.md)

## [Full table of contents](index.md#full-table-of-contents)

------------------------------------------------------------------------

[Table of Contents](index.md) →
[1. Introduction](introduction.md)

