Doc-ock — Extract documentation from OCaml files
------------------------------------------------
%%VERSION%%

> **NOTE**: this library is deprecated as a standalone project. The functionality implemented here can now be found in the [`model`](https://github.com/ocaml/odoc/tree/master/src/model) and [`xref`](https://github.com/ocaml/odoc/tree/master/src/xref) sub-libraries of the [odoc](https://github.com/ocaml/odoc) package.

Doc-ock is a library extract documentation from OCaml files

## Installation

Doc-ock can be installed with `opam`:

    opam install doc-ock

If you don't use `opam` consult the [`opam`](opam) file for build instructions.

## Testing

The package compiles and installs the interface
[`test/ocamlary.mli`](test/ocamlary.mli) in the package's `lib`
directory along the library. This allows documentation consumers and
renderers to exercise a common and tricky selection of documentation
features packages may use.
