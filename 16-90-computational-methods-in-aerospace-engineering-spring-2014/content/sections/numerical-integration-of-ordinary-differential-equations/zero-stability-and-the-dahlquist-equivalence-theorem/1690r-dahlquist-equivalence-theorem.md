---
course_id: 16-90-computational-methods-in-aerospace-engineering-spring-2014
layout: course_section
parent_title: 1.5 Zero Stability and the Dahlquist Equivalence Theorem
title: 1.5 Zero Stability and the Dahlquist Equivalence Theorem
type: course
uid: e726e961fd269620907a1248b173744d

---

*   [<Stability]({{< baseurl >}}/sections/numerical-integration-of-ordinary-differential-equations/zero-stability-and-the-dahlquist-equivalence-theorem/1690r-stability)
*   [1.5.1Consistency]({{< baseurl >}}/sections/numerical-integration-of-ordinary-differential-equations/zero-stability-and-the-dahlquist-equivalence-theorem)
*   [1.5.2Stability]({{< baseurl >}}/sections/numerical-integration-of-ordinary-differential-equations/zero-stability-and-the-dahlquist-equivalence-theorem/1690r-stability)
*   [1.5.3Dahlquist Equivalence Theorem]({{< baseurl >}}/sections/numerical-integration-of-ordinary-differential-equations/zero-stability-and-the-dahlquist-equivalence-theorem/1690r-dahlquist-equivalence-theorem)
*   [\>Systems of ODE's and Eigenvalue Stability]({{< baseurl >}}/sections/numerical-integration-of-ordinary-differential-equations/systems-of-odes-and-eigenvalue-stability)

1.5.3 Dahlquist Equivalence Theorem
-----------------------------------

[Measurable Outcome 1.7]({{< baseurl >}}/sections/measurable-outcome-index/#anchorMO17), [Measurable Outcome 1.8]({{< baseurl >}}/sections/measurable-outcome-index/#anchorMO18), [Measurable Outcome 1.9]({{< baseurl >}}/sections/measurable-outcome-index/#anchorMO19), [Measurable Outcome 1.10]({{< baseurl >}}/sections/measurable-outcome-index/#anchorMO110)

In order for a multi-step method to be convergent (as described in Section [1.4.2]({{< baseurl >}}/sections/numerical-integration-of-ordinary-differential-equations/convergence/1690r-convergence-of-numerical-methods)), two conditions must be met:

**Consistency**: In the limit of \\({\\Delta t}\\rightarrow 0\\), the method must be a consistent discretization of the ordinary differential equation.

**Stability** In the limit of \\({\\Delta t}\\rightarrow 0\\), the method must not have solutions that can grow unbounded as \\(n = T/{\\Delta t}\\rightarrow \\infty\\).

The Dahlquist Equivalence Theorem in fact guarantees that a consistent and stable multi-step method is convergent, and vice-versa:

Dahlquist Equivalence Theorem
-----------------------------

A multi-step method is convergent if and only if it is consistent and stable.

**Exercise** The numerical scheme defined by the equation \\(v^{n+1} + 4v^ n -5v^{n-1} = 4\\Delta t f^ n + 2\\Delta t f^{n-1}\\) is

Exercise 1

 zero stable, not consistent, convergent

 zero stable, consistent, convergent

 not zero stable, consistent, not convergent

 not zero stable, not consistent, not convergent

CheckShow Answer

Answer: The method is consistent, but not zero stable. Since it is not zero stable, the Dahlquist equivalence theorem tells us that the method is not convergent.

BackStability ContinueSystems of ODE's and Eigenvalue Stability