---
author:
- Sarah Alanazi
- Jacan Chaplais
title: Differential cross section for Compton scattering
title-slide-attributes:
    data-background-image: images/bg/title.jpg
    data-background-size: cover
    data-background-opacity: 0.3
slideNumber: 1
transition: convex
transitionSpeed: slow
date: April, 2021
lang: en-GB
...

# Outline {
data-background-image='images/bg/outline.jpg'
data-background-opacity=0.5
}

::: incremental
* Motivation
* Theory
    * Frames of reference
    * The invariant amplitude
    * Phase space integrals
* Method
:::

# Motivation {
data-background-image='images/bg/motivation.jpg'
data-background-opacity=0.3
}

## Quantum theory: old and new {
data-background-image='images/bg/motivation.jpg'
data-background-opacity=0.3
}
:::::::::::::: {.columns}
::: {.column width="45%"}
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
Duis aute irure dolor in reprehenderit in
:::
::: {.column width="45%"}
voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint
occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim
id est laborum.
:::
::::::::::::::

# Theory {
data-background-image='images/bg/theory.jpg'
data-background-opacity=0.3
}

## Kinematics {
data-background-image='images/bg/theory.jpg'
data-background-opacity=0.3
.allowframebreaks
}

During this calculation, we shall make use of two different inertial reference
frames to obtain our final result. Mandelstam variables are constructed from
the incoming and outgoing momenta of the interaction.
$$
\begin{array}{lllllllll}
s &=& (p+k)^{2} &=& p^{2}+k^{2}+2 p \cdot k &=& m^{2}+2 p \cdot k &=& m^{2}+2 p^{\prime} \cdot k^{\prime} \\
t &=& \left(p^{\prime}-p\right)^{2} &=& p^{\prime 2}+p^{2}-2 p \cdot p^{\prime} &=& 2 m^{2}-2 p \cdot p^{\prime} &=& -2 k \cdot k^{\prime} \\
u &=& \left(k^{\prime}-p\right)^{2} &=& k^{\prime 2}+p^{2}-2 k^{\prime} \cdot p &=& m^{2}-2 k^{\prime} \cdot p &=& m^{2}-2 k \cdot p^{\prime}
\end{array}
$$
Casting transition amplitudes in terms of these manifestly Lorentz invariant
quantities allows us to jump between frames with ease.


## Centre-of-mass frame {
data-background-image='images/bg/theory.jpg'
data-background-opacity=0.3
.allowframebreaks
}

Inetial frame in which sum of spatial momenta is zero.

![Centre of mass frame diagram](images/com-frame.svg)

::: notes
I should probably reduce the size of the text here

:::

## Lab frame {
data-background-image='images/bg/theory.jpg'
data-background-opacity=0.3
}

Inertial frame in which the electron is at rest. This will also be the assumed
rest frame for our particle detectors, hence _lab_ frame.

![Lab frame diagram](images/lab-frame.svg)

## Differential cross section {
data-background-image='images/bg/theory.jpg'
data-background-opacity=0.3
}

blah blah

$$
\begin{aligned}
\mathrm{d} \sigma=& \frac{1}{2 E_{\mathcal{A}} 2 E_{\mathcal{B}}\left|v_{\mathcal{A}}-v_{\mathcal{B}}\right|}\left(\prod_{f} \frac{\mathrm{d}^{3} p_{f}}{(2 \pi)^{3}} \frac{1}{2 E_{f}}\right) \\
&\left|\mathcal{M}\left(p_{\mathcal{A}}, p_{\mathcal{B}} \rightarrow\left\{p_{f}\right\}\right)\right|^{2}(2 \pi)^{4} \delta^{(4)}\left(p_{\mathcal{A}}+p_{\mathcal{B}}-\sum p_{f}\right)
\end{aligned}
$$

## Phase space integral {
data-background-image='images/bg/theory.jpg'
data-background-opacity=0.3
}

