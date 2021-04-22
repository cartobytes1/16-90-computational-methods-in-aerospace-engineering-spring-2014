---
course_id: 16-90-computational-methods-in-aerospace-engineering-spring-2014
layout: course_section
parent_title: 1.2 Discretizing ODEs
title: 1.2 Discretizing ODEs
type: course
uid: ae250ef953d178da8810f88b0aaa6408

---

*   [<The Forward Euler Method]({{< baseurl >}}/sections/numerical-integration-of-ordinary-differential-equations/discretizing-odes/1690r-the-forward-euler-method)
*   [1.2.1First-Order ODEs]({{< baseurl >}}/sections/numerical-integration-of-ordinary-differential-equations/discretizing-odes)
*   [1.2.2An Example of First Order ODE]({{< baseurl >}}/sections/numerical-integration-of-ordinary-differential-equations/discretizing-odes/1690r-an-example-of-first-order-ode)
*   [1.2.3Discretization]({{< baseurl >}}/sections/numerical-integration-of-ordinary-differential-equations/discretizing-odes/1690r-discretization)
*   [1.2.4The Forward Euler Method]({{< baseurl >}}/sections/numerical-integration-of-ordinary-differential-equations/discretizing-odes/1690r-the-forward-euler-method)
*   [1.2.5The Midpoint Method]({{< baseurl >}}/sections/numerical-integration-of-ordinary-differential-equations/discretizing-odes/1690r-the-midpoint-method)
*   [\>Order of Accuracy]({{< baseurl >}}/sections/numerical-integration-of-ordinary-differential-equations/order-of-accuracy)

1.2.5 The Midpoint Method
-------------------------

[Measurable Outcome 1.5]({{< baseurl >}}/sections/measurable-outcome-index/#anchorMO15), [Measurable Outcome 1.6]({{< baseurl >}}/sections/measurable-outcome-index/#anchorMO16)

Now, let's look at another integration method known as the midpoint method. For this method, we will use a slightly different point of view to derive it. Specifically, let's start from the definition of a derivative,

| \\\[u\_ t(t) = \\lim \_{{\\Delta t}\\rightarrow 0} \\frac{u(t+{\\Delta t}) - u(t-{\\Delta t})}{2{\\Delta t}}\\\] | (1.31) 

Now, instead of taking the limit, assume a finite \\({\\Delta t}\\). Then, we end up with an approximation to \\(du/dt\\):

| \\\[u\_ t(t) \\approx \\frac{u(t+{\\Delta t}) - u(t-{\\Delta t})}{2{\\Delta t}} \\qquad \\mbox{for small } {\\Delta t}\\\] | (1.32) 

Then, we can re-arrange this to the following estimate for \\(u(t+{\\Delta t})\\),

| \\\[u(t+{\\Delta t}) \\approx u(t-{\\Delta t}) + 2{\\Delta t}u\_ t(t) \\label{equ:mp\_ approx}\\\] | (1.33) 

Then, following the same process as in the forward Euler method, we arrive at the midpoint method,

| \\\[v^{n+1} = v^{n-1} + 2{\\Delta t}f(v^ n, t^ n) \\qquad \\mbox{for} \\qquad n \\geq 1. \\label{equ:mp}\\\] | (1.34) 

However, because of the use of \\(v^{n-1}\\), the midpont method can only be applied for \\(n \\geq 1\\). Thus, for the first timestep a different numerical method must be applied (e.g. the forward Euler method).

We will now solve the falling ice problem using the midpoint method. Using the same values of \\({\\Delta t}\\) and \\(T\\) as before, the results are shown in Figure [1.3](/coursemedia/16-90-computational-methods-in-aerospace-engineering-spring-2014/aabcb5a56cc7a1aabf4b4d66ea7116d6_ice_mp.png).

![This figure shows three bar graphs that represent the behavior of velocity, Reynolds number, and drag coefficient as a function of time for an ice particle falling through the atmosphere. This simulation was performed using the midpoint method with Δt=0.25sec.](/coursemedia/16-90-computational-methods-in-aerospace-engineering-spring-2014/aabcb5a56cc7a1aabf4b4d66ea7116d6_ice_mp.png)

**Figure 1.3**: Behavior of velocity, Reynolds number, and drag coefficient as a function of time for an ice particle falling through the atmosphere. Simulation performed using the midpoint method with \\({\\Delta t}= 0.25\\, sec\\).

Clearly, something has gone wrong here as the results show non-physical oscillations. Perhaps the oscillations will disappear if we take a smaller timestep. To test out this hypothesis, let's re-run the midpoint method with \\({\\Delta t}= 0.025\\, sec\\) which is one-tenth the previous timestep. Those results are shown in Figure [1.4](/coursemedia/16-90-computational-methods-in-aerospace-engineering-spring-2014/415431b8629eb6a521b83d83f0b2d5ed_ice_mp_smallDt.png). Unfortunately, while the results are better, the oscillations are clearly still present. For this problem, clearly the forward Euler method is a better choice than the midpoint method. We will see why this has happened in a few lectures.

![This figure shows three bar graphs that represent the Behavior of velocity, Reynolds number, and drag coefficient as a function of time for an ice particle falling through the atmosphere. Simulation performed using the midpoint method with Δt=0.025sec.](/coursemedia/16-90-computational-methods-in-aerospace-engineering-spring-2014/415431b8629eb6a521b83d83f0b2d5ed_ice_mp_smallDt.png)

**Figure 1.4**: Behavior of velocity, Reynolds number, and drag coefficient as a function of time for an ice particle falling through the atmosphere. Simulation performed using the midpoint method with \\({\\Delta t}= 0.025\\, sec\\).

BackThe Forward Euler Method ContinueOrder of Accuracy