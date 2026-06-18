---
title: "DASH: A Dimensionality Reduction Method for Large-Scale Convex MIQP with Applications in Subset Portfolio Selection"
date: 2026-04-01
tags: ["convex optimization", "portfolio selection", "mixed-integer programming", "MIQP", "subset selection", "Gurobi"]
author: ["Pinzhang (Jack) Cheng"]
description: "Master's thesis proposing DASH, a dimensionality reduction method for large-scale convex MIQPs, with applications to subset portfolio selection."
summary: "This thesis proposes DASH (Decreasing Active Set Hierarchy), a dimensionality reduction method that improves incumbent solutions from MIP solvers for subset selection problems formulated as MIQPs, evaluated against Gurobi on sparse portfolio selection."
editPost:
    URL: "https://www.unsw.edu.au/"
    Text: "UNSW Sydney"

---

---

##### Download

+ [Thesis (PDF)](DASH_master.pdf)

---

##### Abstract

Subset selection problems as MIPs (Mixed Integer Programs) are NP-hard. For large-scale problems, it is infeasible to find global optimal solutions in a reasonable time and good-quality incumbent solutions are sought after with MIP solvers in practice. This thesis proposes DASH (Decreasing Active Set Hierarchy)—a dimensionality reduction method that improves the MIP solver performance for a subclass of best subset selection problems that can be formulated as MIQPs (Mixed Integer Quadratic Programs). We develop and evaluate the performance of DASH in the subset portfolio selection problem with comparison to Gurobi, a commercial MIP solver. In addition to the problem size, the difficulty of a problem is related to the condition number of the covariance matrix and the box constraint on portfolio weights. An extensive set of numerical experiments with varying problem configurations shows that DASH offers consistent and significant improvement of incumbent solutions when the problem is difficult to solve by Gurobi. In particular, the magnitude and duration of improvement by DASH scale with the difficulty of the problem.

---

##### Details

+ **Degree:** Master of Mathematics
+ **Institution:** School of Mathematics and Statistics, UNSW Sydney
+ **Supervisor:** Dr Sarat Moka
+ **Submitted:** April 2026

---

##### Citation

Cheng, Pinzhang (Jack). 2026. "DASH: A Dimensionality Reduction Method for Large-Scale Convex MIQP with Applications in Subset Portfolio Selection." Master of Mathematics thesis, University of New South Wales.

```bibtex
@mastersthesis{Cheng2026,
author = {Pinzhang (Jack) Cheng},
year = {2026},
title = {DASH: A Dimensionality Reduction Method for Large-Scale Convex {MIQP} with Applications in Subset Portfolio Selection},
school = {University of New South Wales},
type = {Master of Mathematics thesis}
}
```
