# Github Flabored Markdown implementation checker

[Table of Contents](index.md) →
[1. Introduction](introduction.md)

------------------------------------------------------------------------

## About this document ([English](README.md) | 日本語)

本文書は[Github Flabored Markdown(GFM)仕様書 (Version 0.29-gfm)](https://higuma.github.io/gfm-implementation-checker/)の全コード例を実際のMarkdown処理系に掛けてHTMLを生成し、対象処理系がGFMにどれだけ準拠しているかを実際に確認する目的で作成した。

仕様書中のExamples 1-673を全てコピーペーストし、仕様書の章立てと同じ順序でMarkdown文書中に埋め込んで作られている。ただし仕様書のExamplesではTabを`→`で表現しているため、これらは全て本物のTab(U+0009)に置換してある。

なお次の場合は文書本文や他のコード例に影響を与える可能性を考慮し、個別の出力用Markdown文書にリンクする。

* [リンク参照定義](https://higuma.github.io/gfm-implementation-checker/#link-reference-definitions)を含む例
* [HTMLブロック](https://higuma.github.io/gfm-implementation-checker/#html-blocks)及び[生HTML](https://higuma.github.io/gfm-implementation-checker/#raw-html)の例
* 閉じていないブロック、またはブロックが閉じていないと解釈される可能性がある例
* その他の理由で文法的に外部に影響を及ぼす可能性があると判断した場合

## Table of contents

* About this document ([English](README.md) | 日本語)
* [1 Introduction](introduction.md)
* [2 Preliminaries](preliminaries.md)
* [3 Blocks and inlines](blocks-and-inlines.md)
* [4 Leaf blocks](leaf-blocks.md)
* [5 Container blocks](container-blocks.md)
* [6 Inlines](inlines.md)
* [Appendix: A parsing strategy](appendix-a-parsing-strategy.md)

## [Full table of contents](index.md/#full-table-of-contents)

------------------------------------------------------------------------

[Table of Contents](index.md) →
[1. Introduction](introduction.md)
