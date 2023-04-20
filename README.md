# A repository of MetaOCaml packages

A repository of [OPAM][opam] packages for [BER MetaOCaml][metaocaml].

![GitHub Actions status](https://github.com/metaocaml/metaocaml-opam/workflows/MetaOCaml/badge.svg)

### Setting up

```
opam update
opam switch create 4.11.1+BER 
opam remote add metaocaml git+https://github.com/metaocaml/metaocaml-opam.git
```

[metaocaml]: http://okmij.org/ftp/ML/MetaOCaml.html
[opam]: https://opam.ocaml.org/

### Current packages:

* [asp](https://github.com/yallop/ocaml-asp/),
  typed, algebraic, staged parser combinators
* [flap](https://github.com/yallop/ocaml-flap),
  a deterministic parser with fused lexing
* [charmatch](https://github.com/yallop/metaocaml-charmatch),
  for generating efficient matches over characters
* [reex](https://github.com/yallop/reex),
  for staged regular expression matching
* [frex](https://github.com/frex-project/metaocaml-frex/),
  for multi-stage programming with algebras
* [letrec](https://github.com/yallop/metaocaml-letrec),
  for generating mutually-recursive definitions
* [staged-streams](https://github.com/strymonas/staged-streams.ocaml),
  for stream computations with fusion
