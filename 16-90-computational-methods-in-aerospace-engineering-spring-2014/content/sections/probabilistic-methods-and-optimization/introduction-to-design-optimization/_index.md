---
course_id: 16-90-computational-methods-in-aerospace-engineering-spring-2014
layout: course_section
menu:
  leftnav:
    identifier: 6f317b0d95c1d32cf178c9fdbae632d2
    name: 3.6 Introduction to Design Optimization
    parent: 487c3b15ab67d7c95cffa6b147049d0c
    weight: 1110
parent_title: 'Unit 3: Probabilistic Methods and Optimization'
title: 3.6 Introduction to Design Optimization
type: course
uid: 6f317b0d95c1d32cf178c9fdbae632d2

---

*   [<Importance Sampling]({{< baseurl >}}/sections/probabilistic-methods-and-optimization/variance-reduction-techniques-for-the-monte-carlo-method/1690r-importance-sampling)
*   [3.6.1Design Optimization]({{< baseurl >}}/sections/probabilistic-methods-and-optimization/introduction-to-design-optimization)
*   [3.6.2Gradient Based Optimization]({{< baseurl >}}/sections/probabilistic-methods-and-optimization/introduction-to-design-optimization/1690r-gradient-based-optimization)
*   [3.6.3Unconstrained Gradient-Based Optimization Methods]({{< baseurl >}}/sections/probabilistic-methods-and-optimization/introduction-to-design-optimization/1690r-unconstrained-gradient-based-optimization-methods)
*   [3.6.4Finite Difference Methods]({{< baseurl >}}/sections/probabilistic-methods-and-optimization/introduction-to-design-optimization/1690r-finite-difference-methods)
*   [3.6.5The 1d Search]({{< baseurl >}}/sections/probabilistic-methods-and-optimization/introduction-to-design-optimization/1690r-the-1d-search)
*   [\>Gradient Based Optimization]({{< baseurl >}}/sections/probabilistic-methods-and-optimization/introduction-to-design-optimization/1690r-gradient-based-optimization)

3.6.1 Design Optimization
-------------------------

[Measurable Outcome 3.17]({{< baseurl >}}/sections/measurable-outcome-index/#anchorMO317)

Engineers are often interested in solving design problems where the best possible design is selected from all possible alternatives. A design problem can be written as an optimization problem, with a set of design variables, objective functions and constraints, defined below.

**Design variables:** Design vector \\(x\\) contains \\(n\\) variables that form the design space. During design space exploration or optimization we change the entries of \\(x\\) in some rational fashion to achieve a desired effect. e.g. , design variables might be wing span, number of engines, airfoil geometries, etc.

**Objective Functions:** The objective can be a vector \\(J\\) of \\(z\\) system responses or characteristics we are trying to maximize or minimize, \\(J = \[ J\_1 J\_2 \\ldots J\_ z \]^ T\\). In many cases the objective is a scalar function, but for real systems often we attempt multi-objective optimization. Here we will consider only a scalar objective, \\(J\\).

**Constraints:** Constraints act as boundaries of the design space and typically occur due to finiteness of resources or technological limitations of some design variables. Often, but not always, optimal designs lie at the intersection of several active constraints.

We will write our optimization problem as follows:

| \\\[\\min \_ x J(x) \\\\ s.t. c(x) = 0 \\\\ g(x) \\leq 0 \\\\ x\_{i}^{l} \\leq x\_ i \\leq x\_{i}^{u}, i = 1, \\ldots , n.\\\] | (3.66) 

Here, \\(x \\in \\mathbb {R}^ n\\) is the vector of \\(n\\) design variables, \\(J(x):\\mathbb {R}^ n \\to \\mathbb {R}\\) is the scalar objective function, \\(c(x):\\mathbb {R}^ n \\to \\mathbb {R}^{m\_1}\\) is a vector that defines the \\(m\_1\\) equality constraints, and \\(g(x):\\mathbb {R}^ n \\to \\mathbb {R}^{m\_2}\\) is a vector that defines the \\(m\_2\\) inequality constraints. \\(x\_{i}^{l} \\in \\mathbb {R}^ n\\) and \\(x\_{i}^{u} \\in \\mathbb {R}^ n\\) define lower and upper bounds, respectively, for the \\(i\\)th design variable \\(x\_ i\\).

The resulting optimization problem is typically solved using numerical optimization methods. In this section, we will discuss some basic approaches to solving optimization problems.

BackImportance Sampling ContinueGradient Based Optimization