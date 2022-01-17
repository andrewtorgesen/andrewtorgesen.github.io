---
layout: doc
title: "Ceres Solver Tutorial"
subtitle: "Tutorial and experiments in PGO with Ceres."
featured_image: /images/projects/pgo.png
active: true
---

**[Try out the tutorial!](https://notes.andrewtorgesen.com/doku.php?id=public:ceres)**

Introductory slides:

{::nomarkdown}
<div>
  <div style="position:relative;padding-top:56.25%;">
    <iframe src="https://notes.andrewtorgesen.com/doku.php?do=export_revealjs&id=public:ceres-slides&size=2000x1000#/" frameborder="0" allowfullscreen
      style="position:absolute;top:0;left:0;width:100%;height:100%;"></iframe>
  </div>
</div>
{:/}

I completed this project in my free time while in graduate school, where part of my research involved multi-agent collaborative localization and mapping. One of the most popular backend optimizers for simultaneous localization and mapping (SLAM) is [Ceres Solver](http://ceres-solver.org/), Google's nonlinear least squares solver. Ceres is a C++ library, but in the interest of rapid prototyping multi-agent SLAM scenarios, I contributed to some [open source Python bindings](https://github.com/Edwinem/ceres_python_bindings) for the solver and also made Python wrappers of my C++ geometry library and corresponding [measurement factor implementations](https://github.com/goromal/ceres-factors). 

With these Python bindings, I took things one step further and wrote up [this tutorial with several robotics estimation examples](https://notes.andrewtorgesen.com/doku.php?id=public:ceres) with the two-fold goal of teaching my lab mates about Ceres and learning more of the nuanced details of the library. I put together the slides above to present the tutorial to my lab, introducing the challenges of optimization on the manifold and how Ceres can be used to solve SLAM-related problems. The presentation sparked interest from the lab, and one project actually subsequently incorporated the Python wrappers into its SLAM algorithm prototyping efforts. The libraries I developed for this effort have continued to be useful in my personal projects, validating the original effort I invested into their documentation and correctness.