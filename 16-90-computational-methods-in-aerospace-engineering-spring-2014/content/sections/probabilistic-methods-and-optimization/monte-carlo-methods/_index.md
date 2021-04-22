---
course_id: 16-90-computational-methods-in-aerospace-engineering-spring-2014
layout: course_section
menu:
  leftnav:
    identifier: 2733fa33374fcb88814c413cb75b3483
    name: 3.3 Monte Carlo Methods
    parent: 487c3b15ab67d7c95cffa6b147049d0c
    weight: 1010
parent_title: 'Unit 3: Probabilistic Methods and Optimization'
title: 3.3 Monte Carlo Methods
type: course
uid: 2733fa33374fcb88814c413cb75b3483

---

*   [<The Central Limit Theorem]({{< baseurl >}}/sections/probabilistic-methods-and-optimization/review-of-probability-and-statistics/1690r-the-central-limit-theorem)
*   [3.3.1Introduction]({{< baseurl >}}/sections/probabilistic-methods-and-optimization/monte-carlo-methods)
*   [3.3.2Monte Carlo Analysis]({{< baseurl >}}/sections/probabilistic-methods-and-optimization/monte-carlo-methods/1690r-monte-carlo-analysis)
*   [3.3.3Monte Carlo Example]({{< baseurl >}}/sections/probabilistic-methods-and-optimization/monte-carlo-methods/1690r-monte-carlo-example)
*   [3.3.4Inversion Method for Sampling]({{< baseurl >}}/sections/probabilistic-methods-and-optimization/monte-carlo-methods/1690r-inversion-method-for-sampling)
*   [\>Monte Carlo Analysis]({{< baseurl >}}/sections/probabilistic-methods-and-optimization/monte-carlo-methods/1690r-monte-carlo-analysis)

3.3.1 Introduction
------------------

[Measurable Outcome 3.3]({{< baseurl >}}/sections/measurable-outcome-index/#anchorMO33)

In the previous section, we reviewed some basic concepts from probability theory. We will now move on to applying some of those concepts, and developing probabilistic tools for engineering and design. Before we move ahead to the units introducing these tools, we will spend some time emphasizing why probabilistic analysis is important in engineering analysis and design.

Observe the two flow fields in Figure [3.1](/coursemedia/16-90-computational-methods-in-aerospace-engineering-spring-2014/b64f5d6e363c7c81d034d9b2ac56f6e7_xiu_karniadakis_2003_pc_fluid_mechanics.png) below. Both represent numerical simulations of a flow past a cylinder at a Reynolds number of 100. The upper flow field only incorporates deterministic effects, in particular, the inlet flow velocity is treated as a fixed, deterministic variable. In contrast, the flow field in the lower plot, treats the inlet velocity as a random variable, i.e., the inlet flow velocity is modeled as the sum of the fixed velocity used to generate the first plot and, an additional random component that models noise.

![This figure shows the oscillations of a vorticity field for flow past a cylinder.  The top panel, showing regular oscillations, is from a deterministic inflow, while the bottom panel shows the uneven field when the inflow is random.](/coursemedia/16-90-computational-methods-in-aerospace-engineering-spring-2014/b64f5d6e363c7c81d034d9b2ac56f6e7_xiu_karniadakis_2003_pc_fluid_mechanics.png)

**Figure 3.1**: Vorticity field for flow past a cylinder: Upper: Deterministic inflow; Lower: Mean solution with random inflow. (Courtesy of Elsevier, Inc., [http://www.sciencedirect.com.](http://www.sciencedirect.com/) Used with permission. Source: Xiu, Dongbin, and George Em Karniadakis. "Modeling uncertainty in flow simulations via generalized polynomial chaos." _Journal of Computational Physics_ 187, no. 1 (2003): 137-167.)

Recall, your experiments in the wind tunnel, where you studied flow past an obstacle. Even though the experiment required a fixed inlet velocity, it is easy to see that enforcing a fixed velocity in the wind tunnel is not possible. Indeed, the actual inlet velocity in those experiments will be a random variable with the mean as the flow velocity we wish to study, plus some random noise. The figure above tells us that such random effects can have a substantial impact on the flow field.

Engineering systems operate in a world where many such random effects are encountered. Our analysis has to include such effects and our design has to be robust to handle such uncertainties. Engineering systems designed in this way are likely to be more reliable and provide better performance than the ones designed with a deterministic analysis.

BackThe Central Limit Theorem ContinueMonte Carlo Analysis