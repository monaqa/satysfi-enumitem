# satysfi-enumitem

`enumitem` is a [SATySFi](https://github.com/gfngfn/SATySFi) package
for flexible ordered/unordered/description lists.
This package was named after the 
[enumitem](https://www.ctan.org/pkg/enumitem) package in LaTeX.

This package provides the following features/commands:

- More flexible and customizable listing commands than those in the standard `itemize` package
- Ordered lists that can be nested
- Commands for description list (definition list)

## Installation

You can install `enumitem` package with
[Satyrographos](https://github.com/na4zagin3/satyrographos),
a package manager of SATySFi.
First you should install Satyrographos
(see [README of Satyrographos](https://github.com/na4zagin3/satyrographos/blob/master/README.md))
and then type in your terminal as follows:

```
opam install satysfi-enumitem
satyrographos install
```

After installation, you can import this package by writing the following sentence in preamble (top of `.saty` file):

```
@require: enumitem/enumitem
```

## Usage

See [the documentation of enumitem](doc/enumitem.pdf) (Japanese only).

## License

MIT
