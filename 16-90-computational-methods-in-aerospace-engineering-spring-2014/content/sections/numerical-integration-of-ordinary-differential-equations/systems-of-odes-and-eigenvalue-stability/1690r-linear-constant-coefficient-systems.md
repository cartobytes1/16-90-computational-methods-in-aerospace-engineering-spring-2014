---
course_id: 16-90-computational-methods-in-aerospace-engineering-spring-2014
layout: course_section
parent_title: 1.6 Systems of ODE's and Eigenvalue Stability
title: 1.6 Systems of ODE's and Eigenvalue Stability
type: course
uid: e8dbfb2204cb6fc4431e0b32e5ea65da

---

*   [<Systems of ODE's and Eigenvalue Stability]({{< baseurl >}}/sections/numerical-integration-of-ordinary-differential-equations/systems-of-odes-and-eigenvalue-stability)
*   [1.6.1Nonlinear Systems]({{< baseurl >}}/sections/numerical-integration-of-ordinary-differential-equations/systems-of-odes-and-eigenvalue-stability)
*   [1.6.2Linear Constant Coefficient Systems]({{< baseurl >}}/sections/numerical-integration-of-ordinary-differential-equations/systems-of-odes-and-eigenvalue-stability/1690r-linear-constant-coefficient-systems)
*   [1.6.3Eigenvalue Stability for a Linear ODE]({{< baseurl >}}/sections/numerical-integration-of-ordinary-differential-equations/systems-of-odes-and-eigenvalue-stability/1690r-eigenvalue-stability-for-a-linear-ode)
*   [1.6.4Imaginary Eigenvalues]({{< baseurl >}}/sections/numerical-integration-of-ordinary-differential-equations/systems-of-odes-and-eigenvalue-stability/1690r-imaginary-eigenvalues)
*   [\>Eigenvalue Stability for a Linear ODE]({{< baseurl >}}/sections/numerical-integration-of-ordinary-differential-equations/systems-of-odes-and-eigenvalue-stability/1690r-eigenvalue-stability-for-a-linear-ode)

1.6.2 Linear Constant Coefficient Systems
-----------------------------------------

[Measurable Outcome 1.1]({{< baseurl >}}/sections/measurable-outcome-index/#anchorMO11), [Measurable Outcome 1.2]({{< baseurl >}}/sections/measurable-outcome-index/#anchorMO12), [Measurable Outcome 1.3]({{< baseurl >}}/sections/measurable-outcome-index/#anchorMO13), [Measurable Outcome 1.4]({{< baseurl >}}/sections/measurable-outcome-index/#anchorMO14), [Measurable Outcome 1.9]({{< baseurl >}}/sections/measurable-outcome-index/#anchorMO19)

The analysis of numerical methods applied to linear, constant coefficient systems can provide significant insight into the behavior of numerical methods for nonlinear problems. Consider the following problem,

| \\\[u\_ t = A u, \\label{equ:ODElinear\_ sys}\\\] | (1.90) 

where \\(A\\) is a \\(d \\times d\\) matrix. Assuming that a complete set of eigenvectors exists, the matrix \\(A\\) can be decomposed as,

| \\\[A = R\\Lambda R^{-1}, \\qquad \\Lambda = \\mbox{diag}(\\lambda \_1, \\lambda \_2, \\cdots , \\lambda \_ d), \\qquad R = \\left(\\begin{array}{c&#124;c&#124;c&#124;c&#124;c}r\_1 & r\_2 & r\_3 & \\cdots & r\_ d \\\\ \\end{array}\\right) \\label{equ:eigen}\\\] | (1.91) 

The solution to Equation [1.90](javascript: void(0)) can be derived as follows,

| &nbsp; | \\(\\displaystyle u\_ t\\) | \\(\\displaystyle =\\) | \\(\\displaystyle A u\\) | &nbsp; | (1.92) |
| &nbsp; | \\(\\displaystyle u\_ t\\) | \\(\\displaystyle =\\) | \\(\\displaystyle R\\Lambda R^{-1} u\\) | &nbsp; | (1.93) |
| &nbsp; | \\(\\displaystyle R^{-1} u\_ t\\) | \\(\\displaystyle =\\) | \\(\\displaystyle \\Lambda R^{-1} u\\) | &nbsp; | (1.94) 

Then, defining \\(w = R^{-1} u\\),

| \\\[w\_ t = \\Lambda w.\\\] | (1.95) 

Since \\(\\Lambda\\) is a diagonal matrix, this system of equations is actually uncoupled from each other, so that each of the eigenmodes has its own independent evolution equation,

| \\\[(w\_ j)\_ t = \\lambda \_ j w\_ j, \\qquad \\mbox{for each } j = 1 \\mbox{ to } d\\\] | (1.96) 

Since each of the eigenmodes has a solution \\(w\_ j(t) = w\_ j(0)\\exp (\\lambda \_ j t)\\), then the solution for \\(u(t)\\) can be written as,

| \\\[u(t) = \\sum \_{j=1}^ d w\_ j(0) r\_ j e^{\\lambda \_ j t}. \\label{equ:ODElinear\_ sys\_ solution}\\\] | (1.97) 

Note that the eigenvalues are in general complex, \\(\\lambda \_ j = {\\lambda \_ j}\_ r + i {\\lambda \_ j}\_ i\\). The imaginary part of the eigenvalues determines the frequency of oscillations, and the real part of the eigenvalues determines the growth or decay rate. Specifically,

| \\\[e^{\\lambda t} = e^{(\\lambda \_ r + i \\lambda \_ i)t} = \\left(\\cos \\lambda \_ i t + i\\sin \\lambda \_ i t\\right) e^{ \\lambda \_ r t}.\\\] | (1.98) 

Thus, when \\(\\lambda \_ r > 0\\), the solution will grow unbounded as \\(t \\rightarrow \\infty\\).

BackSystems of ODE's and Eigenvalue Stability ContinueEigenvalue Stability for a Linear ODE