# Sierpiński–Conway Lambda Notation (SCLN)

The Sierpiński–Conway Lambda Notation (SCLN) is a googologic system that merges Conway’s chained-arrow notation with Sierpiński-style self-iterative hierarchies, extending hyperoperations into transfinite-like levels of the Fast-Growing Hierarchy (FGH) — potentially reaching up to and beyond FΓ₀.

---

## Etymology

The notation honors two mathematicians:  
**Wacław Sierpiński** (Poland) and **John H. Conway** (United Kingdom).  
It unites Sierpiński’s transfinite iterative principles with Conway’s chained-arrow operations to describe extremely large functions beyond standard hyperoperations.

---

## Definition

The lambda operator λ defines a recursive chaining rule based on Conway’s arrow notation:

λ n = n → n → n → ... → n  (n times)

That is, λ n represents Conway’s chained-arrow operation repeated n times, each involving n.

Here →⁽ⁿ⁾ denotes n nested Conway arrows.

---

## Multilambda Operation

Stacking multiple lambdas increases growth dramatically:

λλ n = λ⁽ⁿ⁾(n)

This operation represents self-iteration of λ, applied n times to itself, producing values far beyond the basic λ-notation.

---

## Alphabetic Hierarchy

To generalize, we introduce a family of functions using Greek letters:

ω(n) = λ⁽ⁿ⁾(n)

and extending to multiple variables:

ω(n, m) = ω⁽ᵐ⁾(n)

so that:

ω(n, m, a) = (ω⁽ᵐ⁾(n))⁽ᵃ⁾

Each new argument introduces a meta-iterative layer, compounding the growth rate exponentially beyond the prior.

---

## Alphabetic Escalation

Advancing through the Greek alphabet — from ω to α, β, γ, and so on — each successive letter represents a higher self-iterative degree of the previous one.

Thus, the hierarchy expands indefinitely, forming a transordinal system of hyperoperators, where every Greek letter adds a meta-level of recursion and growth.

---

## Formal Recursive Definition

Let:

f₀(n) = n

and

fₖ₊₁(n) = fₖ(n) →⁽ⁿ⁾ fₖ(n)

Then:

λ n = fₙ(n)  
λλ n = fₙ⁽ⁿ⁾(n)  
ω(n, m) = fₙ⁽ᵐ⁾(n)

and the general alphabetic hierarchy:

Ωₐ(n₁, n₂, …, nₖ) = Ωₐ₋₁⁽ⁿₖ⁾(n₁, n₂, …, nₖ₋₁)

where α is the current Greek index defining the hierarchical depth.

---

## Growth Rate and FGH Position

Approximate mapping between SCLN and the Fast-Growing Hierarchy:

| SCLN Symbol | Equivalent Growth Level | Corresponding FGH Function |
|:-------------|:-------------------------|:----------------------------|
| λ1 | Exponential growth | F₂(n) |
| λ2 | Tetrational growth | F₄(n) |
| λ3 | Pentational growth | F₅(n) |
| λn | n-level hyperoperations | F₍ₙ₊₂₎(n) |
| λλ n | Self-iterating λ | Fω(n) |
| ω(n, m) | Transfinite iteration | Fω·m(n) |
| Alphabetic escalation (ω, α, β, …) | Recursive meta-iterations | up to Fε₀ and FΓ₀ |

Thus, SCLN spans from finite hyperoperations to transordinal and transfinite levels, representing a natural extension of recursive growth systems.

---

## Fast-Growing Hierarchy Position

SCLN can represent functions reaching from Fε₀ up to (and potentially beyond) FΓ₀.

---

## Examples

**1. Simple lambda cases**

λ 2 = 2 → 2 → 2  
λ 3 = 3 → 3 → 3 → 3

**2. Multilambda case**

λλ 3 = λ(λ(λ(3)))

**3. Omega case**

ω(4, 2) = ω(ω(4)) = ω²(4)

---

## Summary

SCLN offers a bridge between finite hyperoperators and transfinite recursion systems, with formal iteration layers that model the escalation of growth far beyond Bowers’, BEAF, or even traditional ordinal-indexed hierarchies.

It serves as a generalized self-iterative notation — concise, elegant, and extendable into ordinal-based recursion theory.

---

© 2025 — Sierpiński–Conway Lambda Notation

