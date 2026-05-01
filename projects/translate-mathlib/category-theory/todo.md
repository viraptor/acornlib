# Category Theory

Goal: provide the categorical abstractions that Mathlib uses to organize large mathematical theories.

## Categories

- [ ] Restore `identity_iso`/`iso_sym` field-accessor theorems in `src/iso.ac` once the
      blocked `Iso[O, M]` certificate bug is fixed (see root `## Blockers`)
- [ ] Build composition of isomorphisms in `src/iso.ac` (`iso_trans`)
- [ ] Build the discrete category construction (objects only, identity morphisms)
- [ ] Build the opposite category construction
- [ ] Build the product category construction
- [ ] Add a small example category instance (e.g. terminal/initial 1-object category)

## Functors and Natural Transformations

- [ ] Add functors and natural transformations
- [ ] Support equivalences of categories

## Universal Constructions

- [ ] Implement limits and colimits
- [ ] Add adjunctions and universal constructions
- [ ] Support monads and comonads
- [ ] Build Yoneda, representability, and presheaf basics
- [ ] Add functor categories and standard categorical constructions

## Specialized Categories

- [ ] Introduce monoidal categories and related structure
- [ ] Add abelian-category infrastructure for later homological algebra
