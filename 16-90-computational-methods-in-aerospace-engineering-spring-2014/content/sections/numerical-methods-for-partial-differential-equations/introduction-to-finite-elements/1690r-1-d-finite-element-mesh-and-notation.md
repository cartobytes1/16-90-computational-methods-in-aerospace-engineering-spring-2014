---
course_id: 16-90-computational-methods-in-aerospace-engineering-spring-2014
layout: course_section
parent_title: 2.9 Introduction to Finite Elements
title: 2.9 Introduction to Finite Elements
type: course
uid: cc8eecdb7e89e1dbce162f90e5ff68fb

---

*   [<Introduction to Finite Elements]({{< baseurl >}}/sections/numerical-methods-for-partial-differential-equations/introduction-to-finite-elements)
*   [2.9.1Motivation]({{< baseurl >}}/sections/numerical-methods-for-partial-differential-equations/introduction-to-finite-elements)
*   [2.9.21-D Finite Element Mesh and Notation]({{< baseurl >}}/sections/numerical-methods-for-partial-differential-equations/introduction-to-finite-elements/1690r-1-d-finite-element-mesh-and-notation)
*   [2.9.31-D Linear Elements and the Nodal Basis]({{< baseurl >}}/sections/numerical-methods-for-partial-differential-equations/introduction-to-finite-elements/1690r-1-d-linear-elements-and-the-nodal-basis)
*   [2.9.4Weak Form of the Weighted Residual]({{< baseurl >}}/sections/numerical-methods-for-partial-differential-equations/introduction-to-finite-elements/1690r-weak-form-of-the-weighted-residual)
*   [2.9.5Calculation of the Finite Element Weighted Residual]({{< baseurl >}}/sections/numerical-methods-for-partial-differential-equations/introduction-to-finite-elements/1690r-calculation-of-the-finite-element-weighted-residual)
*   [2.9.6Calculation of the Stiffness Matrix]({{< baseurl >}}/sections/numerical-methods-for-partial-differential-equations/introduction-to-finite-elements/1690r-calculation-of-the-stiffness-matrix)
*   [\>1-D Linear Elements and the Nodal Basis]({{< baseurl >}}/sections/numerical-methods-for-partial-differential-equations/introduction-to-finite-elements/1690r-1-d-linear-elements-and-the-nodal-basis)

2.9.2 1-D Finite Element Mesh and Notation
------------------------------------------

[Measurable Outcome 2.16]({{< baseurl >}}/sections/measurable-outcome-index/#anchorMO216)

Consider a mesh of one-dimensional elements as shown in Figure [2.35](/coursemedia/16-90-computational-methods-in-aerospace-engineering-spring-2014/407bbf27512174478f129171055e98fc_onedFEMmesh.png).

![The figure shows a horizontal line with evenly spaced nodes and the span between two neighboring nodes labeled as a interger of j.](/coursemedia/16-90-computational-methods-in-aerospace-engineering-spring-2014/407bbf27512174478f129171055e98fc_onedFEMmesh.png)

**Figure 2.35**: Mesh and notation for one-dimensional finite element method.

As shown in the figure, element \\(j\\) is the region from \\(x\_{j} \\leq x \\leq x\_{j+1}\\). Note, each element can have its own length,

| \\\[\\Delta x\_ j \\equiv x\_{j+1} - x\_ j.\\\] | (2.198) 

BackIntroduction to Finite Elements Continue1-D Linear Elements and the Nodal Basis