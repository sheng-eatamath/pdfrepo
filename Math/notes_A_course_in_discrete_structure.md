# Sets, Function and Relations

## Sets

Def 1.1. A *set* is an unordered collections of objects.

Def 1.2. The *cardinality* of a set $A$ is the number of objects in $A$.

Def 1.3. ( Equality ). Set S and T are *equal* if S and T contains same elements.

Def 1.4. ( Subsets ). A set S is a *subset* of set T if every elements in S are in T.

Def 1.5. ( Set operations ). Given set S and T, define following operations:
- *Power Sets*: P(S) is all set subsets of S.
- *Cartesian Product*: $S x T = {(s, t) | s \subset S, t \subset T}$
- *Union*
- *Intersection*
- *Difference*
- *Complements*

Def 1.6. ( $S^n$ ). The product of n copies of S.

Def 1.7. ( $S^*$ ). The union of $S^n$, where n from 0 to N.

For example, $\{0,1\}^n$ is set of n bits string.

Note: the word `collection` in the set definition needs to be well behaviors. 

## Relations

Def 1.8. ( Relations ). A *relation* on sets S and T is a subset of S x T.

Def 1.9. A relation R on set S is: 
- ( Reflexive ). If (x, x) belongs R for all x belongs to S.
- ( Symmetric ). If whenever (x, y) belongs to R, (y, x) belongs to R.
- ( Transitive ). If whenever (x, y), (y, z) belongs to R, then (x, z) belongs to R.

For examples: 
- `<=` is reflective, while `<` is not.

Theorem 1.1. Let R be a relation over S: 
- R is reflective iff its graph has a self-loop on every node.
- R is symmetric iff in its graph, every edge goes both ways.
- R is transitive iff in its graph, whenever there is path from x to y, there is also
   a direct edge from x to y.

Def 1.10. ( Transitive closure ). The *transitive closure* of a relation R is the smallest
 transitive relation R* such that R is subset of R*.

Theorem 1.2. A relation R is transitive iff R = R*.

Def 1.11. ( Equivalence relations ). A relation R on set S is an equivalence relation if it
 is reflective, symmetric and transitive.

## Functions

Def 1.12. ( Function ). A *function* is a mapping from elements in set S to elements in 
 set T. Formally, f is a relation on S and T such that for each s, there exists a unique
 t such that (s, t) belongs to R.

Def. 1.13. ( Injection ). A function is *injective* if whenever s!=s', fs != fs'.

Def. 1.14. ( Surjection ). For every t, there exist some s, f(s) = t. 

Def. 1.15. ( Bijection ). one-to-one correspondence.

We can re-define some set definition by functions.

[function](./function.png)

Theorem 1.3. Given injective maps, f: S->T and g: T->S, we can construct bijection f:S->T.

Def. 1.16. ( Countable ). S is countable if `S<N^+`. 

Theorem 1.4. Positive rational numbers set is countable. 

# Proof and Induction

# Finite Automata

