# dune-enabled-if
toying with dune 1.10.0 and the enabled_if stanza

build with `dune build @all`, the output of `tree _build` should look like
```
_build
├── default
│   ├── LICENSE
│   ├── README.md
│   ├── dune
│   ├── dune-project
│   ├── linux
│   │   ├── dune
│   │   ├── some_lib.ml
│   │   ├── some_lib.mli
│   │   ├── some_linux_lib.a
│   │   ├── some_linux_lib.cma
│   │   ├── some_linux_lib.cmxa
│   │   └── some_linux_lib.cmxs
│   ├── macosx
│   │   ├── dune
│   │   ├── some_lib.ml
│   │   ├── some_lib.mli
│   │   ├── some_macosx_lib.a
│   │   ├── some_macosx_lib.cma
│   │   ├── some_macosx_lib.cmxa
│   │   └── some_macosx_lib.cmxs
│   ├── some_lib
│   │   ├── dune
│   │   ├── some_lib.a
│   │   ├── some_lib.cma
│   │   ├── some_lib.cmxa
│   │   └── some_lib.cmxs
│   ├── test.bc
│   ├── test.exe
│   └── test.ml
└── log

4 directories, 27 files
```
