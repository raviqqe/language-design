# Language design

Language design resources grouped into topics

## Programming languages

- [Elm](https://github.com/elm)
- [Go](https://github.com/golang/go)
  - The package namespace system like Go works only with object-oriented programming as classes create sub-namespaces.
  - [Channels - A Tour of Go](https://tour.golang.org/concurrency/2)
  - [DQNEO/babygo](https://github.com/DQNEO/babygo)
- [Gluon](https://github.com/gluon-lang/gluon)
- [Expresso](https://github.com/willtim/Expresso)
- [IntercalScript](https://github.com/Storyyeller/IntercalScript)
  - Case objects are similar to polymorphic variants in OCaml.
- [TypeScript](https://github.com/microsoft/TypeScript)
- [Haskell](https://github.com/ghc/ghc)
- [OCaml](https://github.com/ocaml/ocaml)
- [Nim](https://github.com/nim-lang/Nim)
  - Its garbage collection with deferred reference counting is interesting.
- [Koka](https://github.com/koka-lang/koka)
- [Lean 4](https://github.com/leanprover/lean4)
- [Lobster](https://github.com/aardappel/lobster)
- [Swift](https://swift.org/)
- [Scala](https://www.scala-lang.org/)
- [Effekt](https://effekt-lang.org/)
- [Elixir](https://elixir-lang.org/)
- [Unison](https://www.unisonweb.org/)
- [Flix](https://flix.dev/)
- [Yatima](https://github.com/yatima-inc/yatima)
- [Lua](https://www.lua.org)

## Language design

- [Less is more: language features](https://blog.ploeh.dk/2015/04/13/less-is-more-language-features/)
- [プログラミング言語の未来はどうなるか](https://keens.github.io/blog/2021/01/04/future_of_proguramming_languages/)
- [Robert Virding - On Language Design (Lambda Days 2016)](https://www.youtube.com/watch?v=f3rP3JRq7Mw)
- [The Rise of "Worse is better"](https://www.dreamsongs.com/RiseOfWorseIsBetter.html)
- [Design Criteria for Programming Languages](http://jcsites.juniata.edu/faculty/rhodes/lt/plcriteria.htm)
- [Go at Google: Language Design in the Service of Software Engineering](https://go.dev/talks/2012/splash.article)
- [Language Design](https://cs.lmu.edu/~ray/notes/languagedesignnotes/)

## Type system

- [Lecture slides of recursive types at Cornell University](https://www.cs.cornell.edu/courses/cs4110/2012fa/lectures/lecture27.pdf)
- [Algebraic subtyping](https://www.cs.tufts.edu/~nr/cs257/archive/stephen-dolan/thesis.pdf)
  - [Polymorphism, Subtyping, and Type Inference in MLsub](https://www.repository.cam.ac.uk/handle/1810/261583)
- [Practical type inference for arbitrary-rank types](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/putting.pdf)

## Effect system

- [Effects bibliography](https://github.com/yallop/effects-bibliography)
- [libhandler](https://github.com/koka-lang/libhandler)

## Garbage collection

### Reference counting

- [Counting Immutable Beans: Reference Counting Optimized for Purely Functional Programming](https://arxiv.org/abs/1908.05647)
  - [Slides](https://leanprover.github.io/talks/IFL2019.pdf)
- [Perceus: Garbage Free Reference Counting with Reuse](https://www.microsoft.com/en-us/research/publication/perceus-garbage-free-reference-counting-with-reuse/)
- [Reference Counting with Frame Limited Reuse](https://www.microsoft.com/en-us/research/publication/reference-counting-with-frame-limited-reuse-extended-version/)
- [Reading Arc in Rust (Japanese)](https://qiita.com/qnighy/items/35db580a139d21f38410)

### Immix GC

- [mu/immix-rust](https://gitlab.anu.edu.au/mu/immix-rust)
- [Immix: A Mark-Region Garbage Collector with Space Efficiency, Fast Collection, and Mutator Performance](https://www.cs.utexas.edu/users/speedway/DaCapo/papers/immix-pldi-2008.pdf)
- [Taking Off the Gloves with Reference Counting Immix](http://users.cecs.anu.edu.au/~steveb/pubs/papers/rcix-oopsla-2013.pdf)
- [Rust as a Language for High Performance GC Implementation](http://users.cecs.anu.edu.au/~steveb/pubs/papers/rust-ismm-2016.pdf)

## Data structures

- [RRB-Trees: Efficient Immutable Vectors](https://infoscience.epfl.ch/record/169879/files/RMTrees.pdf)
  - [elm-array](https://github.com/exists-forall/elm-array)
- [Improving RRB-Tree Performance through Transience](https://hypirion.com/thesis.pdf)
  - [c-rrb](https://github.com/hypirion/c-rrb)
  - [The blog post](https://hypirion.com/musings/thesis)
  - [pvec-rs](https://github.com/arazabishov/pvec-rs)
  - [Other implementations and descriptions of RRB trees | Closure core library](https://cljdoc.org/d/org.clojure/core.rrb-vector/0.1.2/doc/other-implementations-and-descriptions-of-rrb-trees)
- [Optimizing Hash-Array Mapped Tries for Fast and Lean Immutable JVM Collections](https://michael.steindorfer.name/publications/oopsla15.pdf)
- [LazyList | Scala](https://www.scala-lang.org/api/current/scala/collection/immutable/LazyList.html)

## Coroutines

- [From folklore to fact: comparing implementations of stacks and continuations](https://dl.acm.org/doi/10.1145/3385412.3385994)

## Lazy evaluation

- [The Spineless Tagless G-machine](https://www.microsoft.com/en-us/research/wp-content/uploads/1992/04/spineless-tagless-gmachine.pdf)

## WASM

- [emscripten](https://emscripten.org/index.html)
- [wasmtime](https://github.com/bytecodealliance/wasmtime)
- [Cranelift](https://github.com/bytecodealliance/wasmtime/tree/main/cranelift)
  - [Cranelift IR](https://github.com/bytecodealliance/wasmtime/blob/main/cranelift/docs/ir.md)
- [wasi crate for Rust](https://github.com/bytecodealliance/wasi)
- [mimalloc](https://github.com/microsoft/mimalloc)
- [wasm-micro-runtime](https://github.com/bytecodealliance/wasm-micro-runtime)

## Module system

- [Deno](https://deno.land/)
  - [Linking to third party code](https://deno.land/manual/linking_to_external_code)

## Parallel computation

- [Keynote: Announcing Broadway - ElixirConf EU 2019](https://www.youtube.com/watch?v=IzFmNQGzApQ)
  - Basic back pressure can be implemented as queue limits.
  - [dashbitco/broadway](https://github.com/dashbitco/broadway)
  - [Akka Stream](https://doc.akka.io/docs/akka/current/stream/index.html)
- [Runtime Support for Multicore Haskell](https://www.microsoft.com/en-us/research/wp-content/uploads/2009/09/multicore-ghc.pdf)

## Compiler design

- [Guide to Rustc Development](https://rustc-dev-guide.rust-lang.org/)
