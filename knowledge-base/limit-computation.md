# Limit Computation — Working Reference

This page summarizes methods discussed so far. Reconcile it with the teacher's source notes as the course progresses.

## First step: direct substitution
Substitute the approach value when permitted, then classify the result. An indeterminate form is not an answer; it signals that further analysis is needed.

## Common indeterminate forms discussed
| Form | Methods to consider |
|---|---|
| 0/0 | Factorization, cancellation, rationalization; later, equivalent infinitesimals when valid |
| infinity/infinity | Divide by the highest relevant power; compare growth rates |
| infinity minus infinity | Common denominator, conjugate/rationalization, algebraic rearrangement, reciprocal substitution when suitable |
| 0 times infinity | Rewrite as a quotient, then classify again |

## Special cases and necessary-condition reasoning
1. For a two-sided limit to exist, the left and right limits must both exist and be equal.
2. For a quotient of polynomials as x tends to positive or negative infinity, a finite nonzero limit requires equal polynomial degrees.
3. If a quotient tends to a finite nonzero value while its denominator tends to zero, its numerator must also tend to zero.
4. If one factor grows without bound in magnitude while the product tends to a finite value, the other factor must tend to zero, under the corresponding limit assumptions.
5. A bounded function multiplied by a function tending to zero has product tending to zero.

## Cautions
- A nonzero constant divided by a quantity tending to zero is not an indeterminate form; inspect one-sided signs.
- Equal polynomial degrees are a condition for a finite nonzero limit in the polynomial-quotient setting, not a universal shortcut for arbitrary expressions.
- Do not replace terms by equivalent infinitesimals inside sums or differences without checking the required conditions.
