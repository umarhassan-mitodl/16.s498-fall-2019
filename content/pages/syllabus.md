---
content_type: page
description: This page provides the course policy for the MIT class 16.S498 Risk Aware
  and Robust Nonlinear Planning of Fall 2019.
learning_resource_types: []
ocw_type: CourseSection
title: Syllabus
uid: 5ab5d417-eeb2-3699-20f5-887f91821858
---

Course Meeting Times
--------------------

Sessions: 1 session / week, 2 hours / session

Course Description
------------------

Concern for safety is one of the dominant issues that arises in planning in the presence of uncertainties and disturbances. This course addresses advanced probabilistic and robust optimization-based techniques to safely control and analyze nonlinear dynamical systems in the presence of uncertainties. Specifically, we will learn how to leverage rigorous mathematical tools, such as the theory of measures and moments, the theory of nonnegative polynomials, and semidefinite programming to develop convex optimization formulations to control and analyze uncertain nonlinear dynamical systems with applications in autonomous systems and robotics. Students will acquire a comprehensive overview of state-of-the-art techniques for polynomial optimization and will be able to implement the algorithms using related open-source packages. Evaluation will be based on problem sets and a final individual or team research project.

This course introduces optimization methods of semidefinite programs for:

1.  Nonlinear Chance Optimization,
2.  Nonlinear Chance-Constrained Optimization,
3.  Nonlinear Robust Optimization, and
4.  Nonlinear Distributionally Robust Chance Constrained Optimization.

The applications of the programs include:

1.  Probabilistic and Robust Nonlinear Safety Verification,
2.  Risk Aware Control of Probabilistic Nonlinear Dynamical Systems, and
3.  Robust Control of Uncertain Nonlinear Dynamical Systems.

Prerequisites
-------------

_Linear Algebra_ (e.g., [_18.06_](/courses/18-06-linear-algebra-spring-2010)), _Convex Optimization_ (e.g., _6.215_, _[6.251](/courses/6-251j-introduction-to-mathematical-programming-fall-2009)_, _[6.255](/courses/15-093j-optimization-methods-fall-2009)_), _Probability Theory_ (e.g., _[6.431](/courses/6-041-probabilistic-systems-analysis-and-applied-probability-fall-2010)_), _Dynamical Systems_ (e.g., _[6.241](/courses/6-241j-dynamic-systems-and-control-spring-2011)_) or permission of the instructor for MIT students.

Grading Policy
--------------

{{< tableopen >}}
{{< theadopen >}}
{{< tropen >}}
{{< thopen >}}
ACTIVITIES
{{< thclose >}}
{{< thopen >}}
PERCENTAGES
{{< thclose >}}

{{< trclose >}}

{{< theadclose >}}
{{< tropen >}}
{{< tdopen >}}
Problem Sets
{{< tdclose >}}
{{< tdopen >}}
50%
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Research Project
{{< tdclose >}}
{{< tdopen >}}
50%
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

Code Repository
---------------

The codes of the lectures are available on the [fall 2019 course website on GitHub](https://github.com/jasour/rarnop19). To run the codes you need the following packages:

1.  [GloptiPoly 3](https://homepages.laas.fr/henrion/software/gloptipoly/)
2.  [Yalmip](https://yalmip.github.io/download/)
3.  SDP solvers like "[Mosek](https://www.mosek.com/downloads/)" or "[SeDuMi](https://sedumi.ie.lehigh.edu/?page_id=58)"