$$
\int \mathrm{d} \Pi_{2}=\int \frac{\mathrm{d}^{3} k^{\prime}}{(2 \pi)^{3} 2 E_{k^{\prime}}} \frac{\mathrm{d}^{3} p^{\prime}}{(2 \pi)^{3} 2 E_{p^{\prime}}}(2 \pi)^{4} \delta^{4}\left(p+k-k^{\prime}-p^{\prime}\right)
$$

## Invariant amplitude {
data-background-image='images/bg/theory.jpg'
data-background-opacity=0.3
}

By applying the Feynman rules to these diagrams and grouping terms, we obtain
$$
i \mathcal{M}=i e^{2}
\epsilon_{\mu \lambda^\prime}^{\ast}
\left(k^{\prime}\right)
\epsilon_{\nu \lambda}\left(k\right)
\bar{u}^{s^{\prime}}\left(p^{\prime}\right)
\left(
    \dfrac{% numerator
        \gamma^{\mu}(\not{p}+k+m) \gamma^{\nu}}
        {(p+k)^{2}-m^{2}}% denominator
    + \dfrac{% numerator
        \gamma^{\nu}
        \left(\not{p}-k^{\prime}+m\right)
        \gamma^{\mu}}
        {\left(p-k^{\prime}\right)^{2}-m^{2}}% denominator
\right)
u^{s}(p)
$$

This unwieldy expression can be simplified a little by expanding the binomials
in the denominator, and observing for the numerator
$$
\begin{aligned}
(\not{p}+m) \gamma^{\nu} u^{s}(p) &=\left(2 p^{\nu}-\gamma^{\nu} \not{p}+\gamma^{\nu} m\right) u^{s}(p) \\
&=2 p^{\nu} u^{s}(p)-\gamma^{\nu}\underbrace{(\not{p}-m) u^{s}(p)}_{
\text{Dirac equation} \implies 0
} \\
&=2_{} p^{\nu} u^{s}(p)
\end{aligned}
$$

# Evaluating invariant amplitude {
data-background-image='images/bg/inv_amp.jpg'
data-background-opacity=0.5
}

## Spin averages and polarisation sums {
data-background-image='images/bg/inv_amp.jpg'
data-background-opacity=0.5
}

Blah blah algebra

## Working out the traces {
data-background-image='images/bg/inv_amp.jpg'
data-background-opacity=0.5
}

Bluh bluh traces

# Phase space integral {
data-background-image='images/bg/phase.jpg'
data-background-opacity=0.3
}

## In centre-of-mass frame {
data-background-image='images/bg/phase.jpg'
data-background-opacity=0.3
}

blah blah

## In lab frame {
data-background-image='images/bg/phase.jpg'
data-background-opacity=0.3
}

dooda dooda

# Obtaining the cross section {
data-background-image='images/bg/cross.jpg'
data-background-opacity=0.3
}

## Function of squared momentum transfer {
data-background-image='images/bg/cross.jpg'
data-background-opacity=0.3
}


## Function of angle {
data-background-image='images/bg/cross.jpg'
data-background-opacity=0.3
}

# Results {
data-background-image='images/bg/results.jpg'
data-background-opacity=0.3
}

## QED prediction for ds/dtheta {
data-background-image='images/bg/results.jpg'
data-background-opacity=0.3
}

## QED prediction for ds/dt {
data-background-image='images/bg/results.jpg'
data-background-opacity=0.3
}

# Conclusion {
data-background-image='images/bg/conclusion.jpg'
data-background-opacity=0.4
}



<style>
.reveal {
    font-size: 26px;
}
.reveal h1.title {
    font-size: 2em;
}

p.author {
    display: inline-block;
    margin: 0 0.75em;
}

.reveal section img {
    border: none;
    box-shadow: none;
    padding: 20px;
    border-radius: 10px;
    background: rgb(38 34 64 / 72%);
    backdrop-filter: blur(3px);
}

.column { /* left col */
    padding: 0 2.5% 0 0;
}

.column + .column { /* right col */
    padding: 0 0 0 2.5%;
}
</style>