---
course_id: 16-90-computational-methods-in-aerospace-engineering-spring-2014
layout: course_section
parent_title: 1.3 Order of Accuracy
title: 1.3 Order of Accuracy
type: course
uid: 09523d4baafc8f4ce9b7d3d67ad30e7b

---

*   [<Local Truncation Error]({{< baseurl >}}/sections/numerical-integration-of-ordinary-differential-equations/order-of-accuracy/1690r-local-truncation-error)
*   [1.3.1Errors]({{< baseurl >}}/sections/numerical-integration-of-ordinary-differential-equations/order-of-accuracy)
*   [1.3.2Local Truncation Error]({{< baseurl >}}/sections/numerical-integration-of-ordinary-differential-equations/order-of-accuracy/1690r-local-truncation-error)
*   [1.3.3Local Order of Accuracy]({{< baseurl >}}/sections/numerical-integration-of-ordinary-differential-equations/order-of-accuracy/1690r-local-order-of-accuracy)
*   [1.3.4Definition of Multi-Step Methods]({{< baseurl >}}/sections/numerical-integration-of-ordinary-differential-equations/order-of-accuracy/1690r-definition-of-multi-step-methods)
*   [1.3.5Example of Most Accurate Multi-Step Method]({{< baseurl >}}/sections/numerical-integration-of-ordinary-differential-equations/order-of-accuracy/1690r-example-of-most-accurate-multi-step-method)
*   [\>Definition of Multi-Step Methods]({{< baseurl >}}/sections/numerical-integration-of-ordinary-differential-equations/order-of-accuracy/1690r-definition-of-multi-step-methods)

1.3.3 Local Order of Accuracy
-----------------------------

[Measurable Outcome 1.5]({{< baseurl >}}/sections/measurable-outcome-index/#anchorM15), [Measurable Outcome 1.8]({{< baseurl >}}/sections/measurable-outcome-index/#anchorM18), [Measurable Outcome 1.10]({{< baseurl >}}/sections/measurable-outcome-index/#anchorM110)

Suppose we are given a numerical method for solving \\(u\_ t = f(u,t)\\) which we write in the following form,

| \\\[v^{n+1} = N(v^{n+1},v^ n,v^{n-1}, \\ldots , {\\Delta t})\\\] | (1.48) 

For simplicity, the possible dependence on \\(t\\) at various \\(n\\) has been omitted in the definition of \\(N\\) (though it should be there). The local truncation error, \\(\\tau\\), is defined as,

| \\\[\\tau \\equiv N(u^{n+1},u^ n,u^{n-1}, \\ldots , {\\Delta t}) - u^{n+1}, \\label{equ:lte}\\\] | (1.49) 

and the local order of accuracy \\(p\\) is,

| \\\[&#124;\\tau &#124; = O({\\Delta t}^{p+1}) \\qquad \\mbox{as} \\qquad {\\Delta t}\\rightarrow 0.\\\] | (1.50) 

Note: the local order of accuracy is defined to be one less than the order of the leading term of the local truncation error so that the local and global accuracy will be the same.

**Exercise 1** What is the local order of accuracy for the forward Euler method?

Exercise 1

 p=0

 p=1

 p=2

 None of the above

**Exercise 2** What is the local order of accuracy for the midpoint method?

Exercise 2

 p=0

 p=1

 p=2

 None of the above

CheckShow Answer

BackLocal Truncation Error ContinueDefinition of Multi-Step Methods