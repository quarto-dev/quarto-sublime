# quarto-sublime

Sublime Text plugin for [Quarto](https://quarto.org) markdown. Syntax highlighting for a wide variety of Quarto markdown constructs, including executable code cells.

To install, use **Package Control: Install Package** and search for 'quarto'.

Sublime Text does not bundle a Julia syntax, so Julia code stays plain unless a syntax providing the `source.julia` scope is installed. Without one, the console shows `Unable to find syntax file for scope "source.julia"` when the Quarto syntax loads; it is harmless. Mermaid cells are recognised and always stay plain.
