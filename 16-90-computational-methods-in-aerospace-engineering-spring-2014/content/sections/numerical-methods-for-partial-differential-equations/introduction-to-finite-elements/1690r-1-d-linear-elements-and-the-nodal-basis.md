---
course_id: 16-90-computational-methods-in-aerospace-engineering-spring-2014
layout: course_section
parent_title: 2.9 Introduction to Finite Elements
title: 2.9 Introduction to Finite Elements
type: course
uid: 03bb574d085a69950b353c2a70257228

---

*   [<1-D Finite Element Mesh and Notation]({{< baseurl >}}/sections/numerical-methods-for-partial-differential-equations/introduction-to-finite-elements/1690r-1-d-finite-element-mesh-and-notation)
*   [2.9.1Motivation]({{< baseurl >}}/sections/numerical-methods-for-partial-differential-equations/introduction-to-finite-elements)
*   [2.9.21-D Finite Element Mesh and Notation]({{< baseurl >}}/sections/numerical-methods-for-partial-differential-equations/introduction-to-finite-elements/1690r-1-d-finite-element-mesh-and-notation)
*   [2.9.31-D Linear Elements and the Nodal Basis]({{< baseurl >}}/sections/numerical-methods-for-partial-differential-equations/introduction-to-finite-elements/1690r-1-d-linear-elements-and-the-nodal-basis)
*   [2.9.4Weak Form of the Weighted Residual]({{< baseurl >}}/sections/numerical-methods-for-partial-differential-equations/introduction-to-finite-elements/1690r-weak-form-of-the-weighted-residual)
*   [2.9.5Calculation of the Finite Element Weighted Residual]({{< baseurl >}}/sections/numerical-methods-for-partial-differential-equations/introduction-to-finite-elements/1690r-calculation-of-the-finite-element-weighted-residual)
*   [2.9.6Calculation of the Stiffness Matrix]({{< baseurl >}}/sections/numerical-methods-for-partial-differential-equations/introduction-to-finite-elements/1690r-calculation-of-the-stiffness-matrix)
*   [\>Weak Form of the Weighted Residual]({{< baseurl >}}/sections/numerical-methods-for-partial-differential-equations/introduction-to-finite-elements/1690r-weak-form-of-the-weighted-residual)

2.9.3 1-D Linear Elements and the Nodal Basis
---------------------------------------------

[Measurable Outcome 2.16]({{< baseurl >}}/sections/measurable-outcome-index/#anchorMO216)

The finite element method typically uses polynomial functions inside each element. Furthermore, the approximation is usually required to be continuous from element to element. The simplest element which permits continuous functions would be to assume linear variations of \\(x\\) inside each element. This type of element is called a linear element (not too surprisingly). Using linear finite elements, a sample solution might look like that shown in Figure [2.36](/coursemedia/16-90-computational-methods-in-aerospace-engineering-spring-2014/323c3e91af36839b9733a3e877688b1f_linelem_sample.png).

![The graph shows a single line that steadily increases and then decreases representing the linear element solution on a mesh with a constant element size.](/coursemedia/16-90-computational-methods-in-aerospace-engineering-spring-2014/323c3e91af36839b9733a3e877688b1f_linelem_sample.png)

**Figure 2.36**: A linear element solution on a mesh with constant element size, \\(\\Delta x\_ j = 0.2\\).

A linear function can be described by two degrees of freedom. For example, a linear function within an element could be uniquely determined by the following combinations of information:

*   the function values at the two endpoints (i.e., nodes) of the element,
    
*   the function value at some point in the element and the function slope in the element.
    

For a mesh composed of \\(N\\) elements, a total of \\(N+1\\) degrees of freedom exist to describe a continuous, piecewise linear function. If the approximation were allowed to be discontinuous from element to element, then there would be \\(2N\\) degrees of freedom but continuity removes \\(N-1\\) degrees of freedom (one per internal node). Thus, the degrees of freedom to describe a solution over a domain discretized into \\(N\\) linear elements could be (among other choices),

*   the values of the function at the \\(N+1\\) nodes,
    
*   the value of the function at some point in the domain and the slopes in the \\(N\\) elements.
    

The first choice is the most common and leads to what is known as the **nodal basis**.

We now derive the nodal basis functions (i.e., the \\(\\phi \_ j(x)\\)) for linear elements. As discussed above, for \\(N\\) linear elements we have \\(N+1\\) degrees of freedom and therefore \\(N+1\\) basis functions, i.e.,

| \\\[\\tilde{T}(x) = \\sum \_{j=1}^{N+1} a\_ j \\phi \_ j(x), \\label{equ:linelem\_ expansion}\\\] | (2.199) 

where \\(a\_ j\\) are the \\(N+1\\) degrees of freedom. For a nodal basis, we choose \\(a\_ j = \\tilde{T}(x\_ j)\\). Substituting this into Equation ([2.199](javascript: void(0))) gives,

| \\\[\\tilde{T}(x) = \\sum \_{j=1}^{N+1} \\tilde{T}(x\_ j) \\phi \_ j(x).\\\] | (2.200) 

Now, evaluating this expansion at node \\(i\\),

| &nbsp; | \\(\\displaystyle \\tilde{T}(x\_ i)\\) | \\(\\displaystyle =\\) | \\(\\displaystyle \\sum \_{j=1}^{N+1} \\tilde{T}(x\_ j) \\phi \_ j(x\_ i),\\) | &nbsp; | (2.201) |
| &nbsp; | \\(\\displaystyle \\Rightarrow \\phi \_ j(x\_ i)\\) | \\(\\displaystyle =\\) | \\(\\displaystyle \\left\\{ \\begin{array}{cl} 1, & \\mbox{if } i = j, \\\\ 0, & \\mbox{if } i \\neq j. \\end{array}\\right.\\) | &nbsp; | (2.202) 

Finally, since the solutions vary linearly over each element, this means that \\(\\phi \_ j(x)\\) is zero for \\(x < x\_{j-1}\\) and \\(x > x\_{j+1}\\), increases linearly from zero to one from \\(x\_{j-1}\\) to \\(x\_{j}\\), and decreases linearly back to zero at \\(x\_{j+1}\\). \\(\\phi \_ j(x)\\) is shown in Figure [2.37](/coursemedia/16-90-computational-methods-in-aerospace-engineering-spring-2014/80400448ffd69327116c3a9c3fc923ac_linelem_phi.png). The, specific function is,

| \\\[\\phi \_ j(x) = \\left\\{ \\begin{array}{cl} 0, & \\mbox{for } x < x\_{j-1}, \\\\\[0.1in\] \\frac{x-x\_{j-1}}{\\Delta x\_{j-1}}, & \\mbox{for } x\_{j-1} < x < x\_{j},\\\\\[0.1in\] \\frac{x\_{j+1} -x}{\\Delta x\_{j}}, & \\mbox{for } x\_{j} < x < x\_{j+1},\\\\\[0.1in\] 0, & \\mbox{for } x > x\_{j+1}. \\end{array}\\right. \\label{equ:phi\_ linear}\\\] | (2.203) 

![The figure is similar to Figure 2.35, with a horizontal line with nodes and integers, but the center node is increased on the y-axis to 1 that makes a sharp peak in the line. ](/coursemedia/16-90-computational-methods-in-aerospace-engineering-spring-2014/80400448ffd69327116c3a9c3fc923ac_linelem_phi.png)

**Figure 2.37**: \\(\\phi \_ j(x)\\) for linear elements using a nodal basis.

Back1-D Finite Element Mesh and Notation ContinueWeak Form of the Weighted Residual