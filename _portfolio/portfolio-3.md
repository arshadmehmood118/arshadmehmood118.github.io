---
title: "Development of Electronic Structure Visualization Tools"
excerpt: "Click on the above [link](https://arshadmehmood118.github.io/portfolio/portfolio-3/) to read about it. <br/><br/><img src='/images/EDR.png'>"
collection: portfolio
---

## A Toolkit to Understanding Orbital Overlap and Chemical Reactivity

It is a common practice to treat the chemical reactivity using a two-dimensional picture; charge-controlled reactions *vs* the orbital-controlled reactions. The partial atomic charges and molecular electrostatic potential (ESP) surface plots obtained from the calculated wavefunctions are extensively used to rationalize the charge-controlled processes. However, there are many systems where these computed quantities alone give an incomplete picture of reactivity. The common method to overcome the limitations of partial charges and ESP is to include the contributions of orbitals, and this is done by visualizing the frontier molecular orbitals. However, due to the delocalized nature of molecular orbitals, this method has a limitation of visualizing multiple pictures, not just one picture as used for ESP plots.

My Ph.D. work developed a descriptor of the electronic structure intended to more effectively bridge the gap between classical analyses of individual orbitals and the visualization of chemically intuitive quantities on the surface of the molecule. I developed the Electron Delocalization Range Function, \( EDR(\vec{r} ; d) \), and its derived interpretative tools, Orbital Overlap Distance, \( D(\vec{r}) \), and Atomic-averaged Overlap Distance, \( D_A \) \cite{14-17}. I applied these tools to study the electron delocalization in stretched and compressed chemical bonds, and as a partner to the electrostatic potential maps and atomic partial charges.

The major tool \( EDR(\vec{r} ; d) \) quantifies the extent to which the molecular orbitals around point \( \vec{r} \) in a calculated wavefunction overlap with a hydrogenic "test function" orbital of width \( d \) centered at \( \vec{r} \):
$$
EDR(\vec{r} ; d)=\int d^3 \vec{r}^{\prime} g_d\left(\vec{r}, \vec{r}^{\prime}\right) \gamma\left(\vec{r}, \vec{r}^{\prime}\right),
$$
where the test function is given by
$$
g_d\left(\vec{r}, \vec{r}^{\prime}\right)=\rho^{-\frac{1}{2}}(\vec{r})\left(\frac{2}{\pi d^2}\right)^{\frac{3}{4}} \exp \left(-\frac{\left|\vec{r}-\vec{r}^{\prime}\right|^2}{d^2}\right)
$$

