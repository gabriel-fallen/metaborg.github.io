# Stratego

The Stratego transformation was born from a pure rewriting approach to program transformation by the introduction of _traversal combinators_[@LuttikV97] and _programmable rewriting strategies_[@VisserBT98].

## Strategic Rewriting

This section reviews the classic definition of term rewriting and motivates the transition to strategic rewriting.

- [Term rewriting](strategic-rewriting/term-rewriting.md)
- [Limitations of term rewriting](strategic-rewriting/limitations-of-rewriting.md)
- [Factoring out Traversal](strategic-rewriting/traversal-with-rules.md)
- [Strategic Rewriting](strategic-rewriting/strategic-rewriting.md)

## Strategy Combinators

Rather than defining high-level strategies as primitives, Stratego provides basic strategies combinators for composing strategies.
The [section](../../references/stratego/strategy-combinators.md) in the reference manual provides a definition of all the combinators.
Here we expand that description with many examples.

- [Sequential combinators](strategy-combinators/sequential.md)
- [Term combinators](strategy-combinators/term.md)
- [Traveral combinators](strategy-combinators/traversal.md)
- [Type unifying traversals](strategy-combinators/type-unifying.md)

## References

\bibliography
