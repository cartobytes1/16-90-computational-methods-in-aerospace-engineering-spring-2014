---
course_id: 16-90-computational-methods-in-aerospace-engineering-spring-2014
layout: course_section
menu:
  leftnav:
    identifier: 876be530ac0533845428281b2b3c5b68
    name: 2.9 Introduction to Finite Elements
    parent: 125c58ac6a345a7cbba8de2d3160cb8b
    weight: 800
parent_title: 'Unit 2: Numerical Methods for Partial Differential Equations'
title: 2.9 Introduction to Finite Elements
type: course
uid: 876be530ac0533845428281b2b3c5b68

---

*   [<Galerkin Method with New Basis]({{< baseurl >}}/sections/numerical-methods-for-partial-differential-equations/method-of-weighted-residuals/1690r-galerkin-method-with-new-basis)
*   [2.9.1Motivation]({{< baseurl >}}/sections/numerical-methods-for-partial-differential-equations/introduction-to-finite-elements)
*   [2.9.21-D Finite Element Mesh and Notation]({{< baseurl >}}/sections/numerical-methods-for-partial-differential-equations/introduction-to-finite-elements/1690r-1-d-finite-element-mesh-and-notation)
*   [2.9.31-D Linear Elements and the Nodal Basis]({{< baseurl >}}/sections/numerical-methods-for-partial-differential-equations/introduction-to-finite-elements/1690r-1-d-linear-elements-and-the-nodal-basis)
*   [2.9.4Weak Form of the Weighted Residual]({{< baseurl >}}/sections/numerical-methods-for-partial-differential-equations/introduction-to-finite-elements/1690r-weak-form-of-the-weighted-residual)
*   [2.9.5Calculation of the Finite Element Weighted Residual]({{< baseurl >}}/sections/numerical-methods-for-partial-differential-equations/introduction-to-finite-elements/1690r-calculation-of-the-finite-element-weighted-residual)
*   [2.9.6Calculation of the Stiffness Matrix]({{< baseurl >}}/sections/numerical-methods-for-partial-differential-equations/introduction-to-finite-elements/1690r-calculation-of-the-stiffness-matrix)
*   [\>1-D Finite Element Mesh and Notation]({{< baseurl >}}/sections/numerical-methods-for-partial-differential-equations/introduction-to-finite-elements/1690r-1-d-finite-element-mesh-and-notation)

2.9.1 Motivation
----------------

In this lecture, we introduce the finite element method (FEM). In its most general form, FEM is based on the method of weighted residuals. The application of the method of weighted residuals as described in Section [2.8.3]({{< baseurl >}}/sections/numerical-methods-for-partial-differential-equations/method-of-weighted-residuals/1690r-the-method-of-weighted-residuals) becomes difficult when the complexity of the problems increases, specifically in multiple dimensions and with varying properties (e.g., varying thermal conductivity in the heat diffusion problem). The heart of the difficulty in these applications is the construction of the weighted residual integrals. For the simple one-dimensional problem discussed in Section [2.8.3]({{< baseurl >}}/sections/numerical-methods-for-partial-differential-equations/method-of-weighted-residuals/1690r-the-method-of-weighted-residuals), these integrals were relatively easy to do. However, the analogous integrals in multiple dimensions with complex geometries are very difficult to evaluate without some additional form of numerical approximation. For example, consider the heat transfer problem shown in Figure [2.33](/coursemedia/16-90-computational-methods-in-aerospace-engineering-spring-2014/30aa9e6844f1625b47ae714b6219da8b_MITprob.png) and imagine the difficulty in constructing a set of functions which satisfy the boundary conditions and then integrating the weighted residuals of these functions over the entire domain.

![The figure spells out MIT using simple rectangles.](/coursemedia/16-90-computational-methods-in-aerospace-engineering-spring-2014/30aa9e6844f1625b47ae714b6219da8b_MITprob.png)

**Figure 2.33**: Heat transfer problem in a complex domain. Temperature at outer boundary is maintained at \\(T\_0\\). Temperature of all of the internal rectangles except one are maintained at \\(T\_1\\), while the remaining internal rectangle is maintained at \\(T\_2\\).

The finite element method offers one approach to approximating the solution and the weighted residual integrals in general situations and, therefore, makes possible the approximation of complex physical problems. The basic idea behind the finite element method is to discretize the domain into small cells (called elements in FEM) and use these elements to approximate the solution and evaluate the weighted residuals (an example mesh can be seen in Figure [2.34](/coursemedia/16-90-computational-methods-in-aerospace-engineering-spring-2014/2d58de59b4a6d363d7fdd31cdddc6461_MITgrid1.png)). Typically, in each element, the solution is approximated using polynomial functions. Then, the weighted residuals are evaluated an element at a time and the resulting system of equations is solved to determine the weighting coefficients on the polynomials in each element.

![This figure has the same rectangles spelling MIT as Figure 2.33, but the background is a complex mesh.](/coursemedia/16-90-computational-methods-in-aerospace-engineering-spring-2014/2d58de59b4a6d363d7fdd31cdddc6461_MITgrid1.png)

**Figure 2.34**: Mesh for heat transfer problem in a complex domain.

To introduce the basic concepts of the finite element method, we will first discuss the one-dimensional case. In future lectures, we will consider multiple dimensions and return to this complex heat transfer problem.

BackGalerkin Method with New Basis Continue1-D Finite Element Mesh and Notation