# Papers (published and unpublished)

- [Proof-relevant unification](https://jesper.sikanda.be/files/proof-relevant-unification.pdf)

  Incredibly useful reformulation of most-general unifiers allowing for internalised representation of unification problems.
  General rules for unifying inductive data-types.

- [Observational Equality: Now For Good](https://hal.inria.fr/hal-03367052/document)

  Great ideas of computing equality by cases. And overall that's a TT many of us have dreamt of and Idris might implement one sometime.

- [Two-level type theory and applications](https://arxiv.org/pdf/1705.03307.pdf)

  User/programmer writes programs against the inner level. While
  the outer one internalises unification problems and meta-programs over the inner. Inner level is usually HoTT. Outer is
  Martin Lof Type Theory or perhaps Observational Type Theory.

- [A type theory for synthetic ∞-categories](https://arxiv.org/pdf/1705.07442.pdf)

  Was quite useful to better understand the cubical structure of cubical type theories. I've only read a small bit of it in due detail. Fascinating stuff.

- [Cubical type theory: a constructive interpretation of the univalence axiom](https://arxiv.org/pdf/1611.02108.pdf)

  Useful to understand in general because it's so close (or even equivalent, whatever that means) to HoTT described in The Book.

- [Cubical Agda](https://dl.acm.org/doi/pdf/10.1145/3341691)

  Useful to interpret the theoretical knowledge from the relevant papers against. After all (regular) Agda has a syntax and semantics similar to Idris.
  Too bad its canonical editor is emacs.

- [A Cubical Language for Bishop Sets/XTT, Jonathan Sterling](https://jozefg.github.io/papers/a-cubical-language-for-bishop-sets.pdf)

  Much more intuitive and flexible definition of Kan composition and coercion.

- [Decomposition of Univalence](https://arxiv.org/pdf/1712.04890.pdf)

  Quite useful for better understanding of what basic principles univalence implies.

- [HoTT: The Logic of Space, Michael Shulman](https://arxiv.org/pdf/1703.03007.pdf)

  Category Theoretic model of MLTT. Interpretting MLTT in an arbitrary LCCC

- [Meaning Explanaitions at Higher Dimension/Computational Model of CTT, Carlo Angiuli](https://www.cs.cmu.edu/~cangiuli/papers/brouwer.pdf)

  Computational model of CTT

- [Categorical logic, Michael Shulman](http://mikeshulman.github.io/catlog/catlog.pdf)

  Type theory as a presentation of free structure.

- [Internal Parametricity via modal operators](https://publications.lib.chalmers.se/records/fulltext/252073/local_252073.pdf)

- [Type Theory and its Meaning Explanations, Jonathan Sterling](https://arxiv.org/pdf/1512.01837.pdf)

  Deep dive into definition and semantics of a typing-judgement.

- [Cosmology of Data Types/generics-levitation, Pierre-Evariste Dagand](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.366.3635&rep=rep1&type=pdf)

  Presentation of data-types as signatures of a strictly positive endofunctor reflected onto itself.

- [Theory of Containers/generics](http://staff.mmcs.sfedu.ru/~ulysses/Edu/SSGEP/uustalu/tcs-containers.pdf)

  Alternative to strictly positive data-types and W-types.
  Better suited for generics.

- [Elaborating dependent (co)-pattern matching](https://dl.acm.org/doi/pdf/10.1145/3236770)

- [Internal Parametricity for CTT](https://arxiv.org/abs/2005.11290)

- [Higher Inductive Types and Internal Parametricity for CTT](https://kilthub.cmu.edu/articles/thesis/Higher_Inductive_Types_and_Internal_Parametricity_for_Cubical_Type_Theory/14555691)

- [M-Type (dual to W-type / terminal co-algebra) in HoTT](https://hott.github.io/M-types/m-types.pdf)

- [Overlapping order-independent patterns](https://jesper.sikanda.be/files/overlapping-and-order-independent-patterns.pdf)

  Those are much more intuitive to use in many cases for theorem proving and modelling.

- [Normalisation for CTT using gluing/synthetic Tait computability](https://arxiv.org/pdf/2101.11479.pdf)

  Promises to be extremely valuable to us. But the method is based on a lot of technical constructions.

- [Higher inductive types for CCTT with general schemas](https://www.cs.cmu.edu/~rwh/papers/higher/paper.pdf)

  I wouldn't say we necessarily need a schema for *higher* types but
  somewhat unexpectedly: regular inductive families need special treatment in CCTT even
  if they don't contain higher constructors. We need to figure this out
  to justify our addition of inductive data-types. Otherwise canonicity will be lost.

- [Type-checking through unification (draft)](https://arxiv.org/pdf/1609.09709v1.pdf)

  I stumbed upon this draft when reading the thesis on unification via twin variables below.
  The idea presented in the draft highly correlates to what we did back in 2021 to morph
  any type-checking problem into a unification-problem via equality and coercion.

- [Practical Heterogeneous Unification for Dependent Type Checking](https://research.chalmers.se/publication/527051/file/527051_Fulltext.pdf)

  A thesis on unification via twin variables mentioned by Edwin in his weekly new-core reports.

- [Programming in Martin Lof's Type Theory](https://courses.engr.illinois.edu/cs522/sp2016/ProgrammingInMartinLofsTypeTheory.pdf)

  A thorough account of Martin Lof's Type Theory.
  What I (Russoul) is particularly interested in is the higher order elimination rule for the Π-type.

- [Syntax and models of Cartesian CuTT](https://www.cs.cmu.edu/~rwh/papers/uniform/uniform.pdf)

- [Computational Higher Type Theory I: Abstract Cubical Realizability](https://arxiv.org/pdf/1604.08873.pdf)

- [Computational Higher Type Theory II: Dependent Cubical Realizability](https://arxiv.org/pdf/1606.09638.pdf)

- [Computational Higher Type Theory III: Univalent Universes and Exact Equality](https://arxiv.org/pdf/1712.01800.pdf)

- [Computational Higher Type Theory IV: Inductive Types](https://arxiv.org/pdf/1801.01568.pdf)

- [Generalised universe hierarchies, Andras Covacs](https://arxiv.org/pdf/2103.00223)

- [Type-Theoretic Signatures for Algebraic Theories and Inductive Types (thesis), Andras Covacs](https://andraskovacs.github.io/pdfs/phdthesis_compact.pdf)

  Signatures form a type-theory. So we have TT-in-TT. These signatures can be used to get quotient-inductive-inductive types

- [Inductive-recursive types, Andras Covacs](https://gist.github.com/AndrasKovacs/16ce01ad516b3f757ff5d88276f1c515)

  A note related to the above thesis extending it to quotient-inductive-inductive-recursive types

- [Locally cartesian closed categories and type theory, Seely](https://www.math.mcgill.ca/~rags/LCCC/LCCC.pdf)

  Model of ExtMLTT in Locally Cartesian Closed Categories

- [Representing Nested Inductive Types using W-types](https://www.cs.nott.ac.uk/~psztxa/publ/icalp04.pdf)

  Containers, nested inductive types, fixpoint combinator, w-types

- [An Atomic Lambda Calculus](https://people.bath.ac.uk/wbh22/pdf/2013-gundersen-heijltjes-parigot-JFLA-EN.pdf)

  A lambda calculus for explicit memory management. Could be very useful for parallel and GC-free runtime.

- [Spinal Atomic Lambda-Calculus](https://link.springer.com/chapter/10.1007/978-3-030-45231-5_30#preview)

  A laziness upgrade over "atomic lambda calculus"

# Books

- [The HoTT Book, The Univalent Foundations Program](https://homotopytypetheory.org/book/)

  Major source of knowledge about HoTT.

- [Intro to HoTT, Egbert Rijke](https://hott.github.io/HoTT-2019/images/hott-intro-rijke.pdf)

  Great supplemental material to "The HoTT Book".

# Posts and presentations

- [Short presentation for developing basic geometric intuition for HoTT](https://unimath.github.io/bham2017/Spartan-Type-Theory.pdf)

- [Type-Theoretic Yoneda Lemma (HoTT)](https://homotopytypetheory.org/2012/05/02/a-type-theoretical-yoneda-lemma/)

  Path induction as a type-theoretic counterpart of the category-theoretic Yoneda Lemma.
  The ∃ - * - ∀ adjunction.

- [What is a model of Type Theory?](http://128.2.67.219/ufias2012/files/cwf1.pdf)

