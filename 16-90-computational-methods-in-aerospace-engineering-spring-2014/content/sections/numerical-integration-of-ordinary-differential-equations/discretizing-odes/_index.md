---
course_id: 16-90-computational-methods-in-aerospace-engineering-spring-2014
layout: course_section
menu:
  leftnav:
    identifier: f239c31a53e628b3a06a8e6fff5ed57c
    name: 1.2 Discretizing ODEs
    parent: 5cae4847c59aa247c7673c0c6b0abef1
    weight: 130
parent_title: 'Unit 1: Numerical Integration of Ordinary Differential Equations'
title: 1.2 Discretizing ODEs
type: course
uid: f239c31a53e628b3a06a8e6fff5ed57c

---

*   [<Pre-requisite Material]({{< baseurl >}}/sections/numerical-integration-of-ordinary-differential-equations/overview2/1690r-pre-requisite-material2)
*   [1.2.1First-Order ODEs]({{< baseurl >}}/sections/numerical-integration-of-ordinary-differential-equations/discretizing-odes)
*   [1.2.2An Example of First Order ODE]({{< baseurl >}}/sections/numerical-integration-of-ordinary-differential-equations/discretizing-odes/1690r-an-example-of-first-order-ode)
*   [1.2.3Discretization]({{< baseurl >}}/sections/numerical-integration-of-ordinary-differential-equations/discretizing-odes/1690r-discretization)
*   [1.2.4The Forward Euler Method]({{< baseurl >}}/sections/numerical-integration-of-ordinary-differential-equations/discretizing-odes/1690r-the-forward-euler-method)
*   [1.2.5The Midpoint Method]({{< baseurl >}}/sections/numerical-integration-of-ordinary-differential-equations/discretizing-odes/1690r-the-midpoint-method)
*   [\>An Example of First Order ODE]({{< baseurl >}}/sections/numerical-integration-of-ordinary-differential-equations/discretizing-odes/1690r-an-example-of-first-order-ode)

1.2.1 First-order ODEs
----------------------

[Measurable Outcome 1.1]({{< baseurl >}}/sections/measurable-outcome-index/#anchorMO11), [Measurable Outcome 1.2]({{< baseurl >}}/sections/measurable-outcome-index/#anchorMO12)

Many interesting physical phenomena can be modeled by a first-order ODE of the form

| \\\[u\_ t=f(u(t)), u(1)=u\_0, 0<t<T,\\\] | (1.1) 

where \\(u(t)\\) is the time-dependent state of the system, \\(u\_ t=du/dt\\) is the time-derivative of the state, \\(f(u(t))\\) is the forcing function depending on the state, \\(u\_0\\) is the initial condition, and \\(0<t<T\\) indicates that we want to solve the problem forward in time until time \\(t=T\\). We will begin by considering scalar problems where \\(u(t)\\in \\mathbb {R}\\) (a real number), but in [1.6 Systems of ODE's and Eigenvalue Stability]({{< baseurl >}}/sections/numerical-integration-of-ordinary-differential-equations/systems-of-odes-and-eigenvalue-stability) we will extend to the vector-valued case where \\(\\mathbf{u}(t)\\in \\mathbb {R}\\) is a \\(d\\)-dimensional state vector.

Example
-------

Consider transient heat transfer associated to convective heating or cooling (see [16\. Unified notes on Thermodynamics and Propulsion, Section 18.3](http://web.mit.edu/16.unified/www/SPRING/propulsion/notes/node129.html)). The first law states that the heat into the object is given by the product \\(\\rho V c T\_ t\\) where \\(\\rho\\) is the density, \\(V\\) is the volume, and \\(c\\) is the specific heat. Let \\(h\\) be the heat transfer coefficient and \\(A\\) be the surface area of the body, then the time evolution of temperature is given by

| \\\[A h (T-T\_\\infty ) = - \\rho V c T\_ t. \\label{eq:evtemp}\\\] | (1.2) 

Let \\(u(t)\\) be the non-dimensional temperature difference \\((T-T\_\\infty )/(T\_ i-T\_\\infty )\\) where \\(T(t)\\) is the time-dependent temperature in the body (assumed constant throughout, i.e., small Biot number), \\(T\_\\infty\\) is the surrounding ambient temperature, and \\(T\_ i\\) is the initial temperature of the body at time \\(t=0\\). Then the governing equation is

| \\\[u\_ t = -\\lambda u\\\] | (1.3) 

where \\(\\lambda = \\frac{h A}{\\rho V c}\\). The initial condition is \\(u(0)=1\\).

Write down the analytical solution to the initial value problem and plot it in MATLAB® for values \\(h=3\\), \\(A=4\\), \\(\\rho =10\\), \\(V=9\\), and \\(c=1\\). What is the value of \\(u(2)\\)? Please answer with at least 3 significant digits.  

Exercise 1

Numerical Response

CheckShow Answer

BackPre-requisite Material ContinueAn Example of First Order ODE