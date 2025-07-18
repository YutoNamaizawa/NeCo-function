# NeCo-function
A holomorphic generating function using Dirichlet eta values to expand π and ln(2)
# NeCo Function and Dirichlet η Series

A holomorphic generating function using Dirichlet η values to express π and ln(2).

## 📘 Overview

We define a new function:
\[
C(a) = \sum_{k=0}^\infty (-a)^k \eta(-k)
\]

This function connects to:
- the Dirichlet L-function at negative integers,
- polylogarithms,
- the digamma function ψ,
- and trigonometric identities.

It gives formulas like:
\[
\int_0^\infty \frac{e^{-t}}{1 + e^{-a t}} dt = 1 - C(a),
\quad
\pi = 8 - 4 \sum_{k=0}^\infty 2^k \eta(-k)
\]

## 📄 Paper
Full write-up: [GitHub.pdf](./GitHub.pdf)

## 🧪 Examples
See `examples/compute_pi_ln2.ipynb` for calculating constants using NeCo.

## 🏷️ Topics
`number-theory` `zeta-function` `eta-function` `pi-formulas` `neco-function`

## 📚 License
MIT
