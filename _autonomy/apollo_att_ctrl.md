---
layout: doc
title: "Apollo Spacecraft Control"
subtitle: "An investigation into different forms of attitude control."
featured_image: /images/projects/apollo.gif
active: true
---

***Project description in progress...***

## Motivation

## Spacecraft Model

## Controlling the Spacecraft

### Controller Types

### Results

{::nomarkdown}
<script type="text/javascript" id="MathJax-script" async
  src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-chtml.js">
</script>

<style type="text/css">
h4 {text-align: center;}
#wrap {
   width:100%;
   margin:0 auto;
}
#left_col {
   float:left;
   width:45%;
}
#right_col {
   float:right;
   width:45%;
}
</style>

<div id="wrap">
    <div id="left_col">
        <h4>Controller with Euler Error</h4>

        $$\boldsymbol{u}=-k_q\left(\begin{bmatrix}\phi-\phi_d && \theta-\theta_d && \psi-\psi_d\end{bmatrix}^{\top}\right)+\dots$$

        <p>
        <img src="../images/projects/apollo/euler_nonlin_simple-controller-with-full-command1-svg-to-png.png">
        </p>
        <p>
        <img src="../images/projects/apollo/euler_nonlin_simple-controller-with-full-command2-svg-to-png.png">
        </p>
        <p>
        <img src="../images/projects/apollo/euler_nonlin_simple-controller-with-full-command3-svg-to-png.png">
        </p>
        <p>
        <img src="../images/projects/apollo/euler_nonlin_simple-controller-with-full-command4-svg-to-png.png">
        </p>
        <p>
        <img src="../images/projects/apollo/euler_nonlin_simple-controller-with-full-command5-svg-to-png.png">
        </p>
        <p>
        <img src="../images/projects/apollo/euler_nonlin_simple-controller-with-full-command6-svg-to-png.png">
        </p>
    </div>
    <div id="right_col">
        <h4>Controller with Tangent Space Error</h4>
        <!--$$\boldsymbol{u}=-k_q(\boldsymbol{q}\ominus\boldsymbol{q}_d)-k_{\omega}\left(\boldsymbol{\omega}-\boldsymbol{R}^{\top}\boldsymbol{R}_d\boldsymbol{\omega}_d\right)+\boldsymbol{\omega}\times\boldsymbol{J}\boldsymbol{\omega}+\dots$$-->

        $$\boldsymbol{u}=-k_q(\boldsymbol{q}\ominus\boldsymbol{q}_d)+\dots$$

        <p>
        <img src="../images/projects/apollo/manif_nonlin_simple-controller-with-full-command1-svg-to-png.png">
        </p>
        <p>
        <img src="../images/projects/apollo/manif_nonlin_simple-controller-with-full-command2-svg-to-png.png">
        </p>
        <p>
        <img src="../images/projects/apollo/manif_nonlin_simple-controller-with-full-command3-svg-to-png.png">
        </p>
        <p>
        <img src="../images/projects/apollo/manif_nonlin_simple-controller-with-full-command4-svg-to-png.png">
        </p>
        <p>
        <img src="../images/projects/apollo/manif_nonlin_simple-controller-with-full-command5-svg-to-png.png">
        </p>
        <p>
        <img src="../images/projects/apollo/manif_nonlin_simple-controller-with-full-command6-svg-to-png.png">
        </p>
    </div>
</div>

{:/}

## Conclusions


