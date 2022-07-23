# Github Flabored Markdown implementation checker

[Table of contents](index.md) →
[1. Introduction](introduction.md)

------------------------------------------------------------------------

## About this document (English | [日本語](README.ja.md))

This documentation is a helper for Markdown processing environments to determine how they render code examples of [Github Flabored Markdown (GFM) Spec](https://github.github.com/gfm/) [Version 0.29-gfm (preserved mirror)](https://higuma.github.io/gfm-implementation-checker/).

The documentation copies all GFM examples 1 to 673 and embed them to markdown files as the same structure as GFM spec. On embedding, all charcters `→` which represent tabs are substituted to the real tab characters (U+0009).

Some code examples are rendered to other output pages for the following cases:

* Examples which contain [link reference definitions](https://higuma.github.io/gfm-implementation-checker/#link-reference-definitions).
* Examples which contain [HTML blocks](https://higuma.github.io/gfm-implementation-checker/#html-blocks) or [raw HTML](https://higuma.github.io/gfm-implementation-checker/#raw-html).
* Examples which contain unclosed [blocks], or [blocks] which may be parsed as unclosed.
* Examples which possibly affect owner documents or other examples by other reasons.

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

[Table of contents](index.md) →
[1. Introduction](introduction.md)

[blocks]: https://higuma.github.io/gfm-implementation-checker/#blocks
