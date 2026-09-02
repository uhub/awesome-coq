# awesome-coq

A curated list of awesome Coq frameworks, libraries and software.

* Learning and Reference
	* [Tutorials and Books](#tutorials-and-books)
	* [Examples and Exercises](#examples-and-exercises)
* Language and Tooling
	* [Compilers and Interpreters](#compilers-and-interpreters)
	* [Linters and Formatters](#linters-and-formatters)
	* [Editor and IDE Support](#editor-and-ide-support)
* Web
	* [Web Servers and Proxies](#web-servers-and-proxies)
* Data and Storage
	* [Serialization and Formats](#serialization-and-formats)
* Machine Learning and AI
	* [LLM and Inference](#llm-and-inference)
	* [Machine Learning Frameworks](#machine-learning-frameworks)
* Networking and Distributed
	* [Distributed Systems](#distributed-systems)
* User Interface
	* [Applications and End User Tools](#applications-and-end-user-tools)
* Testing and Quality
	* [Testing](#testing)
* Utilities
	* [Text Processing](#text-processing)
	* [Files and Operating System](#files-and-operating-system)
	* [General Purpose Libraries](#general-purpose-libraries)
* Science and Math
	* [Mathematics](#mathematics)
	* [Scientific Computing](#scientific-computing)
	* [Formal Methods and Proofs](#formal-methods-and-proofs)
* [Other](#other)

## Learning and Reference

### Tutorials and Books

* [rocq-community/rocq-tricks](https://github.com/rocq-community/rocq-tricks) - Tricks you wish the Coq manual told you [maintainer=@tchajed]
* [ilyasergey/pnp](https://github.com/ilyasergey/pnp) - Lecture notes for a short course on proving/programming in Coq via SSReflect.
* [xavierleroy/cdf-mech-sem](https://github.com/xavierleroy/cdf-mech-sem) - Coq development for the course "Mechanized semantics", Collège de France, 2019-2020
* [tchajed/iris-simp-lang](https://github.com/tchajed/iris-simp-lang) - We define a simple programming language, simp_lang, then instantiate Iris to verify simple simp_lang programs with concurrent separation logic.
* [philzook58/nand2coq](https://github.com/philzook58/nand2coq) - Build an educational formally verified version of the Nand 2 Tetris course using Coq (and other formal tools).
* [rocq-community/semantics](https://github.com/rocq-community/semantics) - A survey of semantics styles in Coq, from natural semantics through structural operational, axiomatic, and denotational semantics, to abstract interpretation [maintainer=@k4rtik]
* [anton-trunov/coq-lecture-notes](https://github.com/anton-trunov/coq-lecture-notes) - Coq Lecture Notes (WIP)
* [tchajed/ltac2-tutorial](https://github.com/tchajed/ltac2-tutorial) - Ltac2 tutorial
* [arthuraa/poleiro](https://github.com/arthuraa/poleiro) - A blog about Coq
* [choukh/Baby-Set-Theory](https://github.com/choukh/Baby-Set-Theory) - Coq集合论中文教程
* [xavierleroy/cdf-program-logics](https://github.com/xavierleroy/cdf-program-logics) - Companion Coq development for Xavier Leroy's 2021 lectures on program logics
* [vlopezj/coq-course](https://github.com/vlopezj/coq-course) - Coq course at Chalmers CSE
* [codyroux/broad-coq-tutorial](https://github.com/codyroux/broad-coq-tutorial) - Some unstructured notes concerning the Broad tutorial to take place in March 2020
* [rocq-prover/platform-docs](https://github.com/rocq-prover/platform-docs) - A project of short tutorials and how-to guides for Coq features and Coq Platform packages.
* [xavierleroy/cdf-sem-meca](https://github.com/xavierleroy/cdf-sem-meca) - Développement Coq pour le cours "Sémantiques mécanisées", Collège de France, 2019-2020
* [mgrabovsky/fm-notes](https://github.com/mgrabovsky/fm-notes) - Unassorted scribbles on formal methods, type theory, category theory, and so on, and so on *(archived)*
* [rocq-community/hoare-tut](https://github.com/rocq-community/hoare-tut) - A Tutorial on Reflecting in Coq the generation of Hoare proof obligations [maintainer=@k4rtik]

### Examples and Exercises

* [Lysxia/advent-of-coq-2018](https://github.com/Lysxia/advent-of-coq-2018) - Advent of Code 2018, in Coq! (https://adventofcode.com/2018)
* [rocq-community/coq-art](https://github.com/rocq-community/coq-art) - Coq code and exercises from the Coq'Art book [maintainers=@ybertot,@Casteran]
* [marshall-lee/software_foundations](https://github.com/marshall-lee/software_foundations) - My solutions to Software Foundations course in Coq proof assistant.
* [rocq-community/rocq-program-verification-template](https://github.com/rocq-community/rocq-program-verification-template) - Template project for program verification in the Rocq Prover, showcasing reasoning on CompCert's Clight language using the Verified Software Toolchain [maintainer=@palmskog]
* [mmcco/verified-parser-example](https://github.com/mmcco/verified-parser-example) - A minimal example of a formally verified parser using ocamllex and Menhir's Coq backend.

## Language and Tooling

### Compilers and Interpreters

* [AbsInt/CompCert](https://github.com/AbsInt/CompCert) - The CompCert formally-verified C compiler
* [jasmin-lang/jasmin](https://github.com/jasmin-lang/jasmin) - Language for high-assurance and high-speed cryptography
* [antalsz/hs-to-coq](https://github.com/antalsz/hs-to-coq) - Convert Haskell source code to Coq source code *(archived)*
* [mit-plv/koika](https://github.com/mit-plv/koika) - A core language for rule-based hardware design 🦑
* [CertiRocq/certirocq](https://github.com/CertiRocq/certirocq) - A Verified Compiler for Gallina, Written in Gallina
* [ymherklotz/vericert](https://github.com/ymherklotz/vericert) - A formally verified high-level synthesis tool based on CompCert and written in Coq.
* [plclub/hs-to-rocq](https://github.com/plclub/hs-to-rocq) - Convert Haskell source code to Coq source code.
* [INRIA/velus](https://github.com/INRIA/velus) - A Lustre compiler in Coq
* [mit-plv/rupicola](https://github.com/mit-plv/rupicola) - Gallina to Bedrock2 compilation toolkit
* [sigurdschneider/lvc](https://github.com/sigurdschneider/lvc) - LVC verified compiler
* [formal-land/rocq-of-python](https://github.com/formal-land/rocq-of-python) - Translate Python code to Rocq code for formal verification. Applied to the reference implementation of the Ethereum VM in Python (WIP, in pause)
* [pedrotst/coquedille](https://github.com/pedrotst/coquedille) - A Coq to Cedille compiler written in Coq
* [peregrine-project/peregrine-tool](https://github.com/peregrine-project/peregrine-tool) - Verified compiler from LambdaBox to WebAssembly, C, Rust, and OCaml
* [coq-ext-lib/coq-compile](https://github.com/coq-ext-lib/coq-compile) - A compiler for Coq *(archived)*
* [AU-COBRA/coq-rust-extraction](https://github.com/AU-COBRA/coq-rust-extraction) - Coq plugin for extracting Rust code
* [smorimoto/coq-to-ocaml-to-js](https://github.com/smorimoto/coq-to-ocaml-to-js) - Proof of concept to generate safe and fast JavaScript

### Linters and Formatters

* [rocq-community/coq-dpdgraph](https://github.com/rocq-community/coq-dpdgraph) - Build dependency graphs between Coq objects [maintainers=@Karmaki,@ybertot]

### Editor and IDE Support

* [hazelgrove/hazel](https://github.com/hazelgrove/hazel) - Hazel, a live functional programming environment with typed holes
* [rocq-archive/coq-serapi](https://github.com/rocq-archive/coq-serapi) - Coq Protocol Playground with Se(xp)rialization of Internal Structures.
* [Ptival/PeaCoq](https://github.com/Ptival/PeaCoq) - PeaCoq is a pretty Coq, isn't it?
* [EugeneLoy/coq_jupyter](https://github.com/EugeneLoy/coq_jupyter) - Jupyter kernel for Coq

## Web

### Web Servers and Proxies

* [coq-concurrency/pluto](https://github.com/coq-concurrency/pluto) - A web server written in Coq.

## Data and Storage

### Serialization and Formats

* [uwplse/cheerios](https://github.com/uwplse/cheerios) - Formally verified Coq serialization library with support for extraction to OCaml
* [Lysxia/coq-ceres](https://github.com/Lysxia/coq-ceres) - Coq library for serialization to S-expressions

## Machine Learning and AI

### LLM and Inference

* [LLM4Rocq/miniF2F-rocq](https://github.com/LLM4Rocq/miniF2F-rocq) - A Rocq version of the miniF2F dataset
* [JasonGross/autoformalization-transpilation](https://github.com/JasonGross/autoformalization-transpilation) - Using LLMs to transpile from Coq to Lean (public version, may be out of date)

### Machine Learning Frameworks

* [princeton-vl/CoqGym](https://github.com/princeton-vl/CoqGym) - A Learning Environment for Theorem Proving with the Coq proof assistant
* [ml4tp/gamepad](https://github.com/ml4tp/gamepad) - A Learning Environment for Theorem Proving

## Networking and Distributed

### Distributed Systems

* [uwplse/verdi](https://github.com/uwplse/verdi) - A framework for formally verifying distributed systems implementations in Coq
* [mit-pdos/perennial](https://github.com/mit-pdos/perennial) - Verifying concurrent storage and distributed systems
* [uwplse/verdi-raft](https://github.com/uwplse/verdi-raft) - An implementation of the Raft distributed consensus protocol, verified in Coq using the Verdi framework
* [AU-COBRA/ConCert](https://github.com/AU-COBRA/ConCert) - A framework for smart contract verification in Coq
* [verse-lab/toychain](https://github.com/verse-lab/toychain) - A minimalistic blockchain consensus implemented and verified in Coq
* [DistributedComponents/disel](https://github.com/DistributedComponents/disel) - Distributed Separation Logic: a framework for compositional verification of distributed protocols and their implementations in Coq
* [sec-bit/tokenlibs-with-proofs](https://github.com/sec-bit/tokenlibs-with-proofs) - Correctness proofs of Ethereum token contracts
* [cmeiklejohn/distributed-data-structures](https://github.com/cmeiklejohn/distributed-data-structures) - Distributed Data Structures in Coq
* [pirapira/evmverif](https://github.com/pirapira/evmverif) - An EVM code verification framework in Coq
* [logsem/aneris](https://github.com/logsem/aneris) - Program logic for developing and verifying distributed systems
* [vrahli/Velisarios](https://github.com/vrahli/Velisarios) - A Coq-based framework to verify the correctness of Byzantine fault-tolerant distributed systems
* [rocq-community/chapar](https://github.com/rocq-community/chapar) - A framework for verification of causal consistency for distributed key-value stores and their clients in Coq [maintainer=@palmskog]
* [novifinancial/LibraChain](https://github.com/novifinancial/LibraChain) - A library providing mechanized proofs of the LibraBFT consensus using the Coq theorem prover *(archived)*
* [tezos/tezoscoq](https://github.com/tezos/tezoscoq) - working with coq and tezos
* [Zilliqa/scilla-coq](https://github.com/Zilliqa/scilla-coq) - State-Transition Systems for Smart Contracts *(archived)*
* [AU-COBRA/PoS-NSB](https://github.com/AU-COBRA/PoS-NSB) - A formalization of a Proof-of-Stake Nakamoto-style blockchain in Coq

## User Interface

### Applications and End User Tools

* [clarus/coq-chick-blog](https://github.com/clarus/coq-chick-blog) - 🐣 A blog engine written and proven in Coq
* [MichaelBurge/pornview](https://github.com/MichaelBurge/pornview) - Porn browser formally-verified in Coq
* [formal-land/coq-bonsai](https://github.com/formal-land/coq-bonsai) - 🌳 Generate a fresh bonsai in your terminal
* [rocq-community/coqoban](https://github.com/rocq-community/coqoban) - Sokoban (in Coq) [maintainer=@erikmd]
* [thery/T2048](https://github.com/thery/T2048) - a version of the 2048 game for Coq
* [rocq-community/sudoku](https://github.com/rocq-community/sudoku) - A certified Sudoku solver in Coq [maintainers=@siraben,@thery]

## Testing and Quality

### Testing

* [QuickChick/QuickChick](https://github.com/QuickChick/QuickChick) - Randomized Property-Based Testing Plugin for Coq

## Utilities

### Text Processing

* [rocq-community/parseque](https://github.com/rocq-community/parseque) - Total Parser Combinators in Coq [maintainer=@womeier]

### Files and Operating System

* [mit-pdos/fscq](https://github.com/mit-pdos/fscq) - FSCQ is a certified file system written and proven in Coq
* [Lysxia/rocq-simple-io](https://github.com/Lysxia/rocq-simple-io) - IO for Gallina
* [coq-io/system](https://github.com/coq-io/system) - Library of Unix effects for Coq.

### General Purpose Libraries

* [rocq-community/coq-ext-lib](https://github.com/rocq-community/coq-ext-lib) - A library of Coq definitions, theorems, and tactics. [maintainers=@gmalecha,@liyishuai]
* [coq-io/io](https://github.com/coq-io/io) - A library for effects in Coq.
* [mit-plv/coqutil](https://github.com/mit-plv/coqutil) - Coq library for tactics, basic definitions, sets, maps
* [math-comp/finmap](https://github.com/math-comp/finmap) - Finite sets, finite maps, multisets and generic sets
* [tchajed/coq-record-update](https://github.com/tchajed/coq-record-update) - Library to create Coq record update functions
* [charguer/tlc](https://github.com/charguer/tlc) - Library for Classical Coq
* [arthuraa/extructures](https://github.com/arthuraa/extructures) - Finite sets and maps for Coq with extensional equality
* [vafeiadis/hahn](https://github.com/vafeiadis/hahn) - Hahn: A Coq library
* [uwplse/StructTact](https://github.com/uwplse/StructTact) - Coq utility and tactic library.
* [rocq-community/bits](https://github.com/rocq-community/bits) - A formalization of bitset operations in Coq and the corresponding axiomatization and extraction to OCaml native integers [maintainer=@anton-trunov]

## Science and Math

### Mathematics

* [HoTT/Coq-HoTT](https://github.com/HoTT/Coq-HoTT) - A Coq library for Homotopy Type Theory
* [UniMath/UniMath](https://github.com/UniMath/UniMath) - This rocq library aims to formalize a substantial body of mathematics using the univalent point of view.
* [jwiegley/category-theory](https://github.com/jwiegley/category-theory) - An axiom-free formalization of category theory in Coq for personal study and practical work
* [math-comp/math-comp](https://github.com/math-comp/math-comp) - Mathematical Components
* [stepchowfun/proofs](https://github.com/stepchowfun/proofs) - My personal repository of formally verified mathematics.
* [rocq-community/fourcolor](https://github.com/rocq-community/fourcolor) - Formal proof of the Four Color Theorem [maintainer=@ybertot]
* [UniMath/Foundations](https://github.com/UniMath/Foundations) - Voevodsky's original development of the univalent foundations of mathematics in Coq
* [math-comp/analysis](https://github.com/math-comp/analysis) - Mathematical Components compliant Analysis Library
* [GeoCoq/GeoCoq](https://github.com/GeoCoq/GeoCoq) - A formalization of geometry in Coq based on Tarski's axiom system
* [rocq-community/math-classes](https://github.com/rocq-community/math-classes) - A library of abstract interfaces for mathematical structures in Coq [maintainer=@spitters,@Lysxia]
* [uds-psl/coq-library-undecidability](https://github.com/uds-psl/coq-library-undecidability) - A library of mechanised undecidability proofs in the Coq proof assistant.
* [rocq-community/corn](https://github.com/rocq-community/corn) - Coq Repository at Nijmegen [maintainers=@spitters,@VincentSe,@Lysxia]
* [amintimany/Categories](https://github.com/amintimany/Categories) - A formalization of category theory in the Coq proof assistant.
* [rocq-community/hydra-battles](https://github.com/rocq-community/hydra-battles) - Variations on Kirby & Paris' hydra battles and other entertaining math in Coq (collaborative, documented, includes exercises) [maintainer=@Casteran]
* [affeldt-aist/infotheo](https://github.com/affeldt-aist/infotheo) - A Rocq formalization of information theory and linear error-correcting codes
* [rocq-community/coqeal](https://github.com/rocq-community/coqeal) - The Coq Effective Algebra Library [maintainers=@CohenCyril,@proux01]
* [meithecatte/busycoq](https://github.com/meithecatte/busycoq) - Busy Beaver deciders backed by Coq proof
* [choukh/Set-Theory](https://github.com/choukh/Set-Theory) - A formalization of the textbook Elements of Set Theory
* [vladimirias/Foundations](https://github.com/vladimirias/Foundations) - Voevodsky's original development of the univalent foundations of mathematics in Coq
* [jtassarotti/coq-proba](https://github.com/jtassarotti/coq-proba) - A Probability Theory Library for the Coq Theorem Prover
* [geohot/coq-hardy](https://github.com/geohot/coq-hardy) - Formalizing the Theorems from Hardy's "An Introduction to the Theory of Numbers" in coq
* [damien-pous/relation-algebra](https://github.com/damien-pous/relation-algebra) - Relation algebra library for Coq
* [rocq-community/topology](https://github.com/rocq-community/topology) - General topology in Coq [maintainers=@amiloradovsky,@Columbus240,@stop-cran]
* [rocq-community/dedekind-reals](https://github.com/rocq-community/dedekind-reals) - A formalization of the Dedekind real numbers in Coq [maintainer=@andrejbauer]
* [rocq-community/reglang](https://github.com/rocq-community/reglang) - Regular Language Representations in Coq [maintainers=@chdoc,@palmskog]
* [dschepler/coq-sequent-calculus](https://github.com/dschepler/coq-sequent-calculus) - Coq formalizations of Sequent Calculus, Natural Deduction, etc. systems for propositional logic
* [rocq-community/graph-theory](https://github.com/rocq-community/graph-theory) - Graph Theory [maintainers=@chdoc,@damien-pous]
* [thery/coqprime](https://github.com/thery/coqprime) - Prime numbers for Coq
* [math-comp/Coq-Combi](https://github.com/math-comp/Coq-Combi) - Algebraic Combinatorics in Coq
* [math-comp/odd-order](https://github.com/math-comp/odd-order) - The formal proof of the Odd Order Theorem
* [langston-barrett/coq-big-o](https://github.com/langston-barrett/coq-big-o) - A general yet easy-to-use formalization of Big O, Big Theta, and more based on seminormed vector spaces.
* [artagnon/bonak](https://github.com/artagnon/bonak) - 🧊 An indexed construction of semi-simplicial and semi-cubical sets
* [bmsherman/topology](https://github.com/bmsherman/topology) - Formal topology (and some probability) in Coq
* [math-comp/Abel](https://github.com/math-comp/Abel) - A proof of Abel-Ruffini theorem.
* [rocq-archive/zfc](https://github.com/rocq-archive/zfc) - An encoding of Zermelo-Fraenkel Set Theory in Coq
* [rocq-community/gaia](https://github.com/rocq-community/gaia) - Implementation of books from Bourbaki's Elements of Mathematics in Coq [maintainer=@thery]
* [rocq-community/goedel](https://github.com/rocq-community/goedel) - Archived since the contents have been moved to the Hydras & Co. repository *(archived)*
* [llee454/functional-algebra](https://github.com/llee454/functional-algebra) - This package provides a Coq formalization of abstract algebra using a functional programming style. The modules contained within the package span monoids, groups, rings, and fields and provides both axiom definitions for these structures and proofs of foundational results. The current package contains over 800 definitions and proofs.
* [rocq-community/alea](https://github.com/rocq-community/alea) - Coq library for reasoning on randomized algorithms [maintainers=@anton-trunov,@volodeyka]
* [rocq-community/apery](https://github.com/rocq-community/apery) - A formal proof of the irrationality of zeta(3), the Apéry constant [maintainer=@amahboubi,@pi8027]
* [thery/hanoi](https://github.com/thery/hanoi) - Hanoi tower in Coq
* [rocq-community/bignums](https://github.com/rocq-community/bignums) - Coq library of arbitrarily large numbers, providing BigN, BigZ, BigQ that used to be part of the standard library [maintainers=@proux01,@erikmd]
* [sudgy/math-from-nothing](https://github.com/sudgy/math-from-nothing) - Developing mathematics in Rocq from the ground up
* [Coq-Polyhedra/Coq-Polyhedra](https://github.com/Coq-Polyhedra/Coq-Polyhedra) - Formalizing convex polyhedra in Coq
* [Yosuke-Ito-345/Actuary](https://github.com/Yosuke-Ito-345/Actuary) - Formalization of the basic actuarial mathematics using Coq
* [choukh/CategoryTheory](https://github.com/choukh/CategoryTheory) - A Coq formalization of the textbook Categories and Toposes: Visualized and Explained
* [kai-qu/linear-logic](https://github.com/kai-qu/linear-logic) - An encoding of linear logic in Coq with minimal Sokoban and blocks world examples
* [rocq-community/HighSchoolGeometry](https://github.com/rocq-community/HighSchoolGeometry) - Geometry in Coq for French high school [maintainer=@thery]
* [styzystyzy/Axiomatic_Set_Theory](https://github.com/styzystyzy/Axiomatic_Set_Theory) - Formalization of Axiomatic Set Theory in Coq
* [hivert/Coq-Combi](https://github.com/hivert/Coq-Combi) - Algebraic Combinatorics in Coq
* [LogicalAtomist/principia-rewrite](https://github.com/LogicalAtomist/principia-rewrite) - The Principia Rewrite
* [rocq-community/coq-100-theorems](https://github.com/rocq-community/coq-100-theorems) - Statements of famous theorems proven in Coq [maintainer=@jmadiot]

### Scientific Computing

* [inQWIRE/SQIR](https://github.com/inQWIRE/SQIR) - A Small Quantum Intermediate Representation
* [inQWIRE/QuantumLib](https://github.com/inQWIRE/QuantumLib) - Coq library for reasoning about quantum programs
* [affeldt-aist/robot-rocq](https://github.com/affeldt-aist/robot-rocq) - Mathematics of Robotic Manipulation using Rocq and MathComp

### Formal Methods and Proofs

* [formal-land/rocq-of-rust](https://github.com/formal-land/rocq-of-rust) - Formal verification tool for Rust: check 100% of execution cases of your programs to make safer applications.
* [magmide/magmide](https://github.com/magmide/magmide) - A dependently-typed proof language intended to make provably correct bare metal code possible for working software engineers.
* [uwdb/Cosette](https://github.com/uwdb/Cosette) - Cosette is an automated SQL solver.
* [MetaRocq/metarocq](https://github.com/MetaRocq/metarocq) - Metaprogramming, verified meta-theory and implementation of Rocq in Rocq
* [PrincetonUniversity/VST](https://github.com/PrincetonUniversity/VST) - Verified Software Toolchain
* [vellvm/vellvm](https://github.com/vellvm/vellvm) - The Vellvm (Verified LLVM) coq development.
* [DeepSpec/InteractionTrees](https://github.com/DeepSpec/InteractionTrees) - A Library for Representing Recursive and Impure Programs in Coq
* [rocq-prover/equations](https://github.com/rocq-prover/equations) - A function definition package for Rocq
* [sifive/Kami](https://github.com/sifive/Kami) - Kami - a DSL for designing Hardware in Coq, and the associated semantics and theorems for proving its correctness. Kami is inspired by Bluespec. It is actually a complete rewrite of an older version from MIT
* [jscert/jscert](https://github.com/jscert/jscert) - A Coq specification of ECMAScript 5 (JavaScript) with verified reference interpreter
* [barry-jay-personal/tree-calculus](https://github.com/barry-jay-personal/tree-calculus) - Proofs in Coq for the book Reflective Programs in Tree Calculus
* [LPCIC/coq-elpi](https://github.com/LPCIC/coq-elpi) - Rocq plugin embedding Elpi
* [jwiegley/coq-haskell](https://github.com/jwiegley/coq-haskell) - A library for formalizing Haskell types and functions in Coq
* [mit-plv/kami](https://github.com/mit-plv/kami) - A Platform for High-Level Parametric Hardware Specification and its Modular Verification
* [smtcoq/smtcoq](https://github.com/smtcoq/smtcoq) - Communication between Coq and SAT/SMT solvers
* [discus-lang/iron](https://github.com/discus-lang/iron) - Coq formalizations of functional languages.
* [neelsomani/vericuda](https://github.com/neelsomani/vericuda) - A pipeline that translates Rust GPU code into formal Coq models, as a foundation for memory model proofs
* [project-oak/silveroak](https://github.com/project-oak/silveroak) - Formal specification and verification of hardware, especially for security and privacy. *(archived)*
* [verse-lab/ceramist](https://github.com/verse-lab/ceramist) - Verified hash-based AMQ structures in Coq
* [WasmCert/WasmCert-Coq](https://github.com/WasmCert/WasmCert-Coq) - A mechanisation of Wasm in Rocq
* [mit-plv/riscv-coq](https://github.com/mit-plv/riscv-coq) - RISC-V Specification in Coq
* [clarus/falso](https://github.com/clarus/falso) - A proof of false in Coq.
* [SkyLabsAI/BRiCk](https://github.com/SkyLabsAI/BRiCk) - Formalization of C++ for verification purposes.
* [math-comp/hierarchy-builder](https://github.com/math-comp/hierarchy-builder) - High level commands to declare a hierarchy based on packed classes
* [SSProve/ssprove](https://github.com/SSProve/ssprove) - A foundational framework for modular cryptographic proofs in Coq
* [imdea-software/htt](https://github.com/imdea-software/htt) - Hoare Type Theory
* [pi8027/lambda-calculus](https://github.com/pi8027/lambda-calculus) - A Formalization of Typed and Untyped λ-Calculi in Coq and Agda2
* [affeldt-aist/monae](https://github.com/affeldt-aist/monae) - Monadic effects and equational reasoning in Rocq
* [rocq-archive/coq-in-coq](https://github.com/rocq-archive/coq-in-coq) - A formalisation of the Calculus of Constructions
* [rocq-community/autosubst](https://github.com/rocq-community/autosubst) - Automation for de Bruijn syntax and substitution in Coq [maintainers=@RalfJung,@co-dan]
* [mit-plv/bedrock](https://github.com/mit-plv/bedrock) - Coq library for verified low-level programming
* [snu-sf/paco](https://github.com/snu-sf/paco) - A Coq library for parametric coinduction
* [lthms/FreeSpec](https://github.com/lthms/FreeSpec) - A framework for implementing and certifying impure computations in Coq
* [impermeable/rocq-waterproof](https://github.com/impermeable/rocq-waterproof) - The Waterproof plugin for the Rocq proof assistant allows you to write Rocq proofs in a style that resembles handwritten mathematical proofs, designed to help university students with learning how to prove mathematical statements.
* [rocq-community/fav-ssr](https://github.com/rocq-community/fav-ssr) - Functional Data Structures and Algorithms in SSReflect [maintainer=@clayrat]
* [uwplse/pumpkin-pi](https://github.com/uwplse/pumpkin-pi) - An extension to PUMPKIN PATCH with support for proof repair across type equivalences.
* [CertiRocq/VeriFFI](https://github.com/CertiRocq/VeriFFI) - VeriFFI: Verified Foreign Function Interface for connecting Coq programs to C programs at the operational and specification/verification levels; part of CertiCoq project
* [foreverbell/verified](https://github.com/foreverbell/verified) - Coq formalizations and proofs of (data) structures and algorithms.
* [wouter-swierstra/xmonad](https://github.com/wouter-swierstra/xmonad) - xmonad in Coq
* [vrahli/NuprlInCoq](https://github.com/vrahli/NuprlInCoq) - Implementation of Nuprl's type theory in Coq
* [rocq-community/paramcoq](https://github.com/rocq-community/paramcoq) - Old Coq plugin for parametricity [maintainer=@ppedrot]
* [snu-sf/promising-coq](https://github.com/snu-sf/promising-coq) - The Coq development of A Promising Semantics for Relaxed-Memory Concurrency
* [logsem/clutch](https://github.com/logsem/clutch) - Probabilistic separation logics for verifying higher-order probabilistic programs.
* [takanuva/cps](https://github.com/takanuva/cps) - A formalization of continuation-passing style calculi in Coq [WIP]
* [EasyCrypt/certicrypt](https://github.com/EasyCrypt/certicrypt) - CertiCrypt Coq Framework
* [Lysxia/system-F](https://github.com/Lysxia/system-F) - Formalization of the polymorphic lambda calculus and its parametricity theorem
* [math-comp/algebra-tactics](https://github.com/math-comp/algebra-tactics) - Ring, field, lra, nra, and psatz tactics for Mathematical Components
* [Blaisorblade/dot-iris](https://github.com/Blaisorblade/dot-iris) - Scala Step-by-Step: Soundness for DOT with Step-Indexed Logical Relations in Iris — Coq Formalization
* [fblanqui/color](https://github.com/fblanqui/color) - Coq library on rewriting theory and termination
* [gangtan/CPUmodels](https://github.com/gangtan/CPUmodels) - GoNative project: formal machines models in Coq
* [imdea-software/fcsl-pcm](https://github.com/imdea-software/fcsl-pcm) - Partial Commutative Monoids
* [CoqHott/logrel-coq](https://github.com/CoqHott/logrel-coq) - Logical Relation for MLTT in Coq
* [VeriNum/vcfloat](https://github.com/VeriNum/vcfloat) - VCFloat: A Unified Coq Framework for Verifying C Programs with Floating-Point Computations
* [reynir/Brainfuck](https://github.com/reynir/Brainfuck) - Brainfuck formalized in Coq
* [huynhtrankhanh/CoqCP](https://github.com/huynhtrankhanh/CoqCP) - We combat sloppy arguments in competitive programming and raise the standard of rigor
* [rocq-community/dblib](https://github.com/rocq-community/dblib) - Coq library for working with de Bruijn indices [maintainer=@KevOrr]
* [rocq-community/trocq](https://github.com/rocq-community/trocq) - A modular parametricity plugin for proof transfer in Coq [maintainers=@CohenCyril,@ecranceMERCE,@amahboubi,@lweqx,@MysaaJava]
* [weakmemory/imm](https://github.com/weakmemory/imm) - Intermediate Memory Model (IMM) and compilation correctness proofs for it
* [acorrenson/SATurne](https://github.com/acorrenson/SATurne) - Tiny verified SAT-solver
* [math-comp/mczify](https://github.com/math-comp/mczify) - Micromega tactics for Mathematical Components
* [pa-ba/calc-comp](https://github.com/pa-ba/calc-comp) - Coq proofs for the paper "Calculating Correct Compilers"
* [rafaelcgs10/W-in-Coq](https://github.com/rafaelcgs10/W-in-Coq) - This is a Coq formalization of Damas-Milner type system and its algorithm W.
* [dboulytchev/miniKanren-coq](https://github.com/dboulytchev/miniKanren-coq) - A certified semantics for relational programming workout.
* [rocq-community/lemma-overloading](https://github.com/rocq-community/lemma-overloading) - Libraries demonstrating design patterns for programming and proving with canonical structures in Coq [maintainer=@anton-trunov]
* [arthuraa/deriving](https://github.com/arthuraa/deriving) - Class instances for Coq inductive types with little boilerplate
* [damien-pous/coinduction](https://github.com/damien-pous/coinduction) - coinduction library for Coq
* [rocq-community/atbr](https://github.com/rocq-community/atbr) - Coq library and tactic for deciding Kleene algebras [maintainer=@tchajed]
* [lastland/ClairvoyanceMonad](https://github.com/lastland/ClairvoyanceMonad) - The Coq formalization of the paper Reasoning about the garden of forking paths.
* [pi8027/stablesort](https://github.com/pi8027/stablesort) - Stable sort algorithms and their stability proofs in Rocq
* [sweirich/graded-haskell](https://github.com/sweirich/graded-haskell) - Graded Dependent Type systems
* [bobatkey/system-f-parametricity-model](https://github.com/bobatkey/system-f-parametricity-model) - A Model of Relationally Parametric System F in Coq
* [dunnl/tealeaves](https://github.com/dunnl/tealeaves) - A Coq library for abstract syntactical reasoning
* [verif-scop/PolCert](https://github.com/verif-scop/PolCert) - A verified polyhedral scheduling validator in Coq. Vibing proving in progress: https://github.com/Hughshine/PolCert/tree/artifact/cpp27-anonymous-v10. Codex dev doc: https://github.com/verif-scop/polcert-dev/
* [CertiKOS/coqrel](https://github.com/CertiKOS/coqrel) - Binary logical relations library for the Coq proof assistant
* [jwiegley/coq-cds4ltl](https://github.com/jwiegley/coq-cds4ltl) - A formal verification of Linear Temporal Logic in Coq
* [Matafou/LibHyps](https://github.com/Matafou/LibHyps) - A Coq library providing tactics to deal with hypothesis
* [sifive/ProcKami](https://github.com/sifive/ProcKami) - Kami based processor implementations and specifications
* [xavierleroy/canonical-binary-tries](https://github.com/xavierleroy/canonical-binary-tries) - Coq development accompanying the paper "Efficient Extensional Binary Tries"
* [charguer/formalmetacoq](https://github.com/charguer/formalmetacoq) - Arthur's Formal Metatheory in Coq
* [rems-project/islaris](https://github.com/rems-project/islaris) - isla coq infrastructure
* [Huxpro/WasmCert](https://github.com/Huxpro/WasmCert) - A (in-development) Coq mechanization of WebAssembly specification.
* [jwiegley/coq-lattice](https://github.com/jwiegley/coq-lattice) - A reflection-based proof tactic for lattices in Coq
* [LS-Lab/Coq-dL](https://github.com/LS-Lab/Coq-dL) - A formally verified implementation of differential dynamic logic in Coq
* [rodrigogribeiro/unification](https://github.com/rodrigogribeiro/unification) - Formalisation of a type unification algorithm in Coq proof assistant.
* [aslanix/SmallStepNI](https://github.com/aslanix/SmallStepNI) - Mechanization of a noninterference proof for a toy imperative language with small-step semantics in Coq
* [CertiGraph/CertiGraph](https://github.com/CertiGraph/CertiGraph) - A library for verifying graph-manipulating programs. Powered by Coq and VST. Compatible with CompCert.
* [micro-policies/micro-policies-coq](https://github.com/micro-policies/micro-policies-coq) - Coq formalization accompanying the paper: Micro-Policies: A Framework for Verified, Tag-Based Security Monitors
* [heades/System-F-Coq](https://github.com/heades/System-F-Coq) - System F in coq.
* [Ptival/HaysTac](https://github.com/Ptival/HaysTac) - A pile of Ltac tactics that might contain the needle you're looking for...
* [aspiwack/cosa](https://github.com/aspiwack/cosa) - A thing about Coq-verified Shape Analysis

## Other

* [gustavo-depaula/stalin-sort](https://github.com/gustavo-depaula/stalin-sort) - Add a stalin sort algorithm in any language you like ❣️ if you like give us a ⭐️
* [mit-plv/fiat-crypto](https://github.com/mit-plv/fiat-crypto) - Cryptographic Primitive Code Generation by Fiat
* [achlipala/frap](https://github.com/achlipala/frap) - Formal Reasoning About Programs
* [ccz181078/Coq-BB5](https://github.com/ccz181078/Coq-BB5)
* [mit-plv/bedrock2](https://github.com/mit-plv/bedrock2) - A work-in-progress language and compiler for verified low-level programming
* [lulinchen/cnn_open](https://github.com/lulinchen/cnn_open) - A hardware implementation of CNN, written by Verilog and synthesized on FPGA
* [hacspec/hacspec](https://github.com/hacspec/hacspec) - Please see https://github.com/hacspec/hax *(archived)*
* [accordproject/ergo](https://github.com/accordproject/ergo) - Programming Language for Smart Legal Contracts *(archived)*
* [mit-plv/fiat](https://github.com/mit-plv/fiat) - Mostly Automated Synthesis of Correct-by-Construction Programs
* [fraunhoferfokus/acsl-by-example](https://github.com/fraunhoferfokus/acsl-by-example) - Public snapshots of "ACSL by Example"
* [uds-psl/MPCTT](https://github.com/uds-psl/MPCTT) - Modeling and Proving in Computational Type Theory
* [UniMath/TypeTheory](https://github.com/UniMath/TypeTheory) - The mathematical study of type theories, in univalent foundations
* [PrimeMHD/FPGA_ThreeLevelStorage](https://github.com/PrimeMHD/FPGA_ThreeLevelStorage) - 【原创，已被编入官方教材】Three-level storage subsystem(SD+DDR2 SDRAM+Cache), based on Nexys4 FPGA board. 同济大学计算机系统结构课程设计，FPGA三级存储子系统。
* [inQWIRE/QWIRE](https://github.com/inQWIRE/QWIRE) - A quantum circuit language and formal verification tool
* [jonleivent/mindless-coding](https://github.com/jonleivent/mindless-coding) - Mindless, verified (erasably) coding using dependent types
* [logsem/iris-tutorial](https://github.com/logsem/iris-tutorial)
* [jwiegley/coq-pipes](https://github.com/jwiegley/coq-pipes)
* [TheoWinterhalter/formal-type-theory](https://github.com/TheoWinterhalter/formal-type-theory) - Formalising Type Theory in a modular way for translations between type theories
* [TiarkRompf/collapsing-towers](https://github.com/TiarkRompf/collapsing-towers) - Collapsing Towers of Interpreters
* [UniMath/Schools](https://github.com/UniMath/Schools)
* [robbertkrebbers/ch2o](https://github.com/robbertkrebbers/ch2o)
* [DeepSpec/dsss17](https://github.com/DeepSpec/dsss17) - Lecture material for DeepSpec Summer School 2017
* [TiarkRompf/minidot](https://github.com/TiarkRompf/minidot) - Dependent Object Types (DOT), bottom up
* [IBM/FormalML](https://github.com/IBM/FormalML) - Formalization of Machine Learning Theory with Applications to Program Synthesis
* [NVlabs/ptxmemorymodel](https://github.com/NVlabs/ptxmemorymodel)
* [plclub/metalib](https://github.com/plclub/metalib) - The Penn Locally Nameless Metatheory Library
* [gtjennings1/UPDuino_v2_0](https://github.com/gtjennings1/UPDuino_v2_0) - UPDuino v2.0 - PCB Design Files, Designs, Documentation
* [awslabs/aws-lc-verification](https://github.com/awslabs/aws-lc-verification) - This repository contains specifications, proof scripts, and other artifacts required to formally verify portions of AWS libcrypto. Formal verification is used to locate bugs and increase assurance of the correctness and security of the library.
* [sfja/sfja](https://github.com/sfja/sfja) - SoftwareFoundations(Ja)
* [codyroux/name-the-biggest-number](https://github.com/codyroux/name-the-biggest-number)
* [plclub/sf-in-lean](https://github.com/plclub/sf-in-lean) - Development repo for translating Software Foundations to Lean
* [samuelgruetter/dot-calculus](https://github.com/samuelgruetter/dot-calculus) - Formalization of the Dependent Object Types (DOT) calculus
* [TiarkRompf/scala-escape](https://github.com/TiarkRompf/scala-escape) - A compiler plug-in to control object lifetimes in Scala
* [sweirich/corespec](https://github.com/sweirich/corespec) - A Specification for Dependent Types in Haskell (Core)
* [querycert/qcert](https://github.com/querycert/qcert) - Compilation and Verification of Data-Centric Languages
* [peterlefanulumsdaine/general-type-theories](https://github.com/peterlefanulumsdaine/general-type-theories) - A (formalised) general definition of type theories
* [sipa/safegcd-bounds](https://github.com/sipa/safegcd-bounds) - Bounds on divsteps iterations in safegcd
* [TiarkRompf/reachability](https://github.com/TiarkRompf/reachability)
* [Mtac2/Mtac2](https://github.com/Mtac2/Mtac2)
* [adampetcher/fcf](https://github.com/adampetcher/fcf) - Foundational Cryptography Framework for machine-checked proofs of cryptography.
* [tcarstens/verlang](https://github.com/tcarstens/verlang)
* [Lysxia/profunctor-monad](https://github.com/Lysxia/profunctor-monad) - Bidirectional programming in Haskell with monadic profunctors
* [sweirich/replib](https://github.com/sweirich/replib) - Replib: generic programming & Unbound: generic treatment of binders
* [Veridise/Coda](https://github.com/Veridise/Coda)
* [ChezJrk/verified-scheduling](https://github.com/ChezJrk/verified-scheduling)
* [garrigue/certint](https://github.com/garrigue/certint) - A Certified Interpreter for ML with Structural Polymorphism
* [yugithub/OFDM-baseband](https://github.com/yugithub/OFDM-baseband) - Verilog实现OFDM基带
* [Lysxia/advent-of-coq-2021](https://github.com/Lysxia/advent-of-coq-2021)
* [UCSD-PL/proverbot9001](https://github.com/UCSD-PL/proverbot9001)
* [QinxiangCao/QualifiedCProgramming](https://github.com/QinxiangCao/QualifiedCProgramming) - QCP (Qualified C Programming), a C program verification tool
* [plclub/cis670-16fa](https://github.com/plclub/cis670-16fa) - Advanced Topics in Programming Languages, Penn CIS 670, Fall 2016
* [dbp/howtoproveacompiler](https://github.com/dbp/howtoproveacompiler) - Writeup that goes along with this:
* [pirapira/dry-analyzer](https://github.com/pirapira/dry-analyzer) - Dr. Y's Ethereum Contract Analyzer
* [HIPERFIT/contracts](https://github.com/HIPERFIT/contracts) - Symbolic financial contract EDSL
* [liufengyun/stoic](https://github.com/liufengyun/stoic) - a capability-based system
* [OUPL/MLCert](https://github.com/OUPL/MLCert) - Certified Machine Learning
* [rocq-prover/stdlib](https://github.com/rocq-prover/stdlib) - Stdlib for the Rocq Prover
* [RSPwFPGAs/opae-xilinx](https://github.com/RSPwFPGAs/opae-xilinx) - OPAE porting to Xilinx FPGA devices.
* [rems-project/archsem](https://github.com/rems-project/archsem) - Rocq framework to define the semantics of CPU architectures
* [smtcoq/sniper](https://github.com/smtcoq/sniper)
* [rocq-archive/stdlib2](https://github.com/rocq-archive/stdlib2)
* [tlringer/proof-demos](https://github.com/tlringer/proof-demos) - Repository where I'll collect some demos of proof assistants that I show to various people in order to spread the magic
* [bit-mips/bitmips_experiments](https://github.com/bit-mips/bitmips_experiments) - 北京理工大学 MIPS 指令集 CPU 设计系列教学实验
* [uds-psl/coq-library-complexity](https://github.com/uds-psl/coq-library-complexity)
* [vzaliva/helix](https://github.com/vzaliva/helix) - Formally verified operator language and rewriting engine for high-performance computing
* [aa755/ROSCoq](https://github.com/aa755/ROSCoq) - Robots powered by Constructive Reals
* [formal-land/garden](https://github.com/formal-land/garden) - Make your zero-knowledge circuits safe with formal verification. 🍀
* [jwiegley/bytestring-fiat](https://github.com/jwiegley/bytestring-fiat) - An implementation of the Haskell ByteString library using the Fiat system from MIT
* [vellvm/vellvm-legacy](https://github.com/vellvm/vellvm-legacy)
* [pedagand/MPRI-2.4-DTP](https://github.com/pedagand/MPRI-2.4-DTP) - MPRI-2.4 Dependently-typed Functional Programming
* [Beluga-lang/McTT](https://github.com/Beluga-lang/McTT) - Building A Correct-By-Construction Proof Checkers For Type Theories
* [KevinHexin/FPGA-Bicubic-interpolation](https://github.com/KevinHexin/FPGA-Bicubic-interpolation) - use Verilog HDL implemente bicubic interpolation in FPGA
* [mit-frap/spring23](https://github.com/mit-frap/spring23) - Problem Sets for MIT 6.512 Formal Reasoning About Programs, Spring 2023
* [0xf3cd/CPU54-Pipeline](https://github.com/0xf3cd/CPU54-Pipeline) - CPU based on MIPS with 5-stage pipeline and cache, working with DDR2 memory and SD card.
* [tchajed/coq-tla](https://github.com/tchajed/coq-tla)
* [coq-quantum/CoqQ](https://github.com/coq-quantum/CoqQ)
* [mit-plv/bbv](https://github.com/mit-plv/bbv) - Bedrock Bit Vector Library
* [rocqetry/rocqet](https://github.com/rocqetry/rocqet) - Rocqet proof language
* [fredfeng/CS292C](https://github.com/fredfeng/CS292C)
* [ichistmeinname/free-proving](https://github.com/ichistmeinname/free-proving) - Resources for "One Monad to Prove Them All"
* [barry-jay-personal/typed_tree_calculus](https://github.com/barry-jay-personal/typed_tree_calculus) - types for various combinatory systems, especialy tree calculi
* [mit-plv/rewriter](https://github.com/mit-plv/rewriter) - Reflective PHOAS rewriting/pattern-matching-compilation framework for simply-typed equalities and let-lifting
* [PrincetonUniversity/DeepSpecDB](https://github.com/PrincetonUniversity/DeepSpecDB)
* [Agnishom/lregex](https://github.com/Agnishom/lregex) - Verified and Efficient Matching of Regular Expressions with Lookaround
* [logsem/cerise](https://github.com/logsem/cerise) - Formalisation of a capability machine and principles for reasoning about security properties
* [runtimeverification/algorand-verification](https://github.com/runtimeverification/algorand-verification) - Formal verification of the Algorand consensus protocol
* [CategoricalData/HoTT-categories](https://github.com/CategoricalData/HoTT-categories) - A category theory library built on top of Homotopy Type Theory, by Jason Gross
* [CharlesCNorton/intel-4004-verified](https://github.com/CharlesCNorton/intel-4004-verified) - Formalizing the Intel 4004 microprocessor
* [konne88/bagpipe](https://github.com/konne88/bagpipe) - BGP Policy Verification
* [max2468tw/IC_Lab](https://github.com/max2468tw/IC_Lab) - NCTU 2018 Spring Integrated Circuit Design Laboratory
* [kcrary/istari](https://github.com/kcrary/istari)
* [QinxiangCao/UnifySL](https://github.com/QinxiangCao/UnifySL)
* [ynot-harvard/ynot](https://github.com/ynot-harvard/ynot) - The Ynot Project source code.
* [dricketts/teaching-concurrency](https://github.com/dricketts/teaching-concurrency) - Specifications and safety proofs in different tools of a simple concurrent algorithm
* [Javran/Thinking-dumps](https://github.com/Javran/Thinking-dumps) - This repo keeps track of my codes, answers and thinkings when exploring books.
* [kunalg123/riscv_workshop_collaterals](https://github.com/kunalg123/riscv_workshop_collaterals) - This repository is created for conducting RISC-V 5-day workshops
* [MudroadWhite/Neo-Principia](https://github.com/MudroadWhite/Neo-Principia) - Continuation on formalizing Principia Mathematica
* [RiccardoBiosas/LeanGPT](https://github.com/RiccardoBiosas/LeanGPT) - Experiments with interactive theorem provers, LLMs and formal systems
* [rocq-archive/automata](https://github.com/rocq-archive/automata) - Beginning of formal language theory
* [ankitku/TAL0](https://github.com/ankitku/TAL0) - Based on paper by Greg Morrisett , TAL-0 is the design of a RISC-style typed assembly language which focuses on control-flow safety.
* [mit-frap/spring18](https://github.com/mit-frap/spring18) - Problem Sets for MIT 6.822 Formal Reasoning About Programs, Spring 2018
* [ropas/zooberry](https://github.com/ropas/zooberry) - A software framework for global sparse analyzers and their verified validators
* [vellvm/ctrees](https://github.com/vellvm/ctrees) - An itree-like data-structure to additionally support internal non-determinism
* [fplaunchpad/cs6225_s25_iitm](https://github.com/fplaunchpad/cs6225_s25_iitm) - Programs and Proofs -- Spring 2025 -- IITM
* [katydid/regex-deriv-coq](https://github.com/katydid/regex-deriv-coq)
* [picodma/picodma-fpga](https://github.com/picodma/picodma-fpga)
* [robbertkrebbers/compcert](https://github.com/robbertkrebbers/compcert) - Fork of http://compcert.inria.fr/
* [rocq-archive/ltl](https://github.com/rocq-archive/ltl) - Linear Temporal Logic
* [uds-psl/autosubst-ocaml](https://github.com/uds-psl/autosubst-ocaml)
* [braibant/Synthesis](https://github.com/braibant/Synthesis)
* [inQWIRE/VyZX](https://github.com/inQWIRE/VyZX) - Verifying the ZX Calculus
* [jonsterling/coq-guarded-computational-type-theory](https://github.com/jonsterling/coq-guarded-computational-type-theory)
* [joscoh/why3-semantics](https://github.com/joscoh/why3-semantics) - Formal Semantics for Why3
* [tymmym/software-foundations](https://github.com/tymmym/software-foundations) - Solutions to the exercises from the 'Software Foundations' book by Benjamin Pierce et al.
* [arthuraa/memory-safe-language](https://github.com/arthuraa/memory-safe-language) - A formalization of properties of a simple imperative, memory-safe language.
* [atungare/coq-software-foundations](https://github.com/atungare/coq-software-foundations)
* [bloomberg/game-trees](https://github.com/bloomberg/game-trees) - Functions and proofs about game trees in Rocq, implemented as rose trees.
* [daniellustig/pipecheck](https://github.com/daniellustig/pipecheck)
* [dongjaelee1/refinement-tutorial](https://github.com/dongjaelee1/refinement-tutorial) - Tutorial for refinement based verification
* [julesjacobs/cgraphs](https://github.com/julesjacobs/cgraphs) - Deadlock freedom by type checking
* [katamaran-project/katamaran](https://github.com/katamaran-project/katamaran) - Katamaran is a semi-automated separation logic verifier for the Sail specification language. It works on an embedded version of Sail called μSail and verifies separation logic-based contracts of functions by generating (succinct) first-order verification conditions.
* [l2ctsinghua/l2c](https://github.com/l2ctsinghua/l2c)
* [maximedenes/coq-amd64](https://github.com/maximedenes/coq-amd64)
* [mit-frap/spring17](https://github.com/mit-frap/spring17) - Problem Sets for MIT 6.887 Formal Reasoning About Programs, Spring 2017
* [mit-frap/spring22](https://github.com/mit-frap/spring22) - Problem Sets for MIT 6.822 Formal Reasoning About Programs, Spring 2022
* [mozow01/A1-2024-vill](https://github.com/mozow01/A1-2024-vill)
