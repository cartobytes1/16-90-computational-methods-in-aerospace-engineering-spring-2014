---
course_id: 16-90-computational-methods-in-aerospace-engineering-spring-2014
layout: course_section
parent_title: 2.11 The Finite Element Method for Two-Dimensional Diffusion
title: 2.11 The Finite Element Method for Two-Dimensional Diffusion
type: course
uid: cd2d971fe847d266f0b1555caab639d4

---

*   [<Construction of the Stiffness Matrix]({{< baseurl >}}/sections/numerical-methods-for-partial-differential-equations/the-finite-element-method-for-two-dimensional-diffusion/1690r-construction-of-the-stiffness-matrix)
*   [2.11.1Overview]({{< baseurl >}}/sections/numerical-methods-for-partial-differential-equations/the-finite-element-method-for-two-dimensional-diffusion)
*   [2.11.2Reference Element and Linear Elements]({{< baseurl >}}/sections/numerical-methods-for-partial-differential-equations/the-finite-element-method-for-two-dimensional-diffusion/1690r-reference-element-and-linear-elements)
*   [2.11.3Differentiation using the Reference Element]({{< baseurl >}}/sections/numerical-methods-for-partial-differential-equations/the-finite-element-method-for-two-dimensional-diffusion/1690r-differentiation-using-the-reference-element)
*   [2.11.4Construction of the Stiffness Matrix]({{< baseurl >}}/sections/numerical-methods-for-partial-differential-equations/the-finite-element-method-for-two-dimensional-diffusion/1690r-construction-of-the-stiffness-matrix)
*   [2.11.5Integration in the Reference Element]({{< baseurl >}}/sections/numerical-methods-for-partial-differential-equations/the-finite-element-method-for-two-dimensional-diffusion/1690r-integration-in-the-reference-element)
*   [\>Probabilistic Methods and Optimization]({{< baseurl >}}/sections/probabilistic-methods-and-optimization)

2.11.5 Integration in the Reference Element
-------------------------------------------

[Measurable Outcome 2.20]({{< baseurl >}}/sections/measurable-outcome-index/#anchorMO220)

The reference element can also be used to evaluate integrals. For example, consider the evaluation of the forcing function integral within an element:

| \\\[\\int \_{\\delta \\Omega \_ k} w(\\vec{x})\\, f(\\vec{x})\\, dA.\\\] | (2.285) 

In transforming the integral from \\((x,y)\\) to \\((\\xi \_1,\\xi \_2)\\), the differential area of integration must be transformed using the following result:

| \\\[dA = dx\\, dy = J d\\xi \_1\\, d\\xi \_2 = J\\, dA\_{\\xi }. \\label{equ:Ax\_ to\_ Axi}\\\] | (2.286) 

Thus, the integrals can now be evaluated in reference element space,

| \\\[\\int \_{\\Omega \_{\\xi }} w(\\vec{x}(\\vec{\\xi }))\\, f(\\vec{x}(\\vec{\\xi }))\\, J dA\_{\\xi }.\\\] | (2.287) 

BackConstruction of the Stiffness Matrix ContinueProbabilistic Methods and Optimization