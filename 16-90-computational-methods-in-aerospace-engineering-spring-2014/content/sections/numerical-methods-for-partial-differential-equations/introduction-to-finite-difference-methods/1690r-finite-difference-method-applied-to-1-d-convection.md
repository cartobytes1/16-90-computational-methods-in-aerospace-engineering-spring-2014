---
course_id: 16-90-computational-methods-in-aerospace-engineering-spring-2014
layout: course_section
parent_title: 2.3 Introduction to Finite Difference Methods
title: 2.3 Introduction to Finite Difference Methods
type: course
uid: 431a74fb7dca19ce0c6fe4b6a0a6446d

---

*   [<Finite Difference Methods]({{< baseurl >}}/sections/numerical-methods-for-partial-differential-equations/introduction-to-finite-difference-methods/1690r-finite-difference-methods)
*   [2.3.1Finite Difference Approximations]({{< baseurl >}}/sections/numerical-methods-for-partial-differential-equations/introduction-to-finite-difference-methods)
*   [2.3.2Finite Difference Methods]({{< baseurl >}}/sections/numerical-methods-for-partial-differential-equations/introduction-to-finite-difference-methods/1690r-finite-difference-methods)
*   [2.3.3Finite Difference Method Applied to 1-D Convection]({{< baseurl >}}/sections/numerical-methods-for-partial-differential-equations/introduction-to-finite-difference-methods/1690r-finite-difference-method-applied-to-1-d-convection)
*   [2.3.4Forward Time-Backward Space FTBS]({{< baseurl >}}/sections/numerical-methods-for-partial-differential-equations/introduction-to-finite-difference-methods/1690r-forward-time-backward-space--ftbs-)
*   [\>Forward Time-Backward Space FTBS]({{< baseurl >}}/sections/numerical-methods-for-partial-differential-equations/introduction-to-finite-difference-methods/1690r-forward-time-backward-space--ftbs-)

2.3.3 Finite Difference Method applied to 1-D Convection
--------------------------------------------------------

[Measurable Outcome 2.2]({{< baseurl >}}/sections/measurable-outcome-index/#anchorMO22), [Measurable Outcome 2.3]({{< baseurl >}}/sections/measurable-outcome-index/#anchorMO23), [Measurable Outcome 2.9]({{< baseurl >}}/sections/measurable-outcome-index/#anchorMO29), [Measurable Outcome 2.10]({{< baseurl >}}/sections/measurable-outcome-index/#anchorMO210)

In this example, we solve 1-D convection,

| \\\[\\frac{\\partial U}{\\partial t} + u\\frac{\\partial U}{\\partial x} = 0,\\\] | (2.58) 

using a central difference spatial approximation with a forward Euler time integration,

| \\\[\\frac{U\_ i^{n+1}-U\_ i^ n}{{\\Delta t}} + u\_{i}^ n\\delta \_{2x} U^ n\_{i} = 0.\\\] | (2.59) 

Note: this approximation is the Forward Time-Central Space method from Equation ([2.57](javascript: void(0))) with the diffusion terms removed.

Specifically, we will use a constant velocity \\(u=1\\) and set the initial condition to be a _Gaussian disturbance_:

| \\\[U\_0(x) = 0.75e^{-\\left(\\frac{x-0.5}{0.1}\\right)^2}.\\\] | (2.60) 

We consider the domain \\(\\Omega =\[0.1\]\\), with periodic boundary conditions. A MATLAB® script that implements this algorithm is:

% This MATLAB script solves the one-dimensional convection
% equation using a finite difference algorithm.  The
% discretization uses central differences in space and forward
% Euler in time.

clear all;
close all;

% Number of points
Nx = 50;
x = linspace(0,1,Nx+1)
dx = 1/Nx;

%velocity
u=1;

% Set final time
tfinal = 10.0;

% Set timestep
dt = 0.001;

% Set initial condition
Uo = 0.75\*exp(-((x-0.5)/0.1).^2)';
t = 0;

U = Uo;

% Loop until t > tfinal
while (t < tfinal)
    % Forward Euler Step
    U(2:end) = U(2:end) - dt\*u\*centraldiff(U(2:end));
    U(1) = U(end); % enforce periodicity

    % Increment time
    t = t + dt;

    % Plot current solution
    clf
    plot(x,Uo,'b\*');
    hold on;
    plot(x,U,'\*','color',\[0 0.5 0\]);
    xlabel('x','fontsize',16); ylabel('U','fontsize',16);
    title(sprintf('t = %f\\n',t));
    axis(\[0, 1, -0.5, 1.5\]);
    grid on;
    drawnow;
end

Figures [2.10](/coursemedia/16-90-computational-methods-in-aerospace-engineering-spring-2014/ffbc64a31c9b60e43abc12f2e869fcbc_ftcs1.png), [2.11](/coursemedia/16-90-computational-methods-in-aerospace-engineering-spring-2014/e13e7724631975c6c173a8de99434b2f_ftcs2.png), and [2.12](/coursemedia/16-90-computational-methods-in-aerospace-engineering-spring-2014/4d259a410f31151735aa6f0d1fa5bcf5_ftcs3.png) plot the finite difference solution at times \\(t=0.25, t=0.5\\) and \\(t=1.0\\). The exact solution for this problem has \\(U(x,t) = U\_0(x)\\) for any integer time \\((t=1,2, \\ldots ).\\). When the numerical method is run, the Gaussian disturbance is convected across the domain, however small oscillations are observed at \\(t=0.5\\) which begin to pollute the numerical solution. Eventually, these oscillations grow until the entire solution is contaminated. We will later show that the \\(FTCS\\) algorithm is unstable for any \\(\\Delta t\\) for pure convection. Thus, what we are observing is an instability that can be predicted through some analysis.

![This plot shows the finite difference solution at t=0.25 that has two lines, each with a single peak.  The first peak is centered over x=0.5, while the second peak is centered over x=0.75.](/coursemedia/16-90-computational-methods-in-aerospace-engineering-spring-2014/ffbc64a31c9b60e43abc12f2e869fcbc_ftcs1.png)

**Figure 2.10**: Forward Time-Central Space method for 1-D convection at \\(t=0.25\\)

![This plot shows the finite difference solution at t=0.5 that has the same first peak centered over x=0.5.  The second line shows the Guassian disturbances that have resulted in multiple oscillations.](/coursemedia/16-90-computational-methods-in-aerospace-engineering-spring-2014/e13e7724631975c6c173a8de99434b2f_ftcs2.png)

**Figure 2.11**: Forward Time-Central Space method for 1-D convection at \\(t=0.5\\)

![This plot shows the finite difference solution at t=1.0 that has the same first peak centered over x=0.5.  The second line shows even larger Guassian disturbances resulting in multiple oscillations.](/coursemedia/16-90-computational-methods-in-aerospace-engineering-spring-2014/4d259a410f31151735aa6f0d1fa5bcf5_ftcs3.png)

**Figure 2.12**: Forward Time-Central Space method for 1-D convection at \\(t=1.0\\)

BackFinite Difference Methods ContinueForward Time-Backward Space FTBS