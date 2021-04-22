---
course_id: 16-90-computational-methods-in-aerospace-engineering-spring-2014
layout: course_section
menu:
  leftnav:
    identifier: a3fbfbbde140393baed5af945a9316f9
    name: 1.3 Order of Accuracy
    parent: 5cae4847c59aa247c7673c0c6b0abef1
    weight: 180
parent_title: 'Unit 1: Numerical Integration of Ordinary Differential Equations'
title: 1.3 Order of Accuracy
type: course
uid: a3fbfbbde140393baed5af945a9316f9

---

*   [<The Midpoint Method]({{< baseurl >}}/sections/numerical-integration-of-ordinary-differential-equations/discretizing-odes/1690r-the-midpoint-method)
*   [1.3.1Errors]({{< baseurl >}}/sections/numerical-integration-of-ordinary-differential-equations/order-of-accuracy)
*   [1.3.2Local Truncation Error]({{< baseurl >}}/sections/numerical-integration-of-ordinary-differential-equations/order-of-accuracy/1690r-local-truncation-error)
*   [1.3.3Local Order of Accuracy]({{< baseurl >}}/sections/numerical-integration-of-ordinary-differential-equations/order-of-accuracy/1690r-local-order-of-accuracy)
*   [1.3.4Definition of Multi-Step Methods]({{< baseurl >}}/sections/numerical-integration-of-ordinary-differential-equations/order-of-accuracy/1690r-definition-of-multi-step-methods)
*   [1.3.5Example of Most Accurate Multi-Step Method]({{< baseurl >}}/sections/numerical-integration-of-ordinary-differential-equations/order-of-accuracy/1690r-example-of-most-accurate-multi-step-method)
*   [\>Local Truncation Error]({{< baseurl >}}/sections/numerical-integration-of-ordinary-differential-equations/order-of-accuracy/1690r-local-truncation-error)

1.3.1 Errors
------------

[Measurable Outcome 1.5]({{< baseurl >}}/sections/measurable-outcome-index/#anchorMO15)

There are two sources of error when we solve an ODE with a numerical method. The first is _rounding error_, due to the finite precision of floating-point arithmetic. The second is _truncation error_ (sometimes called discretization error), due to the method used. The truncation error would remain even if we were to use exact arithmetic. We will be concerned with truncation error, which is typically the dominant error source for our problems of interest. We will further define two types of truncation error: the _global error_ is the difference between the computed solution at \\(t^ n\\) and the true solution of the ODE at \\(t^ n\\), while the _local error_ is the error made in one step of the numerical method, i.e. the difference between the computed solution at \\(t^ n\\) and the solution of the ODE passing through the previous point \\((t^{n-1},v^{n-1})\\). We defer the global error to Section [1.4.2]({{< baseurl >}}/sections/numerical-integration-of-ordinary-differential-equations/convergence/1690r-convergence-of-numerical-methods) and will investigate the local error here.

BackThe Midpoint Method ContinueLocal Truncation Error