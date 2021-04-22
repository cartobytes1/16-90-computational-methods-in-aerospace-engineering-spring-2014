---
course_id: 16-90-computational-methods-in-aerospace-engineering-spring-2014
layout: course_section
parent_title: 2.2 Partial Differential Equations
title: 2.2 Partial Differential Equations
type: course
uid: e6408661a4be8cfb3204ee1581c8dff1

---

*   [<Diffusion]({{< baseurl >}}/sections/numerical-methods-for-partial-differential-equations/partial-differential-equations/1690r-diffusion)
*   [2.2.1Conservation Laws in Integral and Differential Form]({{< baseurl >}}/sections/numerical-methods-for-partial-differential-equations/partial-differential-equations)
*   [2.2.2One-Dimensional Burgers Equation]({{< baseurl >}}/sections/numerical-methods-for-partial-differential-equations/partial-differential-equations/1690r-one-dimensional-burgers-equation)
*   [2.2.3Convection]({{< baseurl >}}/sections/numerical-methods-for-partial-differential-equations/partial-differential-equations/1690r-convection)
*   [2.2.4Characteristics for One-Dimensional Burgers Equation]({{< baseurl >}}/sections/numerical-methods-for-partial-differential-equations/partial-differential-equations/1690r-characteristics-for-one-dimensional-burgers-equation)
*   [2.2.5Diffusion]({{< baseurl >}}/sections/numerical-methods-for-partial-differential-equations/partial-differential-equations/1690r-diffusion)
*   [2.2.6Convection-Diffusion]({{< baseurl >}}/sections/numerical-methods-for-partial-differential-equations/partial-differential-equations/1690r-convection-diffusion)
*   [2.2.7Linear Elasticity]({{< baseurl >}}/sections/numerical-methods-for-partial-differential-equations/partial-differential-equations/1690r-linear-elasticity)
*   [\>Linear Elasticity]({{< baseurl >}}/sections/numerical-methods-for-partial-differential-equations/partial-differential-equations/1690r-linear-elasticity)

2.2.6 Convection-Diffusion
--------------------------

[Measurable Outcome 2.1]({{< baseurl >}}/sections/measurable-outcome-index/#anchorMO21), [Measurable Outcome 2.2]({{< baseurl >}}/sections/measurable-outcome-index/#anchorMO22), [Measurable Outcome 2.5]({{< baseurl >}}/sections/measurable-outcome-index/#anchorMO25)

In practice, both convection and diffusion are important phenomenon governing fluid dynamics. While convection may be the dominant transport mechanism in most of a flow, accounting for diffusion near solid boundaries may be essential for accurately computing engineering quantities such as drag or heat transfer. The convection-diffusion equation is derived from a general conservation law including both convective and diffusive fluxes. In differential form, the convection-diffusion equation is

| \\\[\\dfrac {\\partial U}{\\partial t} + \\vec{v} \\cdot \\nabla U - \\nabla \\cdot ( \\mu \\nabla U ) = S.\\\] | (2.36) 

The convection-diffusion equation arises in many engineering applications ranging from heat transfer to statistical mechanics (and even in finance!). Solutions of the convection-diffusion equation exhibit behavior which is the combined effect of both convection and diffusion. A key question which naturally arises is how significant are the relative effects of convection and diffusion. This is governed by the non-dimensional Peclet number (in aerodynamics applications, the Reynolds number is equivalent).

| \\\[Pe = \\frac{&#124;\\vec{v}&#124; L}{\\mu }\\\] | (2.37) 

where \\(L\\) is a characteristic length scale for the problem of interest. When \\(Pe \\ll 1\\) diffusion effects are dominant, and convection plays a relatively small role. On the other hand, when \\(Pe \\gg 1\\) convection is the dominant transport mechanism. Figures [2.5](/coursemedia/16-90-computational-methods-in-aerospace-engineering-spring-2014/4bb6da2bf7f7caf53f5f5dab915d31f7_convdiffpe10.png), [2.6](/coursemedia/16-90-computational-methods-in-aerospace-engineering-spring-2014/15190016438f73a0a57edc9c90a9cc06_convdiffpe100.png), [2.7](/coursemedia/16-90-computational-methods-in-aerospace-engineering-spring-2014/d3353a2e60ccec444c2d08541d8ebd5a_convdiffpe1000.png) show solutions for the one-dimensional convection-diffusion problem with Peclet numbers \\(10, 100\\) and \\(1000\\) (\\(\\vec{v}=1\\) is fixed). As the Peclet number increases the solution of the convection-diffusion problem approaches that of the pure convection problem.

![The graph shows the peaks (t=0, t=1) from the convection-diffusion equation at Pe=10.](/coursemedia/16-90-computational-methods-in-aerospace-engineering-spring-2014/4bb6da2bf7f7caf53f5f5dab915d31f7_convdiffpe10.png)

**Figure 2.5**: One-dimensional convection-diffusion problem, \\(Pe=10\\)

![The graph shows the peaks (t=0, t=1) from the convection-diffusion equation at Pe=100.](/coursemedia/16-90-computational-methods-in-aerospace-engineering-spring-2014/15190016438f73a0a57edc9c90a9cc06_convdiffpe100.png)

**Figure 2.6**: One-dimensional convection-diffusion problem, \\(Pe=100\\)

![The graph shows the peaks (t=0, t=1) from the convection-diffusion equation at Pe=1000.](/coursemedia/16-90-computational-methods-in-aerospace-engineering-spring-2014/d3353a2e60ccec444c2d08541d8ebd5a_convdiffpe1000.png)

**Figure 2.7**: One-dimensional convection-diffusion problem, \\(Pe=1000\\)

BackDiffusion ContinueLinear Elasticity